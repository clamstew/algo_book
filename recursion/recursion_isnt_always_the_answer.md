# Recursion isn't always the answer!

After most programmers learn how to code recursively, recursion starts to look like a hammer and every iterative function starts to look like a nail. The elegance and simplicity of a recursive function becomes exceedingly alluring. But recursion isn't always the perfect tool for the job. Sometimes it can actually take much longer to run through a recursive function than it does an iterative function. Other times a recursive function can have the same Big O as an iterative function, but the recursive function can cause the ever famous `SystemStackError: stack level too deep` error even though it is working as expected.