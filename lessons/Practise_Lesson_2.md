# Lesson June 1, 2020

# Concept - Tight Coupling, Loose coupling.

```py

import math

# listOfOddNo=[1,3,5,7,9,11,13,15]

# def addToOddNoList(newNoToAdd):
#  print(" ")
#  print("the new no given is {}".format(newNoToAdd))
#  if newNoToAdd  in listOfOddNo:
#   print("ERROR:Number already exists.")
#   return
#  #new number to add must be odd
#  if not newNoToAdd % 2 == 0:
#    listOfOddNo.append(newNoToAdd)
#  else:
#    print("ERROR: Even numbers not allowed!")
   
    
# print(listOfOddNo)
# addToOddNoList(12)
# print(listOfOddNo)


#to print square roots in Loop
def squarePower(numberToBeSquared):
 square = numberToBeSquared ** 2
 return square

def squareRoot(numberToBeSquared):
  squareRoot = math.sqrt(numberToBeSquared)
  return squareRoot

def printWithBlankLine(input):
  print(" ")
  print(input)

for num in [2,4,6,8,10,12]:
    square = squarePower(num)
    stringToPrint = "the square power of {} is {}".format(num,square)
    printWithBlankLine(stringToPrint)

for num in [169, 181, 124, 68, 72, 36]:
    squareRootAns = squareRoot(num)
    stringToPrint = "the square root of {} is {}".format(num,squareRootAns)
    printWithBlankLine(stringToPrint)



# parctical marks and theory marks
# > 25            and > 65  or total mark > 80 [Pass] else [fail]


total_mmarks=89
marks_practical=25
marks_theory=38

if marks_practical + marks_theory > 80:
  print("condition-1")
  print("You have passed the test.")
elif marks_practical >= 25 and marks_theory >= 40:
  print("condition-2")
  print("You have passed the test.")
else:
  print("condition-3")
  print("You have NOT passed the test.")


# if(marks_practical > 25):
#   print("score is eligible to pass the practical exam")
#   print("condition-1")
# elif(marks_theory < 65):
#   print("score is not eligible to pass the exam")
#   print("condition-2")
# else:
#   print("you have qualified this exam")
#   print("condition-3")



def addToOddNoList(newNoToAdd, inputList):
 print(" ")
 print("the new no given is {}".format(newNoToAdd))
 if newNoToAdd  in inputList:
  print("ERROR:Number already exists.")
  return
  
 if not newNoToAdd % 2 == 0:
   inputList.append(newNoToAdd)
 else:
   print("ERROR: Even numbers not allowed!")


listOfOddNo = [1,3,5,7,9,11,13,15]

listFromBoss = [3, 7, 9, 11, 21, 25]

addToOddNoList(73, inputList=listOfOddNo)

addToOddNoList(34, inputList=listFromBoss)

print(listOfOddNo)

print(listFromBoss)
```


# Questions for problems

1. Using a For loop in Python, print your name 10 times

2. Using a For loop in Python, print all even numbers between 0 and 101

3. Do the same to print odd numbers between 0 and 101

4. Write a function in python that takes length and width of a rectangle as input parameters 
and returns area of the rectangle.

5. Write a function that takes the height in centimeters as input parameter and tells us if
the person is tall enough to go on a ride in Disney Land
