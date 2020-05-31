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
