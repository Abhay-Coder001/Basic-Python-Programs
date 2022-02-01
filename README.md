# Python-Basic-Program-Challenge-Series
In this series i cover each topics with various easy examples for every concept i create seprate file 

#for basics
Python is case sensitive so it is important that you use the correct case, otherwise
your code will not work.
Text values need to appear in speech marks (") but numbers do
not.
When naming variables (i.e. values that you want to store
data in) you cannot use any dedicated words such as print,
input, etc. otherwise your code will not work.
When saving your files do not save them with any
dedicated words that Python already uses, such as print,
input, etc. If you do this it will not run and you will need to
rename the file before it works.
To edit a program you have saved and closed, right-click on the
file and select Edit with IDLE. If you just double-click on
the file it will only try to run it and you will not be able to edit it.

`basic things`

`addition`
answer = num1 + num2
Adds together num1 and num2 and stores the
answer in a variable called answer.

`subtraction`
answer = num1 - num2
Subtracts num2 from num1 and stores the
answer in a variable called answer.

`multiplication`
answer = num1 * num2
Multiplies num1 by num2 and stores the
answer in a variable called answer.

`division`
answer = num1 / num2
Divides num1 by num2 and stores the answer
in a variable called answer.

`whole number division`
answer = num1 // num2
A whole number division (i.e. 9//4 = 2) and
stores the answer in a variable called answer.

`diaplay the message`
print (“This is a message”)
Displays the message in the brackets. As the value we want displayed is a text value it
has the speech marks, which will not be displayed in the output. If you wanted to display
a numerical value or the contents of a variable, the speech marks are not needed.

`next line`
print (“First line\nSecond line”)
“\n” is used as a line break.

`take input`
textValue = input(“Enter a text value: ”)
Displays the question “Enter a text value: ” and stores the value the user enters in a
variable called textValue. The space after the colon allows a space to be added before
the user enters their answer, otherwise they appear squashed unattractively together.

`answer`
print (“The answer is”, answer)
Displays the text “The answer is” and the value of the variable answer.

`taking integer``
numValue = int(input(“Enter a number: ”))
Displays the question “Enter a number: ” and stores the value as an
integer (a whole number) in a variable called numValue Integers can be
used in calculations but variables stored as text cannot.



# for if else

I created ' if_else.py ' 
In this we see "If statement allow your program to make decision and change the route that is taken through
the program
In this i also cover basic concept of #Comparison_Operators
 >Operator   Description
 > ==         Equal to
 >!=         Not equal to
 > " >, <,"      Greater than, Less then
 > >=,<=      Greater than equals to, Less then equals to
  
 **Logical_Operators**
 Operator            Description
   and          Both conditions must be met
   or          Either conditions must be met

# for strings

I created 'Strings.py'
String is the technical name for text. To define a block of code as a string, you need to
include it in either double quotes (") or single quotes ('). It doesn’t matter which you use so
long as you are consistent.
There are some characters you need to be particularly careful with when inputting them
into strings. These include:
" ' \
That is because these symbols have special meanings in Python and it can get confusing if
you use them in a string.

Multiple-Line Strings
If you want to input a string across multiple lines you can either use the line break (\n) or
you can enclose the entire thing in triple quotes. This will preserve the formatting of the
text.
  address = """123
  Oldtown
  ABI 43BF"""
  print(address)
 
 
### I also introduce some functions

`len(word)`
Fnds the length of the variable called word.

`word.upper()` 
Changes the string into upper case

`print(word.capitalize())`
Displays the variable so only the first word
has a capital letter at the beginning and
everything else is in lower case.

`word.title()'
Changes a phrase so that every word
has a capital letter at the beginning
with the rest of the letters in the
word in lower case (i.e.Title Case).

`text = “ This is some text. ”
print(text.strip(“ ”))`
Removes extra characters (in this case spaces) from the start and end of a string.

`print (“Hello world”[7:10])`
Each letter is assigned an index number to
identify its position in the phrase, including
the space. Python starts counting from 0, not
1.
Therefore, in this example, it would display
the value of positions 7, 8 and 9 ,which is
“orl”.
name = firstname+surname


# for math
###I created math.py
Python can perform several mathematical functions, but these are only available when the
data is treated as either an integer (a whole number) or a floating-point (a
number with a decimal place). If data is stored as a string, even if it only contains numeric
characters, Python is unable to perform calculations with it (see page 24 for a fuller
explanation).

`import math.py`
In order to use some of the mathematical functions (math.sqrt(num)
and math.pi) you will need to import the maths
library at the start of your program. You do this by
typing import math as the first line of your
program.

`float`
num=float(input(“Enter number: “))
Allows numbers with a decimal point dividing the integer and fraction part.

`decimal places`
print(round(num,2))
Displays a number rounded to
two decimal places.

`square root`
**
To the power of
(e.g. 102 is 10**2).
math.sqrt(num)
The square root of a number, but you must have the line import
math at the top of your program for this to work.

'pie`
math.pi
Gives you pi (π) to 15 decimal places,
but you must have the line import
math at the top of your program for
this to work.

`whole number division`
x // y
Whole number division (e.g.15//2 gives
the answer 7).

`x%y`
x % y
Finds the remainder (e.g. 15%2 gives
the answer 1).

# for loop
I created loops.py
A for loop allows Python to keep repeating code a set number of times. It is sometimes
known as a counting loop because you know the number of times the loop will run
before it starts.

The range function is often used in for loops and lists the starting number, the ending
number and can also include the steps (e.g. counting in 1s, 5s or any other value you wish).

`about loop`

for i in range(1,10):
print(i)
This loop uses a variable called “i” to keep track of the number of times
the loop has been repeated. It will start i at 1 (as that is the starting
value in the range function) and repeat the loop, adding 1 to i each time
and displaying the value of i until it reaches 10 (as dictated by the range
function), where it will stop. Therefore, it will not repeat the loop a tenth
time and will only have the following output:
1, 2, 3, 4, 5, 6, 7, 8, 9

`case1`

for i in range(1,10,2):
print(i)
This range function includes a third value
which shows how much is added to i in
each loop (in this case 2). The output will
therefore be: 1, 3, 5, 7, 9

`case2`

for i in range(10,1,-3):
print(i)
This range will subtract 3 from i each
time. The output will be: 10, 7, 4
for i

# while loop

A while loop allows code to be repeated an unknown number of times
as long as a condition is being met. This may be 100 times, just the once or
even never. In a while loop the condition is checked before the code is run,
which means it could skip the loop altogether if the condition is not being
met to start with. It is important, therefore, to make sure the correct
conditions are in place to run the loop before it starts.

I created while_loop.py to cover it

# random

Python can generate random values. In reality, the values are not
completely random as no computer can cope with that; instead it uses an
incredibly complex algorithm that makes it virtually impossible to accurately
predict its outcome so, in effect, it acts like a random function.
There are two types of random value that we will be looking at:

Random numbers within a specified range;
A random choice from a range of items that are input.

To use these two options, you will need to import the random library. You do
this by typing import random at the start of your program

For this I created random.py 

### Some useful example of random which we use in random.py

`import random`
This must appear at the start of your program otherwise the random function will not
work.

`num = random.random()`
Selects a random floating-point number between 0 and 1 and
stores it in a variable called “num”. If you want to obtain a
larger number, you can multiply it as shown below:
import random
num = random.random()
num = num * 100
print(num)

`num = random.randint(0,9)`
Selects a random whole number
between 0 and 9 (inclusive).

`num1 = random.randint(0,1000)
num2 = random.randint(0,1000)
newrand = num1/num2
print(newrand)`
Creates a random floating-point number by
creating two random integers within two
large ranges (in this case between 0 and 1000) and dividing one by the other.

`num = random.randrange(0,100,5)`
Picks a random number between the
numbers 0 and 100 (inclusive) in steps of five,
i.e. it will only pick from 0, 5, 10, 15, 20, etc.

`colour = random.choice([“red”,“black”,“green”])`
Picks a random value from the options “red”, “black” or “green” and stores it as the
variable “colour”. Remember: strings need to include speech marks but numeric data
does not.

# Turtle Graphics
For this I created turtle.py

It is possible to draw using a turtle in Python. By typing in commands
and using loops, you can create intricate patterns. Here is how it works.
A turtle will travel along a path that you define, leaving a pen mark behind it. As you control
the turtle, the pattern that is left is revealed. To draw the pentagon shown below you would
type in the following code.

import turtle

turtle.shape("turtle")
for i in range(0,5):
 turtle.forward(100)
 turtle.right(72)
turtle.exitonclick()

By combining these simple shapes and using nested loops (i.e. loops inside other loops)
it is possible to create beautiful patterns very easily.

`import turtle`
This line needs to be included
at the beginning of your
program to import the turtle
library into Python, allowing
you to use the turtle functions.

`scr = turtle.Screen()`
Defines the window as being
called “scr”. This means we can
use the shorthand “scr”, rather
than having to refer to the window
by its full name each time.

`scr.bgcolor(“yellow”)`
Sets the screen background
colour to yellow. By default, the
background colour will be
white unless it is changed.

`turtle.pensize(3)`
Changes the turtle pen size
(the thickness of the line that is
drawn) to 3. By default, this is 1
unless it is changed.

`turtle.penup()`
Removes the pen from
the page so that as the
turtle moves it does not
leave a trail behind it.

`turtle.pendown()`
Places the pen on the
page so that when the
turtle moves it will
leave a trail behind it.
By default, the pen is
down unless specified
otherwise.

`turtle.forward(50)`
Moves the turtle forward 50
steps.

`turtle.left(120)`
Turns the turtle 120° to
the left (counter
clockwise). turtle.right(90)
Turns the turtle 90° to
the right (clockwise).

`turtle.showturtle()`
Shows the turtle on the screen.
By default, the turtle is
showing unless specified
otherwise.

`turtle.hideturtle()`
Hides the turtle so it is not
showing on the screen.

`turtle.shape(“turtle”)`
Changes the shape of the turtle to look like a turtle
. By default, the turtle will look like a small arrow.

`turtle.exitonclick()`
When the user clicks on the
turtle window it will
automatically close.

`turtle.begin_fill()`
Entered before the code that draws a shape so it
knows to fill in the shape it is drawing.

`turtle.end_fill()`
Entered after the code that is drawing the shape to
tell Python to stop filling in the shape.

`turtle.color(“black”,“red”)`
Defines the colours filling in the shape. This
example will make the shape have a black outline
and a red fill. This needs to be entered before the
shape is drawn.


