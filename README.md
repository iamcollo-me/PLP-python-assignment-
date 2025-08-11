def calculator():
    print("Simple Calculator")
    # Ask the user for two numbers
    num1 = float(input("Enter the first number: "))
    num2 = float(input("Enter the second number: "))

    # Ask the user for a mathematical operation
    operation = input("Enter the operation (+, -, *, /): ").strip()

    # Perform the operation based on user input
    if operation == "+":
        result = num1 + num2
        print(f"The result of {num1} + {num2} is {result}")
    elif operation == "-":
        result = num1 - num2
        print(f"The result of {num1} - {num2} is {result}")
    elif operation == "*":
        result = num1 * num2
        print(f"The result of {num1} * {num2} is {result}")
    elif operation == "/":
        if num2 != 0:
            result = num1 / num2
            print(f"The result of {num1} / {num2} is {result}")
        else:
            print("Error: Division by zero is not allowed.")
    else:
        print("Invalid operation. Please choose from +, -, *, /.")

# Call the calculator function
calculator()#
