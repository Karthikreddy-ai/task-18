def compare_numbers(a, b):
    if a > b:
        print(f"{a} is larger than {b}")
    elif a < b:
        print(f"{a} is smaller than {b}")
    else:
        print(f"{a} and {b} are equal")

compare_numbers(10, 20)
compare_numbers(15, 15)
num = int(input("Enter a number: "))
if num >= 10 and num <= 20:
    print("Number is within the range 10–20")
else:
    print("Number is outside the range")
text = input("Enter a string: ")
if text and len(text) > 5:
    print("Valid string with length greater than 5")
else:
    print("String is either empty or too short")
➕➖✖️➗ 3. Simple Calculator
def calculator(a, b, operation):
    if operation == "add":
        print("Result:", a + b)
    elif operation == "subtract":
        print("Result:", a - b)
    elif operation == "multiply":
        print("Result:", a * b)
    elif operation == "divide":
        if b != 0:
            print("Result:", a / b)
        else:
            print("Error: Division by zero")
    else:
        print("Invalid operati"}
calculator(10, 5, "add")
calculator(10, 0, "di")
age = int(input("Enter age: "))

if age < 13:
    print("Category: Child")
elif age >= 13 and age < 20:
    print("Category: Teenager")
elif age >= 20 and age < 60:
    print("Category: Adult")
else:
    print("Category: Senior")
username = "admin"
password = "12345"

user = input("Enter username: ")
pwd = input("Enter password: ")

if user == username and pwd == password:
    print("Login successful!")
else:
    print("Invalid credentials. Access denied.")
