# Lesson May 31, 2020

```py

# Homework - list of 5 first even numbers 2, 4, 6, 8, 10
# write a function to add numbers to this list but you have to 
# make sure that numbers are even before you add them to the list

#def faxMachine(paper):


listOfEvenNumbers = [2, 4, 6, 8, 10]

def addToEvenNumberList(newNumberToAdd):
  print(" ")
  print("The number provides is {}".format(newNumberToAdd))
  if newNumberToAdd in listOfEvenNumbers:
    print("ERROR: Number already exists.")
    return
  
  #newNumberToAdd must be even
  if newNumberToAdd % 2 == 0:
    listOfEvenNumbers.append(newNumberToAdd)
  else:
    print("ERROR: Odd numbers not allowed!")


print(listOfEvenNumbers)
addToEvenNumberList(11)
print(listOfEvenNumbers)
addToEvenNumberList(11)


newListOfNumbers = [11, 22, 104, 99, 86, 87, 91, 90]

for currentNumberToProcess in newListOfNumbers:
  print(" ")
  print("I will now process this number : {}".format(currentNumberToProcess))
  print(" ")
  addToEvenNumberList(currentNumberToProcess)


print(listOfEvenNumbers)

```
Homework for the following
```py
import math

# listOfOddNo=[1,3,5,7,9,11,13,15]

# def addToOddNoList(newNoToAdd):
#  print(" ")
#  print("the new no given is {}".format(newNoToAdd))
#  if newNoToAdd  in listOfOddNo:
#   print("ERROR:Number already exists.")
#   return

# #new number to add must be odd
# if newNoToAdd % 1 == 0:
#  listOfOddNo.append(newNoToAdd)

# Else:
#  print("ERROR: Odd numbers not allowed!")


# print(listOfOddNo)
# addToOddNoList(12)
# print(listOfOddNo)


#to print square roots in Loop
def squareRoot(noToBeSquared):
 print(" ")
 print(noToBeSquared) 

for noToBeSquared in [2,4,6,8,10,12]:
    square= noToBeSquared ** 2
    squareRoot("the square root is {}".format(square))

if newNoToAdd % 1 ==0:
  print("error its an odd number")
  
  
  
#elif statement

total_mmarks=89
marks_practical=28
marks_theory=66

if(marks_practical > 25):
  print("score is eligible to pass the practical exam")
  print("condition-1")

elif(marks_theory < 65):
  print("score is not eligible to pass the exam")
  print("condition-2")

else:
  print("you have qualified this exam")
  print("condition-3")
```
