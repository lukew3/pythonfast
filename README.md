# pythonfast
Learn python the fast way

## Description
With this tutorial, you can learn everything you need to know to program with python in a very short time. 

## Lessons
### Basics
#### Running code
To use python, you need to install it to your system. Then, create a file with the .py ending. Run this file in terminal or command line with `python <your-filename>.py`

#### print
`print("Hello World!")` writes `Hello World!` to your terminal. `print()` can also print numbers and variables. Just remove the `""` and write the variable or number inside the parenthesis.

#### comments
The `#` symbol is used to show the beginning of a comment. Each character after the `#` symbol on that line will not be run by the computer. `"""` can also be used for multi-line comments, with three quotes at the beginning and at the end. 

#### variables
Variables are used to hold data. 
* Numbers: `my_num = 3`
* Strings(What programmers call text): `city = "Paris"`
* Lists: `grades = ["A", "B", "B+"]`
* Or objects: `df = pd.read_csv(fp)`

You can do math with numeric variables:
```
x = 2
y = 3
z = x + y
```
In this case z will equal 5

#### if, elif, else
If statements are used when you want to run a certain piece of code if a condition is true.
```
if x > 1:
	print("x is greater than 1")
elif x < 1:
	print("x is less than 1")
else:
	print("x is equal to 1")
```

#### for loop
The for loop is used to run an action multiple times, with the values given in the loop.
This snippet will print the numbers 0, 1, 2:
```
for x in range(0, 3):
	print(x)
```
This will print each item in the list:
```
for item in my_list:
	print(item)
```

#### while loop
The while loop is used to run an action as long as the condition is true.
The following will print the value of x until x is greater than or equal to 10. 
```
x = 0
while x < 10:
	print(x)
	x = x + 1
```

#### functions
Use functions when you want to reuse a part of your code or want to split your code up to make it easier to understand. Functions must be defined before they are called.
```
# Define the function
def my_function(in_var):
	print(in_var)

# Call the function
my_function(3)
```
The variable inside the parenthesis is a parameter. Parameters are used to give data to functions, which can then manipulate that data.


## Future Lessons
* import modules
* classes
