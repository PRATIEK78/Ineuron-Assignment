# Ineuron-Assignment
1. Write a program which will find all such numbers which are divisible by 7 but are not a multiple of 5, between 2000 and 3200 (both included). The numbers obtained should be printed in a comma-separated sequence on a single line.
Soln: for i in range (2000,3201):
    if (i%7==0 and i%5!= 0):
        print (i,end= ',')
        
2. Write a Python program to accept the user's first and last name and then getting them printed in the the reverse order with a space     between first name and last name.
soln: First_Name= input()
Last_Name = input()
print(Last_Name + ' ' + First_Name)

3. Write a Python program to find the volume of a sphere with diameter 12 cm. Formula: V=4/3 * π * r**3

soln: r = float(input())
pi= 3.14
V = 4.0/3.0 * pi * r**3
print('The Volume of the Sphere is', V)

4. Write a program which accepts a sequence of comma-separated numbers from console and generate a list.

soln: x= str(input())

list = x.split(",")

list
       
l=[]

for i in list:
    j=int(i)
    l.append(j)
    if (len(l))==len(list):
         print(l)
 
 5. Create the below pattern using nested for loop in Python.

#*

#* *

#* * *

#* * * *

#* * * * *

#* * * *

#* * *

#* *

#*

soln: x = "*"
n=input()
n = int(n)
for i in range (0, n):
    for j in range(0, i + 1):
        print("*", end=' ')
    print("\r")
    

for i in range (n,0,-1):
    for j in range(0,i-1):
        print("*",end = ' ')
    print("\r")
 
 6. Write a Python program to reverse a word after accepting the input from the user. Sample Output: Input word: AcadGild Output: dilGdacA
 
 soln: a= "AcadGild"

for i in range(len(a)-1,0,-1):    
    print(a[i],end =' ')
    
 7. Write a Python Program to print the given string in the format specified in the sample output.
WE, THE PEOPLE OF INDIA, having solemnly resolved to constitute India into a
SOVEREIGN, SOCIALIST, SECULAR, DEMOCRATIC REPUBLIC and to secure to all
its citizens
Sample Output:
WE, THE PEOPLE OF INDIA,
  having solemnly resolved to constitute India into a SOVEREIGN, !
     SOCIALIST, SECULAR, DEMOCRATIC REPUBLIC
        and to secure to all its citizens
        
  soln: print("WE, THE PEOPLE OF INDIA,{} having solemnly resolved to constitute India into a SOVEREIGN,{}    SOCIALIST, SECULAR, DEMOCRATIC REPUBLIC{}       and to secure to all its citizens"
       .format("\n","\n","\n","\n"))
