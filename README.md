# assignment-5Open In Colab
Write a python program to find a area of circle using math function
In [ ]:
import math
r=int(input("Enter the radius of the circle"))
a=math.pi*r*r
print("The area of the circle is", a)
Enter the radius of the circle3
The area of the circle is 28.274333882308138
write a python function to find the area of regular polygon using math function
In [ ]:
import math
n=int(input('enter the number of sides of a polygon'))
l=int(input('enter the length of the side of the polygon'))
a=(n*l**2)/(4*math.tan(math.pi/n))
print('The area of the polygon is', a)
enter the number of sides of a polygon6
enter the length of the side of the polygon78
The area of the polygon is 15806.695669873576
Write a program to find area of a segmentof a circle formula using math function
In [ ]:
import math
r=int(input('Enter the radius of Circle'))
a=int(input('Enter the angle of segment'))
if a>=360:
    print('Angle is not possible')
else:
  s=(math.pi*r**2)*(a/360)
  print('Area of segment is', s)
Enter the radius of Circle4
Enter the angle of segment45
Area of segment is 6.283185307179586
Write a python program to shuffle list[1={100,1,2,3,30,40,"Hai","Hello"}
In [ ]:
import random
a=[100,1,2,3,30,40,"Hai","Hello"]
random.shuffle(a)
print(a)
[100, 40, 'Hai', 1, 'Hello', 2, 30, 3]
Write a program to generate random numbers between 1,10000
In [61]:
import random
def Rand(start, end, n): 
    res=[]
    for j in range(n): 
        res.append(random.randint(start, end)) 
    return res 
n=10
start=1
end=10000
print(Rand(start, end, n))
[8017, 1787, 4939, 9032, 4770, 2045, 8970, 5452, 8853, 3330]
Write a python program by using math module to find
sin60
cos(pi)
tan90
angle of sin(0.8660254037844386)
5^8
Square root of 400
The value of 5^e
The value of Log(1024),base 2 9.The value of log(1024),base 10
The Floor and ceiling value of 23.56
In [75]:
import math 
a=math.pi/6 
print('The value of sine of 60 is', math.sin(a)) 
b=math.pi
print('The value of cos(pi) is', math.cos(b))
c=math.pi/4
print('The value of tan of 90 is', math.tan(c))
d=math.asin(0.8660254037844386)
print('The angle of sin(0.8660254037844386) is', math.degrees(d))
e=math.pow(5,8)
print('The value of 5^8 is', e)
f=math.sqrt(400)
print('The value of square root of 400 is', f)
g=math.pow(5,math.e)
print('The value of 5^e is', g)
h=math.log(1024,2)
print('The value of log(1024),base 2 is', h)
i=math.log(1024,10)
print('The value of log(1024),base 10 is', i)
j=math.ceil(23.56)
print('The Floor value of 23.56 is', j)
k=math.floor(23.56)
print('The Ceiling value of 23.56 is', k)
The value of sine of 60 is 0.49999999999999994
The value of cos(pi) is -1.0
The value of tan of 90 is 0.9999999999999999
The angle of sin(0.8660254037844386) is 59.99999999999999
The value of 5^8 is 390625.0
The value of square root of 400 is 20.0
The value of 5^e is 79.43235916621322
The value of log(1024),base 2 is 10.0
The value of log(1024),base 10 is 3.0102999566398116
The Floor value of 23.56 is 24
The Ceiling value of 23.56 is 23
