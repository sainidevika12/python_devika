
# Lesson - June 8th, 2020

# For
# Functions


mahatmaDevikaStreet = [2, 3, 4, 5, 7, 10]

def multiplicationWithNumber2(inputNumber=0, temprature=23, isEven=True):
  product = 2 * inputNumber
  return product

def powerWithNumber3(inputNumber=0):
  powerResult = inputNumber ** 3
  return powerResult

for number in mahatmaDevikaStreet:
  #resultFromFunction = 2 * number
  resultFromPower = powerWithNumber3(number)
  resultFromFunction = multiplicationWithNumber2(inputNumber=resultFromPower)
  
  #print("The number is : {}".format(number))
  print("The result from the multiply function call is : {}".format(resultFromFunction))

homework-
marksInMaths=[25,27,21,18,16]

def mathScoreOfClass(input=0):
  totalMathScoreOfClass=2 * input
  return totalMathScoreOfClass

for marks in marksInMaths:
   totalMathScoreOfClass=2 + marksInMaths

print("the total marks of students in maths is = {}".format(totalMathScoreOfClass))
