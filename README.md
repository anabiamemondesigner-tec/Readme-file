Chapter 1
1. First we install python in our software.
2. Then we download visual studio code.
3. Then we open visual studio code and open python extension.
4. Then we open settings and tick the mouse wheel setting.
5. Then we create a file Name: first.py.
6. Then we code something we code print("Hello World") .
7. If we need to run this code we need to open terminal and write python first.py then press enter it give us answer which is Hello World.
8. Then we make another file which name is module.py.
9. Then we install flask and pyjokes like this first we open terminal write pip install flask flask install successfully.
10. Then we write pip install pyjokes and write import pyjokes

Chapter 2

                                                      Variables and Data Types




1. If I write a = 1 and b = 2  then I write print (a + b) a  has 1 b has 2 if we add 2 + 1 = 3 it gives output which is 3.

2. If you think what is a variable? in your kitchen you have a container in which you add rice flour etc.

3. Your container in which things is store is a variable for example a is your container which we called in python language variable.

4. For example you have a red box and a blue box in red box you have sugar and in blue box you have flour if you need red box in this  box you have sugar is store we say it red box or sugar box like this a = 1 it's means if we call a in this in a 1 is stored in the RAM Random Access Memory.

5. If I write a = 30 b = " Anabia " any time I write any name I need to write this name in double or single coats if we don't add double or single coats it give us an error because in python we write any person name we need to right in double or single coats we call it a string data type ok.

6. Now we talk about data types:
1. String.
2. Floating point numbers.
3. Integers.
4. Booleans.
5. None.

7. a = 1 # a is an integer number integer means a number not a string or floating point number.

8. b = 5.22 # b is a floating point number floating point number means numbers in decimal form.

9. c = "Anabia"  # c is a string data type string data type means any name is in double or single coats if any name in python language without single or double coats python gives error we also write number in double or single coats but for number if we don't write number in double or single coats it don't gives us error because number is also called integer.

10. d = False # d is a Booleans variable Booleans variable means if in the word Jupiter alphabet is greater then 5 it's True and less then five it's  False in python we write True or False first letter capital.

11. e = None # e is a none type variable none type variable means nothing else why we don't use True or False because True means yes False means no if I need to a specific variable has nothing so then I use none variable. 

12. **Rules for Defining a Variable Name (Also Applies to Other Identifiers)**

1. A variable name can contain alphabets, digits, and underscores.
2. A variable name can only start with an alphabet or an underscore.
3.A variable name cannot start with a digit.
3. No white space is allowed inside a variable name.

5.Examples of valid variable names:**

`harry`
`one8`
`seven`
`__seven`

13.**OPERATORS IN PYTHON**

Following are some common operators in Python:

1. Arithmetic Operators:** `+`, `-`, `*`, `/`, etc.
2. Assignment Operators:** `=`, `+=`, `-=`, etc.
3. Comparison Operators:** `==`, `>`, `>=`, `<`, `!=`, etc.
4. Logical Operators:** `and`, `or`, `not`.

Examples:

* Arithmetic: `5 + 3`
* Assignment: `x = 10`
* Comparison: `5 > 3`
* Logical: `True and False`




11.Then we write this code.

first.py
print("Hello World")



12. If we need to run this file we need to open terminal then write python first.py



module.py
import pyjokes
# print("Printing Jokes ...")
joke = pyjokes.get_joke()
print(joke)


import pyttsx3

# Initialize the engine
engine = pyttsx3.init()

# Convert text to speech
engine.say("Hello I'm Anabia Memon")
engine.runAndWait()



import os

# 1. Path ko '.' kar diya taaki ye isi folder ko check kare
directory_path = '.'

# 2. 'conttents' ki spelling theek karke 'contents' kar di
contents = os.listdir(directory_path)

print(contents)



13. If we need to run this file we need to open terminal then write python module.py.
14. Then we install flask and pyjokes and pyttsx3 like this first we open terminal write pip install flask flask install successfully.
15. Then we write pip install pyjokes.

Chapter 2












1. if we need to calculate we need to do this but it doesn't calculate it just give us exact numbers.


a = input("Enter first number:")
b = input("Enter second number:")
print ("The average of two numbers is:" , (a+b))


2. if we need to calculate we need to do this but it doesn't calculate it just give us exact numbers we need to do this .

a = int(input("Enter first number:"))
b = int(input("Enter second number:"))
print ("The average of two numbers is:" , (a+b))



