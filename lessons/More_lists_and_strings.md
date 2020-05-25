# Lesson May 23, 2020

Concepts

# - index in list, list sorting, list operations(add 2 lists, add to a list, remove from a list), square-root, String operations

Source: https://www.learnpython.org/en/String_Formatting, https://www.learnpython.org/en/Lists, https://www.learnpython.org/en/Basic_Operators


```py

list1 = [ 20, 34, 56, 7, 67, 83, 72]

list1.sort() # Devika will google how to sort in descending



list1.append(37)

print("This is the list before poping a member.")
print(list1)

print("I will pop a member from the list.")
print(list1.pop(0))

print("This is the list after poping is over.")
print(list1)


firstNumber = 4
powerNumber = 3

answerNumber = firstNumber ** powerNumber

print("The poer number result is : ")
print(answerNumber)


string1 = "Devika"

print(string1[2:6])

print("Hello, %s !" % string1)

print("Hello, %s! You are %d years old today." % (string1, 23))

print("The list of class score is is %s " % [21, 23, 25, 26])


```

# Homework assignment
```py
create1=[45,78,56,44,32,21,10,4,3]
create1.sort(reverse= True)
print("list in descending order")
print(create1)



print("list in ascending order")
create1.sort()
print(create1)
#sort list of strings

create2=["yellow","green","red","blue","pink","purple","lemon","magenta"]

create2.sort(reverse=True)
print(create2)

print("both the list after sorting in ascending order")
create3=create1 + create2

print(create3)
create2.sort()
print(create2)

create1.append(88)
print("adding a new number to the list")
print(create1)

create2.append("white")
print("adding new colour to the list")
print(create2)

print(create1.pop(4))
 print(create1)



print(" after poping index number-3")
print(create2.pop(3))
print("the new list")
print(create2)

firstNumber=32
powerNumber=2
squareRoot=firstNumber ** powerNumber
print("the square root of 32 is")
print(squareRoot)


print("string operations")

follow1="London"

print(follow1[1:3])

print("welcome to,%s " % follow1)
print("welcome to,%s devika in %d." %(follow1,2020))
```









