# Calculator
Code for a basic calculator, usual operators

num1 = float(input("Enter first number: "))
op = input("Enter operator: ")
num2 = float(input("Enter second numer: " ))

# operators for the usual calculators below

if op == "+":
    print(num1 + num2)
elif op == "-":
    print(num1 - num2)
elif op == "/":
    print(num1 / num2)
elif op == "*":
    print(num1 * num2)
else:
    print("Invalid operator")
