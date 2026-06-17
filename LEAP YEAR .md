🎯 LEAP YEAR PROJECT REPORT
🏫 Project Title
🎓 Student Utility System
👩‍🎓 Student Information
👤 Name: Rupali Chauhan
🆔 GR Number: 13868 
🏫 College/institute Name: _rnw_
📚 Course: Python Programming
👨‍🏫 Faculty Name: @kumar
📅 Submission Date: 17 / 06 / 2026
📖 Project Objective

The objective of this project is to develop a simple menu-driven Python application that helps users perform basic utility tasks such as:

📅 Leap Year Checking
🔢 Multiplication Table Generation
⭐ Star Pattern Printing

This project demonstrates the use of Python programming concepts like loops, conditional statements, match-case, and user input handling.

🛠️ Tools & Technologies Used
🐍 Python 3
💻 VS Code / PyCharm / IDLE
🖥️ Windows Operating System
💻 Source Code
while True:

    print("\n🎯 STUDENT UTILITY SYSTEM")
    print("1️⃣ Leap Year Checker")
    print("2️⃣ Multiplication Table")
    print("3️⃣ Star Pattern")
    print("4️⃣ Exit")

    choice = int(input("👉 Enter Your Choice: "))

    match choice:

        case 1:
            year = int(input("📅 Enter Year: "))

            if (year % 4 == 0 and year % 100 != 0) or (year % 400 == 0):
                print("✅ Leap Year")
            else:
                print("❌ Not a Leap Year")

        case 2:
            num = int(input("🔢 Enter Number: "))

            print(f"\n📋 Table of {num}")
            for i in range(1, 11):
                print(num, "*", i, "=", num * i)

        case 3:
            rows = int(input("⭐ Enter Number of Rows: "))

            for i in range(1, rows + 1):
                for j in range(i):
                    print("*", end=" ")
                print()

        case 4:
            print("🙏 Thank You!")
            break

        case _:
            print("⚠️ Invalid Choice")
📚 Concepts Used

✅ Variables
✅ User Input
✅ If-Else Statements
✅ Match-Case
✅ While Loop
✅ For Loop
✅ Nested Loop
✅ Pattern Printing

🎯 Expected Output
🎯 STUDENT UTILITY SYSTEM

1️⃣ Leap Year Checker
2️⃣ Multiplication Table
3️⃣ Star Pattern
4️⃣ Exit

👉 Enter Your Choice:
✅ Conclusion

This project successfully demonstrates the implementation of basic Python programming concepts. It provides a simple and interactive menu-driven interface that allows users to perform different utility operations. The project helps improve logical thinking and programming skills.

🙏 Submitted By

👤 Name: Rupali Chauhan
🆔 GR Number: _13868_
📚 Subject: Python Programming
📅 Academic Year: 2026–27
