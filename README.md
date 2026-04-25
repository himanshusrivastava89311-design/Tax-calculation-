# Tax-calculation-
📌 Description
This is a simple Python program that calculates the tax percentage based on the user's salary input. It uses conditional statements (if-elif-else) to determine the correct tax slab.
⚙️ How It Works
The user enters their salary.
The program checks which salary range it falls into.
Based on the range, it prints the applicable tax percentage.
📊 Tax Slabs
Salary Range
Tax Rate
Less than 30,000
5%
30,000 – 70,000
15%
Above 70,000
25%
💻 Code
salary = int(input("enter the salary: "))

if salary < 30000:
    print("Tax 5%")
elif salary >= 30000 and salary <= 70000:
    print("Tax 15%")
else:   
    print("Tax 25%")
🚀 Features
Easy to understand
Uses basic Python concepts
Helpful for beginners learning conditions
