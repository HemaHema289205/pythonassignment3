task1 :
    In this task1 we work on functions.Function is a group of code and it must contain base condtion.In these we perform a function for finding a factorial  of a number.q  q  2
    def factorial(num):
    if num < 2:
        return 1
    else:
        return num*factorial(num-1)
    num=int(input('Enter a number: '))
    result=factorial(num)
    print(f'Factorial of {num} is: {result}')


task2 :
     In this task2 we import math module by using math module we print square root,logorithm and sine of a given number.
     import math
     num=int(input('Enter a number: '))
     print('Square root: ',math.sqrt(num))
     print('Logarithm: ',math.log(num))
     print('Sine: ',math.sin(num))
    
