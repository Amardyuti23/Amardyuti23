- 👋 Hi, I’m @Amardyuti23
- 👀 I’m interested in developing software 
- 🌱 I’m currently learning Python
- 📫 How to reach me an email: amardyuti00@gmail.com

<!---
Amardyuti23/Amardyuti23 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->

a = int(input("enter first number: "))
b = int(input("enter second number: "))
add = a + b
sub = a - b
mul = a * b
div = a / b

print("1. add")
print("2. sub")
print("3. mul")
print("4. div")
choice = int(input("enter your choice: "))


if choice == 1:
    print("addition of two numbers is =", add)
elif choice == 2:
    print("subtraction of two numbers is =", sub)
elif choice == 3:
    print("multiplication of two numbers is =", mul)
elif choice == 4:
    print("division of two numbers is =", div)
else:
    print("enter correct choice")

