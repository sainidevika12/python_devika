# Lesson: May 29th, 2020

# Concept - Loops

```py
def customPrintWithEmptyLine(input):
 print(" ")
 print(input)


# customPrintWithEmptyLine( " 2 * 1 = {}".format(2*1))
# customPrintWithEmptyLine( " 2 * 2 = {}".format(2*2))
# customPrintWithEmptyLine( " 2 * 3 = {}".format(2format(2*4))
# customPrintWithEmptyLine( " 2 * 5 = {}".format(2*5))*3))
# customPrintWithEmptyLine( " 2 * 4 = {}".

for tableNumber in range(1,101):
  multiplicationValue = 2 * tableNumber
  customPrintWithEmptyLine( " 2 * {} = {} {}".format(tableNumber, multiplicationValue))
  #customPrintWithEmptyLine(tableNumber)

# Home work write a for loop solution to print square roots of the number in range

def create_design(input):
 print(" ")
 print(input)

brandNamesList = ['Brittania', 'Monaco', 'Amul', 'Mother Dairy']

def addNewBrandToTheList(nameOfNewBrand):
  if not nameOfNewBrand.strip():
    create_design("ERROR: Cannot add empty value for Brand name.")
    return
  
  if nameOfNewBrand.strip() in brandNamesList:
    create_design("ERROR: Brand name already exists in the list.")
    return

  brandNamesList.append(nameOfNewBrand.strip())
  brandNamesList.sort()

create_design("Printing the list of Brands as : {}".format(brandNamesList))

addNewBrandToTheList(nameOfNewBrand='Casio ')

create_design("Printing the list of Brands as : {}".format(brandNamesList))

addNewBrandToTheList(nameOfNewBrand=' ')

addNewBrandToTheList(nameOfNewBrand='Casio ')

create_design("Printing the list of Brands as : {}".format(brandNamesList))

# Homework - list of 5 first even numbers 2, 4, 6, 8, 10
# write a function to add numbers to this list but you have to 
# make sure that numbers are even before you add them to the list


```
