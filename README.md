# Counter
print("Hello, World!")
print("Mayas Calculator!")
print("1 for Additon")
print("2 for Subtraction")
print("3 for Multiplication")
print("4 for Division")
operation = input()
if operation == "1":
  num1 = input("Enter First Number:")
  num2 = input("Enter Second Number:")
  print("The Sum Is: " + str(int(num1) + int(num2)))
elif operation == "2":
  num1 = input("Enter First Number:")
  num2 = input("Enter Second Number:")
  print("The Sum Is: " + str(int(num1) - int(num2)))
elif operation == "4":
  num1 = input("Enter First Number:")
  num2 = input("Enter Second Number:")
  print("The Sum Is: " + str(int(num1) / int(num2)))
