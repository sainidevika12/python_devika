# Lesson May 27, 2020


```py

guestName="ben"
guestRoomNo=500

if guestName.title() == "Akshita" and guestRoomNo == 502:
   print("1")
   print("allow access to guest")
elif guestName.lower() > "akshita" and (guestRoomNo > 502 or guestRoomNo < 502):
  print("3")
  print("allow acess to guest")
else:
  print("2")
  print("no access allowed")


# if "A" > "a":
#   print("True")
# else:
#   print("False")

#####

import datetime
# alaram clock

# presenTime=7
# timeForMorningAlarm=7
# timeForLunchBreakAlarm=13

# if timeForMorningAlarm == presenTime:
#   print("wake up,have a great day!")
# elif timeForLunchBreakAlarm == presenTime:
#   print("its lunch,take a break!")
# else:
#   print("keep on working")

# coffee machine

# CurrenTime=7
# TimeForCoffee=7
# TimeForCoffeeIsReady=8

# if TimeForCoffee == CurrenTime:
#   print("start making coffee")
# elif TimeForCoffeeIsReady == CurrenTime:
#   print("Your coffee is ready")



currentTime = datetime.datetime.now().replace(hour=6, minute=30, second=00, microsecond=00)

#time for coffee is 7AM
timeForCoffee = datetime.datetime.now().replace(hour=7, minute=00, second=00, microsecond=00)
timeForCoffeeIsReady = datetime.datetime.now().replace(hour=7, minute=30, second=00, microsecond=00)

if currentTime == timeForCoffee:
  print("Current time is : {}".format(currentTime))
  print("start making coffee")
elif currentTime == timeForCoffeeIsReady:
  print("Current time is : {}".format(currentTime))
  print("Your coffee is ready")
else:
  print("Current time is : {}".format(currentTime))







salaryHigh=[100000,90000,98000,87000,82000]
salaryMedium=[50000,67000,73000,54000,62000]
salaryLow=[20000,18000,32000,15000]

salaryHighToTest=83000

# if salaryHighToTest in salaryHigh:
#  print("someone has their pay in high salary group")
# else:
#    print("not a part of the high salary ")


# 80000                <= 100000
# salaryHighToTest is <= maximum in salaryHigh list 

# and

# 80000                >= 82000
# salaryHighToTest is >= minimum in salaryHigh list 


if salaryHighToTest <= max(salaryHigh) and salaryHighToTest >= min(salaryHigh):
  print("{} is a part of high salary group!".format(salaryHighToTest))



```
