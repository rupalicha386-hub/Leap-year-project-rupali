# Leap-year-project-rupaliwhile True:

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
            
