# CodeCamp Notes

Lesson notes for LaunchCode's Immersive CodeCamp

some notes

1. Does a function have to have parameters?

No.

def some_function():
	print("Hello there")

some_function()

2. What happens if we call a function without providing a value for one or more
   input parameters?

We receive a type error indicating that the function requires its arguments.

def some_function(tacos, burritos):
    print(tacos)

some_function()

3. Does a function have to return a value?

No.

def some_function(num):
	i = 0
	i = num + 2

some_function(3)

4. What happens if we have a function that doesn't return a value, but we try
   to store a return value in a variable?

The variable takes on the value of the function within the function, but not
outside of the function.

def some_function(num):
	i = num + 2
	print(i)

some_function(3)

would output 5. But if we put the print(i) outside of the function we would
receive a name error indicating that i is not defined.