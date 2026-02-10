name = input("Enter Student Name: ")
roll = input("Enter Roll Number: ")
course = input("Enter Course Name: ")
print("\nEnter marks out of 100:\n")
s1 = int(input("Subject 1: "))
s2 = int(input("Subject 2: "))
total = s1 + s2
percentage = total / 2
if percentage >= 90:
 grade = "A+"
elif percentage >= 80:
 grade = "A"
elif percentage >= 70:
 grade = "B+"
elif percentage >= 60:
 grade = "B"
elif percentage >= 50:
 grade = "C"
else:
 grade = "Fail"
print("\n============== STUDENT MARKSHEET ==============")
print("Name :", name)
print("Roll Number :", roll)
print("Course :", course)
print("-----------------------------------------------")
print("Subject 1 :", s1)
print("Subject 2 :", s2)
print("-----------------------------------------------")
print("Total Marks :", total)
print("Percentage :", percentage, "%")
print("Grade :", grade)
print("===============================================")

output
Enter Student Name: hari
Enter Roll Number: 34
Enter Course Name: cs

Enter marks out of 100:

Subject 1: 80
Subject 2: 88

============== STUDENT MARKSHEET ==============
Name : hari
Roll Number : 34
Course : cs
-----------------------------------------------
Subject 1 : 80
Subject 2 : 88
-----------------------------------------------
Total Marks : 168
Percentage : 84.0 %
Grade : A
===============================================


