def add(number1, number2):
    return number1 + number2


def substract(number1, number2):
    return number1 - number2


def multiply(number1, number2):
    return number1 * number2


def divide(number1, number2):
    return number1 / number2


while True:
    try:
        first_number = int(input("Enter number"))
        second_number = int(input("Enter number"))
        operator = input("Select operation")
        break
    except ValueError:
        print("Invalid input")

if operator == "+":
    result = add(first_number, second_number)
    print(str(first_number) + "+" + str(second_number) + "=" + str(result))
elif operator == "-":
    result = substract(first_number, second_number)
    print(str(first_number) + "-" + str(second_number) + "=" + str(result))
elif operator == "*":
    result = multiply(first_number, second_number)
    print(str(first_number) + "*" + str(second_number) + "=" + str(result))
elif operator == "/":
    result = divide(first_number, second_number)
    print(str(first_number) + "/" + str(second_number) + "=" + str(result))
else:
    print("Invalid operator")
