
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
