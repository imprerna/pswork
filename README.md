# pswork
 ## TASK 1: 
 ##Install Jupyter notebook and run the first program and share the screenshot of the output
 ## Write a program which will find all such numbers which are divisible by 7 but are not a multiple
of 5, between 2000 and 3200 (both included). The numbers obtained should be printed in a
comma-separated sequence on a single line.
Source code:
list=[ x for x in range(2000,3201) if x % 7 == 0 and x % 5 != 0]
print(list)

TASK 1:
##Question 3: Write a Python program to accept the user's first and last name and then getting them printed in
the the reverse order with a space between first name and last name.
##Source Code:
Firstname=input()
Surname=input()
print(Firstname+"  " +Surname)
print(Firstname[::-1]+" " +Surname[::-1])

##Question 4:Write a Python program to find the volume of a sphere with diameter 12 cm
##Source Code:
import math
d=12
r=d*2
v=(4/3)*math.pi*pow(r,3)
print(v)

##TASK 2:
##Question 1:Write a program which accepts a sequence of comma-separated numbers from console and
generate a list.
##Source Code:
values = input("Input some comma seprated numbers : ")
list = values.split(",")
print('List : ',list)

##Question 2: Create the below pattern using nested for loop in Python.
*
* *
* * *
* * * *
* * * * *
* * * *
* * *
* *
*
##Source Code:
n=5;
for i in range(n):
    for j in range(i):
        print ('* ', end="")
    print('')
for i in range(n,0,-1):
    for j in range(i):
        print('* ', end="")
    print('')

##Question 3:Write a Python program to reverse a word after accepting the input from the user.
##Sample Output:
Input word: AcadGild
Output: dilGdacA
###
Source Code:
WORD=input()
print(WORD[::-1])

##Question 4:Write a Python Program to print the given string in the format specified in the sample output.
WE, THE PEOPLE OF INDIA, having solemnly resolved to constitute India into a
SOVEREIGN, SOCIALIST, SECULAR, DEMOCRATIC REPUBLIC and to secure to all
its citizens
### Sample Output:
WE, THE PEOPLE OF INDIA,
having solemnly resolved to constitute India into a SOVEREIGN, !
SOCIALIST, SECULAR, DEMOCRATIC REPUBLIC
and to secure to all its citizens
###
Source Code:
print("WE, THE PEOPLE OF INDIA,\n\thaving solemnly resolved to constitute India into a SOVEREIGN,
! \n\t\tSOCIALIST, SECULAR, DEMOCRATIC REPUBLIC \n\t\t and to secure to all its citizens")

	




