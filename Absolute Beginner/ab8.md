### Problem no.8

You are provided with the radius of a circle "A". Find the length of its circumference.

***Note:** In case the output is coming in decimal, roundoff to 2nd decimal place. In case the input is a negative number, print "Error".*

**Input Description:**
The Radius of a circle is provided as the input of the program.

**Output Description:**
Calculate and print the Circumference of the circle corresponding to the input radius up to two decimal places.

**Sample Input :**
```
2
```

**Sample Output :**
```
12.57
```

**Code :**
```python
a=float(input())
if(a<0):
  print("Error")
else:
  print(round((2*(22/7)*a),2))
```
