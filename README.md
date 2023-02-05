# sample-lab3

**create code that** 
1. reads a valid numeric grade in a variable called `grade` from the user and 
2. a conditional that prints the letter grade based on the inputted value of `grade` according to the following table:

| From | To (but not including) | Letter Grade |
| ---- | ---- | ---- |
|  0   |  50  |   F  |
|  50  |  60  |   D  |
|  60  |  70  |   C  |
|  70  |  80  |   B  |
|  80  |  100 |   A  |

*Note that our code accepts a valid `grade` which is only numeric values between 0 and 100.*

```python
grade = int(input("Enter your grade"))
if grade<50 and grade>0:
  print("F")
elif grade>=50 and grade<60:
  print("D")
elif grade>=60 and grade<70:
  print("C")
elif grade>=70 and grade<80:
  print("B")
elif grade>=80 and grade<=100:
  print("A")
else:
  print("Invalid Input")
```
