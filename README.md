# Calculator.py


#def main():
#   x = int(input("What's x? "))
#    print("x sqaured is", square(x))
    
    
#def square(n):
#    return pow(n, 2)

#main()


#List of actions
print("Hello! I am a calcutor. What kind of problem can I help you solve? ")
print("1: Add")
print("2: Substract")
print("3: Multiply")
print("4: Divide")

#Ask user what them need to do

a = int(input("What kind of problem do you need to solve? Please enter 1-4. "))

# If the user wants to add two numbers
if a == 1 :
    x = int(input("What is your first number? "))
    y = int(input("What is your second number? "))
    print(x + y)

# If the user wants to subtract two numbers
elif a == 2 :
    x = int(input("What is your first number? "))
    y = int(input("What is your second number? "))
    print(x - y)


# If the user wants you mutiply two numbers
elif a == 3 :
    x = int(input("What is your first number? "))
    y = int(input("What is your second number? "))
    print(x * y)

# If the user wants to divide two numbers
elif a == 4 :
    x = int(input("What is your first number? "))
    y = int(input("What is your second number? "))
    print(x / y)

else:
    print("Not a option. Please choose from 1, 2, 3 or 4. ")
