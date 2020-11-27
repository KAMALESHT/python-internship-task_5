# python-internship-task_5

1)Create a function getting two integer inputs from user. & print the following:

Addition of two numbers is +value
Subtraction of two numbers is +value
Division of two numbers is +value
Multiplication of two numbers is +value

Here the value represents math function associated

Solution:

def add(x,y):  

    sum=x+y

    return sum

def sub(x,y):

    sub=x-y
    
    return sub

def mul(x,y):

    mul=x*y

    return mul

def div(x,y):

    div=x/y

    return div

no_1=int(input("Enter the first no:"))

no_2=int(input("Enter the second no:"))

print("Addition of two no is:",add(no_1,no_2))

print("Subraction of two no is:",sub(no_1,no_2))

print("Multiplication of two no is:",mul(no_1,no_2))

print("Division of two no is:",div(no_1,no_2))


 2. Create a function covid( ) & it should accept patient name, and body temperature, by default the body temperature should be 98 

degree

solution:

def covid(patient_name,body_temperature=98):

    print("patient name:",patient_name)

    print("patient body temperature:",body_temperature)

covid("Kamalesh")
