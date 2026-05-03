# Classes and Objects in Python: Calculate the Area of a Circle

## 🎯 Aim
To write a Python program that calculates the **area of a circle** based on the radius provided by the user. This program uses a class named `cse` and a method `mech` to perform the calculation.

## 🧠 Algorithm
1. **Get user input**: Take the radius of the circle as input from the user.
2. **Define the class**: Create a class named `cse`.
3. **Define the method**: Inside the class, define the method `mech` to calculate the area of the circle using the formula:  
   Area = pi *r^2 
4. **Execute the program**: Create an object of the class and call the method with the radius value.

## 🧾 Program
```
class cse:
    def mech(self,r):
        area = 3.14*r**2
        return area
r = int(input())
obj = cse()
res = obj.mech(r)
print("Area of circle",res)
```

## Output
<img width="247" height="107" alt="image" src="https://github.com/user-attachments/assets/425950f4-936a-45d0-879f-16edf077661b" />

## Result
Thus , a Python program that calculates the area of a circle based on the radius provided by the user. This program uses a class named cse and a method mech to perform the calculation is successfully completed.
