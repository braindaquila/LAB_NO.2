# LAB_NO.2
# Task: Create a calculator program using input function
num1 = int(input("Enter first number: "))
num2 = int(input("Enter second number: "))

sum_result = num1 + num2
diff_result = num1 - num2
prod_result = num1 * num2

print(f"Sum: {sum_result}")
print(f"Difference: {diff_result}")
print(f"Product: {prod_result}")

# Task: Compute average using 2 user input values
val1 = float(input("Enter first value: "))
val2 = float(input("Enter second value: "))

average = (val1 + val2) / 2

print(f"The average is: {average}")

# Task: Pass or Fail System
grade = float(input("Enter your grade: "))

if grade >= 75:
    print("Status: Passed")
else:
    print("Status: Failed")
