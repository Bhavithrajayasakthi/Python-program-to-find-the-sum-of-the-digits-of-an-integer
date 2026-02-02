# Python-program-to-find-the-sum-of-the-digits-of-an-integer
def sum_of_digits(number):
    total = 0

    while number != 0:
        digit = number % 10
        total = total + digit
        number = number // 10

    print("Sum of digits is:", total)

num = int(input("Enter an integer: "))
sum_of_digits(num)
output:
Sum of digits is: 10
