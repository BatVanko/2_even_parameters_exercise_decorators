# 2_even_parameters_exercise_decorators
Create a decorator function called even_parameters. It should check if all parameters passed to a function are even numbers and only then execute the function and return the result. Otherwise, don't execute the function and return "Please use only even numbers!"

Test Code
@even_parameters
def add(a, b):
    return a + b

print(add(2, 4))
print(add("Peter", 1))

Output

6
Please use only even numbers!

