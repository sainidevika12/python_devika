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
homework for functions
```py
print("  ")
import statistics


def create_design(input):
 print(" ")
 print(input)

# create_design("l-shape sofa")
# create_design("4 seater dining table")
# create_design("king size bed")

def calculateTax (inputTotalSalary):
  answer=0.25 * inputTotalSalary
  return answer

salaryOfEmployee1= calculateTax(5000)
salaryOfEmployee2= calculateTax(9000)
salaryOfEmployee3=calculateTax(2000)
salaryOfEmployee4=calculateTax(4000)

create_design("the total salary of employee1 after tax is : {}".format(salaryOfEmployee1))

create_design("the total salary of employee1 after tax is : {}".format(salaryOfEmployee2))

create_design("the total salary of employee1 after tax is : {}".format(salaryOfEmployee3))

create_design("the total salary of employee1 after tax is : {}".format(salaryOfEmployee4))

print(" ")

total_salary_of_employee=[1250,2250,500,1000]
total_salary_of_employee.sort(reverse= True)
print("list in descending order")
print(total_salary_of_employee)

print(" ")

total_salary_of_employee.sort()
print("list in ascending order")
print(total_salary_of_employee)

def listingDateForToday (nameOfBrand):
  answer=nameOfBrand
  return answer

listingDateForToday=nameOfBrand("amul")

create_design("brand name added today is : {}".format(listingDateForToday))
```
