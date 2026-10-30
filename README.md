# Python-practice-programs
Python practice programs
#python program to print hello world
print("Hello world")
#python program to print name
name="kirthika"
print(name)
#python program to print name,age,city
name="kirthika"
age="20"
city="thiruppathur"
print(name,age,city)
#python program to print the values separately
a=10
b=20
print(a,b,sep="-")
#python program to swap the values
a=10
b=20
a,b=b,a
print(a,b)
#python program to print int,float,string,boolean
a=10
b=12.3
c="kirthika"
d=a<b
print(a,b,c,d)
#python program to print datatype of input
age=20
print(type(age))
#python program to sum the input
a=10
b=20
print(a+b)
#python program to datype of input
a=input()
a=float(a)
print(type(a))
#python program to perform floor division and modulus
a=235
print(a%100)
print(a//100)
#python program to sum
a=25
last=a%10
first=a//10
print(first+last)
#python program to square the inputs
a=int(input())
print(a**2)
print(a**3)

#python program to calculate area and perimeter
length=int(input())
breadth=int(input())
print("area",length*breadth)
print("perimeter",2*(length+breadth))
#python program to check whether the inputs are equal
a=20
b=20
print(a==b)
#python program to compare inputs using comparision operator
a=int(input())
b=int(input())
print((a>b)*a+ (b>=a)*b)
#python program using comparision operator
a=25
b=20
c=10
print(a>b>c)
print(10==10.0)
print(10!=5)
print(7<3)
#python program to check greater
a=int(input())
print(a>10 and a<100)
#python program to print last number and check equal or not
a=int(input())
print(a%3==0 or a%5==0)
#python program to print output oppositely
a=int(input())
print(not(a==0))
#python program to find total,higher price,lower price
a=1000
b=2000
total=a+b
print("total:",total)
print("higher price:",max(a,b))
print("lower price:",min(a,b))
#python program to calculate area and perimeter and print output 2 decimal place
length=25.67
breadth=76.35
print("Area:",length*breadth)
print("perimeter:",2*(length+breadth))
print(f"{length*breadth:.2f}")
print(f"{2*(length+breadth):.2f}")
#python program to calculate total,average marks in two decimal places 
name="kirthika"
print("student name:",name)
tamil=90
english=88
maths=89
science=75
social=86
total=tamil+english+maths+science+social
print("total marks:",total)
average=total/5
print("average marks:",f"{average:.2f}")
#Write a python program that reads one value of each type from the user
a=int(input())
b=float(input())
c=str(input())
d=int(input())
e=float(input())
print(a)
print(b)
print(c)
print(d)
print(e)
