"# Define a function to perform the calculator operations
def calculator(x, y, operation):
  if operation == '+':
    return x + y
  elif operation == '-':
    return x - y
  elif operation == '*':
    return x * y
  elif operation == '/':
    return x / y
  else:
    return 'Invalid operator'

# Get input from the user
x = float(input('Enter the first number: '))
y = float(input('Enter the second number: '))
operation = input('Enter the operation (+, -, *, /): ')

# Print the result of the calculator function
print(calculator(x, y, operation))
"
![image](https://user-images.githubusercontent.com/120616574/208027343-cb059300-cbac-4f7d-ae8d-593a31bb6f4e.png)
