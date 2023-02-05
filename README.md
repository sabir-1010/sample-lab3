# Sample_solution_W23-lab03_assignment

create code reads a valid numeric prints the letter grade 
*Note that the code  accepts a valid `grade` which is only numeric values between 0 and 100.*

## Sample Solution: Method1
 
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
