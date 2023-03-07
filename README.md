# BIOT-Lab1
This was a simple lab to try and get started with Python. Most students had not used Python before and some had never programmed before, so this was an introductory lab meant to get us to be comfortable with Python and programming in general. 
The first program used math operators in Python to find the hypotnuse of a triangle, the long edge of the triangle, when given the two, shorter, sides. The math for this is sqrt(leg1^2+leg2^2). If this is still confusing, then going to a site like math.net/hypotenuse might help make it clearer. 
For the second program, the following is given:

\#

\# Python program with basic logic

\#

import math

\# a pair of values

x = 5

y = -4

\#

\# arithmetic using x and y

x1 = math.sqrt(x - 6)

y1 = 1 / (y + 4)

\#

\# print out the results:

print ("x1 is ", x1)

print ("y1 is ", y1)

The point of this program is to add control logic so that the program doesn't crash if it encouters a square root to some negative number. To do that, relational operators (<, >, =, !=, etc.) are used to prevent anything less than the square root of 0 to be calculated and instead telling the user that the program is not able to divide by that number.
The final program takes a given program:
\#

\# Python program with string comparison

\#

\# a pair of strings

x = "ATGCT"

y = "ATGCCA"

\#

\# compare variables x and y:

if (x < y):

print( "x is less than y" )

elif (x == y):

print( "x and y are the same" )

else:

print( "x is greater than y" )

And uses logical operators (and, or, not) to see if x is larger then y and then do other comparisons.
