# Python
Python Practice


STRINGS

Looping through a string using a for loop
**************
str="SREEKAR"

for x in str:
   print(x)
   
****************

String Length
***************

str="SREEKAR"
print(len(str))
**************


Containing in String or not
********************
str = "SREEKAR"
if "SREE" in str:
   print("It's there")
if "SREEH" not in str:
   print("it's not there")
*********************

Slicing
*******

str = "SREEKAR"
print(str[2])# output -> E
print(str[2:5])# output ->EEK
print(str[:5])# output -> SREEK
print(str[2:])# output -> EEKAR
print(str[-5:-2]) # output -> EEK
********************

Combining numbers and strings
****************
We will get error if we directly combine numbers and string
num = 23
str = "my age is " + num
print(str)

>using type casting
num = str(23)
str = "my age is " + num
print(str)

>using format
num = 23
str = "my age is {}"
print(txt.format(age))

quantity = 3
itemno = 567
price = 49.95
myorder = "I want {} pieces of item {} for {} dollars."
print(myorder.format(quantity, itemno, price))






