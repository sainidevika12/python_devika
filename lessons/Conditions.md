# Lesson, May 25, 2020

https://www.learnpython.org/en/Conditions


```py

# String modification upper, lower, title, split

firstName = "stuti"
lastName = "Saini"

modified_firstName = firstName.title()

print(modified_firstName)


firstNames = "Devika;Ben;Shivani;Stuti;Savita;Gauri"

firstNamesAfterSplit = firstNames.split(";")

print(" ")
print(firstNamesAfterSplit)
print(" ")
print(" ")

# Conditions
  # == : Equals 
  # >  : greater than
  # <  : less than
  # >= : greater than or Equals
  # <= : less than or Equals

targetTemprature = 23
currentRoomTemprature = 13

if currentRoomTemprature <= targetTemprature:
  print("Fan mode")
  print("If condition is succesful")
  print("Devika has suuccessfully learned the conditons in Python. Hooray!")
else:
  print("Cooling!")
  print("I know it very hot but be patient it will get cool soon.")
  print("Please do not stand in front of the ac when it is cooling.")

print(" ")
print(" ")
# Conditons : And   Or
passwordVerified = False
thumbPrintVerification = False
residentBuzzerValid = False
voiceRecognition = False

if (passwordVerified == True or thumbPrintVerification == True or voiceRecognition == True) or residentBuzzerValid == True:
  print("Open the door")
else:
  print("Sorry, verification failed. Please try later.")

```
homework assignment
```py
#creating an automated curtain for window for specific time

timeForDowning=13
timeForUpraisal=18

if timeForDowning == timeForUpraisal:
  print("activate shade mode")
else:
  print("deactivate shade mode")
  
  
  # As discussed with Ben in class
  currenTime = 20
timeForDowning=13
timeForUpraisal=18

# if timeForDowning == timeForUpraisal:
#   print("activate shade mode")
# else:
#   print("deactivate shade mode")

# currenTime is greater or equal than timeForDowning and is less than timeForUpraisal -> put curtain 

# currenTime is greather or equal than timeForUpraisal remove curtains

# if currenTime >= timeForDowning and currenTime < timeForUpraisal:
#   print("First Condition")
#   print("activate shade mode")
# elif currenTime >= timeForUpraisal:
#   print("Second Condition")
#   print("deactivate shade mode")
# else:
#   print("Third Condition")
#   print("deactivate shade mode")


if currenTime >= timeForDowning and currenTime < timeForUpraisal:
  print("First Condition")
  print("activate shade mode")
else:
  print("Third Condition")
  print("deactivate shade mode")
  ```
