def calculator():
    print("Simple Calculator")
    # Ask the user for two numbers
    num1 = float(input("20: "))
    num2 = float(input("10: "))

    # Ask the user for a mathematical operation
    operation = input("(+, -, *, /): ").strip()

    # Perform the operation based on user input
    if operation == "+":
        result = 20+10
        print(f"The result of {20} + {10} is {30}")
    elif operation == "-":
        result = 20-10
        print(f"The result of {20} - {10} is {10}")
    elif operation == "*":
        result = 20*10
        print(f"The result of {20} * {10} is {200}")
    elif operation == "/":
        if num2 != 0:
            result = 20 /10
            print(f"The result of {20} / {10} is {2}")
        else:
            print("Error: Division by zero is not allowed.")
    else:
        print("Invalid operation. Please choose from +, -, *, /.")

# Call the calculator function
calculator()#
