# Calculator
 #function add two number
def add(num1,num2):
    return num1 + num2

#function subtract two number
def sub(num1,num2):
    return num1 - num2

#function multiply two number
def multiply(num1,num2):
    return num1 * num2

#function divide two number
def divide(num1,num2):
    return num1 / num2

#function average two number
def avg(num1,num2):
    return (num1 + num2)/2

print("please select a opreaion:\n "\
      "1. addition\n" \
      "2. subtraction\n" \
      "3. multiplication\n" \
      "4. division\n" \
      "5. average\n")

Select = int(input("select a opreation from 1,2,3,4,5: "))

number1 = int(input("enter first number :"))
number2 = int(input("enter second number :"))  

if Select == 1:
   print(number1 , "+" , number2, "=" , \
           add(number1 ,number2))
   
elif Select == 2:
   print(number1 , "-" , number2, "=" , \
           sub(number1 ,number2))
   
elif Select == 3:
   print(number1 , "*" , number2, "=" , \
           multiply(number1 ,number2))
   
elif Select == 4:
   print(number1 , "/" , number2, "=" , \
           divide(number1 ,number2))   
   
elif Select == 5:
   print("(" , number1 , "+" , number2, ")" , "/" ,"2" ,  "=" , \
           avg(number1 ,number2)) 

   print("invali opreation! please select  again!") 
