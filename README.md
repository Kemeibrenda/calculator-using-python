# calculator-using-python
print("select an operation to perfom:")
print("1_add")
print("2_subtract")
print("3_divide")
print("4_multiply") 
operation=input()


if (operation == "1"):
    num1=input("enter first number: ")
    num2=input("enter second number: ")
    print(float(num1) + float(num2))
elif (operation == "2"):
    num1=input("enter first number: ")
    num2=input("enter second number: ")
    
    print(float(num1) - float(num2))
elif (operation == "3"):
    num1=input("enter first number: ")
    num2=input("enter second number: ")
    print(float(num1) / float(num2))
elif (operation == "4"):
    num1=input("enter first number: ")
    num2=input("enter second number: ")
    print(float(num1) * float(num2))
else:
    print("invalid entry")
