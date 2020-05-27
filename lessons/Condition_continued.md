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
homework assignment
```py
guestName="Akshita"
guestRoomNo=502

# if guestName.title()== "Akshita" and guestRoomNo == 502:
#    print("allow access to guest")
# else:
#     print("no access allowed")
#     if guestName.title() > "akshita" and guestRoomNo > or < 502:
#       print("allow acess to guest")


salaryHigh=100000,90000,98000,87000,82000
salaryMedium=50000,67000,73000,54000,62000
salaryLow=20000,18000,32000,15000

salaryHighToTest=93000
if salaryHighToTest in salaryHigh
 print("someone has thatnamt of pay in salary high group")
 else:
   print("not a part of the high salary ")
   # guestName="Akshita"
# guestRoomNo=502

# if guestName.title()== "Akshita" and guestRoomNo == 502:
#    print("allow access to guest")
# else:
#     print("no access allowed")
#     if guestName.title() > "akshita" and guestRoomNo > or < 502:
#       print("allow acess to guest")


# 
# alaram clock

# presenTime=13
# timeForMorningAlarm=7
# timeForLunchBreakAlarm=13

# if timeForMorningAlarm == presenTime:
#    print("wake up,have a great day!")
# else:
#    if timeForLunchBreakAlarm == presenTime:
#      print("its lunch,take a break!")
else:
  print("keep on working")
# coffee machine

CurrenTime=7
TimeForCoffee=7
TimeForCoffeeIsReady=8
if TimeForCoffee == CurrenTime:
   print("start making coffee")
else:
   if TimeForCoffeeIsReady == CurrenTime:
     print("Your coffee is ready")
```
