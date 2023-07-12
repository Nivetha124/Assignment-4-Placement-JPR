# Assignment-4-Placement-JPR

# 1)Write a program to display name of day on the basis of entered number for example, 2 for Monday

x=int(input("enter the number"))
if x==1:
    print("sunday")
elif x==2:
    print("monday")
elif x==3:
    print("tuesday")
elif x==4:
    print("wednesday")
elif x==5:
    print("thursday")
elif x==6:
    print("friday")
elif x==7:
    print("saturday")
else:
    print("please enter x is between 0-7")

# 2)Input: Enter Cost Price of the Product:45 Enter Selling Price of the Product:58 Output: The Product sold by the Profit of Rs.13.

costprice=int(input("enter cost price of the product"))
sellingprice=int(input("enter selling price of te product"))
productsold=sellingprice-costprice
if productsold>0:
    print("the product sold by the profit of", productsold)
elif productsold==0:
    print("the product sold by no profit and no loss of", productsold)
else:
    print("the product sold by the loss of", productsold)
    
# 3)Input: Enter time in hours:15 Output: Good evening

Time=int(input("enter the time in hours"))
if (Time>=0 and Time<=12):
    print("Good morning")
elif (Time>12 and Time<=18):
    print("Good evening")
elif (Time>18 and Time<=24):
    print("Good night")
else:
    print("hours should be 24hours only")

    
# 5) Input: Enter the number: 4 Output: Four
n=int(input("enter the number"))
if n==1:
    print("one")
elif n==2:
    print("two")
elif n==3:
    print("three")
elif n==4:
    print("four")
elif n==5:
    print("five")
elif n==6:
    print("six")
elif n==7:
    print("seven")
elif n==8:
    print("eight")
elif n==9:
    print("nine")
else:
    print("none")
    
# 7)Calculate X power of Y without use of inbuilt math function. Ex, Input: X=2 Y=3 Output:8
base=int(input("enter the base value"))
exponent=int(input("enter the exponent value"))
result=1
while (exponent!=0):
    result*=base
    exponent-=1
print("answer = ", result)
                                                                             (OR)
base=int(input("enter the base value"))
exponent=int(input("enter the exponent value"))
result=1
for i in range(exponent, 0, -1):
    result*=base
print("answer = ", result)

