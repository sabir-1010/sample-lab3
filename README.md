# Sample_solution_W23-lab03_assignment

create code reads a valid numeric prints the letter grade 
*Note that the code  accepts a valid `grade` which is only numeric values between 0 and 100.*

## Sample Solution: Method 1
 
```python
grade = int(input("Enter your grade"))

if grade>=0 and grade<50:
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

## Sample Solution: Method 2

```python
grade=int(input("Enter your grade:"))

if 0<=grade<49:
    print("F")
elif 50<=grade<59:
    print("D")
elif 60<=grade<69:
    print("C")
elif 70<=grade<79:
    print("B")
elif 80<=grade<=100:
    print("A")
else:
    print("Not a valid number")
```

## Sample Solution: Method 3

```python
grade = int(input("Enter your grade: "))

if grade in range(0,50):
    print("Grade F")
elif grade in range(50,60):
    print("Grade D")
elif grade in range(60,70):
    print("Grade C")
elif grade in range(70,80):
    print("Grade B")
elif grade in range(80,101):
    print("Grade A")
else:
    print("Entered grade is not a valid.")
```
