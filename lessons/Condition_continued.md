# Lesson May 26th, 2020


# Concepts : String comparrison, in operator, is operator, not operator

```py
name = "Devika"
age = 23


# if name.lower() == "ben" and age > 20:
#   print("Yes, you can drive the car!")
# else:
#   print("Yes, you can fly the plane!")

# if name.lower() > "ben" and age > 20:
#   print("You can drive!") 
# else:
#   print("No, you cannot drive yet.") 


firstNamesOf8thGraders = ['Lisa', 'Michael', 'Ron', 'Mickey', 'Stuti', 'Carl']
nameToTest = 'Carl'

if nameToTest in firstNamesOf8thGraders:
  print("Yes, this is a student in my class.")
else:
  print("No, this student is not in my class.")

# Homework - find if a given salary is high, medium or low 


devikasAge = 23
carlsAge = 43

ageToTest = carlsAge

print(" ")
print(" ")

if ageToTest is devikasAge:
  print("Yes, it is Devika's age variable.")

if ageToTest is carlsAge:
  print("No, it is not Devika's age variable.")


print(" ")
print(" ")

if not 2 > 3:
  print("Yes, condition met.")
else:
  print("No, condition was not met.")


print(" ")
print(" ")

currenTime = 20
timeForDowning=13
timeForUpraisal=18


if not (currenTime >= timeForDowning and currenTime < timeForUpraisal):
  print("First Condition")
  print("activate shade mode")
else:
  print("Third Condition")
  print("deactivate shade mode")
  
```
