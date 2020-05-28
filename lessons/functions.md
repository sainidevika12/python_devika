# Lesson May 28, 2020

# Concept - function

```py
print(" ")

def devikas_print(input):
  print(" ")
  print(input)

# devikas_print("Can you please print the menu for the McDonalds for me!")
# devikas_print("the total bill amount at the McDonalds is $36")
# devikas_print("I am now going to call an Uber to go home.")


def multiplyBy5657(inputNumber):
  answer = 5657 * inputNumber
  return answer

def calculateTax(inputTotalSalary):
  answer = 0.25 * inputTotalSalary
  return answer

multiplicationValueFor86 = multiplyBy5657(86)
multiplicationValueFor186 = multiplyBy5657(186)
multiplicationValueFor56 = multiplyBy5657(56)
multiplicationValueFor1 = multiplyBy5657(1)
multiplicationValueFor0 = multiplyBy5657(0)

devikas_print("multiplicationValueFor86 is : {}".format(multiplicationValueFor86))
devikas_print("multiplicationValueFor186 is : {}".format(multiplicationValueFor186))
devikas_print("multiplicationValueFor56 is : {}".format(multiplicationValueFor56))
devikas_print("multiplicationValueFor1 is : {}".format(multiplicationValueFor1))
devikas_print("multiplicationValueFor0 is : {}".format(multiplicationValueFor0))

#+ - /
def multiplyBy5657(inputNumber, multiplier=5657):
  answer = multiplier * inputNumber
  return answer

multiplicationValueFor86 = multiplyBy5657(inputNumber=86, multiplier=20)
multiplicationValueFor56 = multiplyBy5657(inputNumber=56)

devikas_print("multiplicationValueFor86 is : {}".format(multiplicationValueFor86))
devikas_print("multiplicationValueFor56 is : {}".format(multiplicationValueFor56))

```

# Practised the following in if Conditions

```py
totalTime = datetime.time(0,15,00)

timeElapsed = datetime.time(0,16,00)


if timeElapsed >= totalTime:
  print("potatoes are baked")
else:
  print("Still baking.")
```
