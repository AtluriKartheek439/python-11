# python-11
# nested if for checking the num is the both pos and even..
num=int(input("Enter the number"))
if num>0:
    print("Positive number")
    if num%2==0:
        print("Even")
    else:
        print("Odd")
else:
    print("Number is Non-Positive")
