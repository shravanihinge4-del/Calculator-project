# Calculator-project
num1 = float(input("Enter first number: "))
num2 = float(input("Enter second number: "))

print("1. Addition")
print("2. Subtraction")
print("3. Multiplication")
print("4. Division")

choice = input("Enter your choice: ")

if choice == "1":
    result = num1 + num2
    print("Result =", result)

elif choice == "2":
    result = num1 - num2
    print("Result =", result)

elif choice == "3":
    result = num1 * num2
    print("Result =", result)

elif choice == "4":
    if num2 != 0:
        result = num1 / num2
        print("Result =", result)
    else:
        print("Cannot divide by zero.")

else:
    print("Invalid choice.")