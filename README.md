# PythonMegaCourse_Udemy_Exercises

Exercises from the Course by Udemy: "The Python Mega Course Build 10 Real World Applications", solved by myself

---------------------------------------------------------------------------------------------------------------

The next lecture will be an exercise and there will be more exercises as you progress through the course.
The exercises are difficult and sometimes tricky and I don't expect students to solve them all. Most students actually fail to solve the exercisesunless they are already familiar with Python.
The whole point of exercises is to force you to think about how to solve a problem independently. The next lecture following each exercise contains the solution where you can compare your approach.

1) Simple Function Exercise: 

Create a functionthat converts Celsius degrees toFahrenheit. The formula to convert Celsius to Fahrenheit isF= C 9/5 + 32.

In the previous exercises you used the interactive Udemy interface to write your code.For this exercise, please use your computertools (Python, editor, terminal,etc.). This will help you get used with Python in a real environment.

Once you are done check your solution against my solution which islocatedin the next lecture. Don't worry if your solution is not exactly the same as mine. As far as the solutions generate the same output, your solution is most likely correct.

2) Calculate Length Exercise: Create a function that takes any string as argument and returns the length of that string.

3) Function and Conditionals 1 Exercise: In one of the previous exercises we created the following function:

def string_length(mystring):
    return len(mystring)

Calling the function with a string as the value for the argument mystringwill return the length of that string.

However, if an integer is passed as an argument value:

string_length(10)

that wouldgenerate an error since the len() function doesn't work for integers.

Your duty is to modify the function so that if an integer is passed as an input, the function should output a message like "Sorry integers don't have length".

4)Function and Conditionals 2 Exercise: The function that we implemented in the previous exercise checks integer datatypes, but not about floats. So, please expand the conditional block so that floats are counted too.

5)Function and Conditionals 3 Exercise: 

In one of the previous exercisesyou created a function that convertedCelsius degrees to Fahrenheit:

def cel_to_fahr(c):
    f = c * 9/5 + 32
    return f

Now, the lowest possibletemperature that physicalmatter can reach is -273.15C.With that in mind, please improve the function by making itprint out a message in case a number lower than -273.15 is passed as input when calling the function.

