#Assignment I
#(Python)
#Name: Yuvraj Sharma 
#E-mail: yuvrajs961@gmail.com
#Phone no. 7006419883

#Question 1: Explain the key features of Python that make it a popular choice for programming.
#Answer 1: We have many features of Python because of which it is a popular choice for programming among developers, but below are the key features:
#•	Easy To Understand:
#Python as a language is easy to understand comparatively to other Languages. As for beginners are considered if they are not familiar with any other language like C, C++ or other’s they can start with python.
#•	Easy To Write:
#Python syntax and interface are much easier for a beginner for his developer journey. As the coding doesn’t include much complex methods or syntax.
#•	Compatibility:
#If you start working with python and understand all the basics you will understand that python is much highly compatible with various programming paradigms which include Object Oriented Programming (OOP), scripting, functional programming and more. This allows developers to choose their specific paradigm through which they want to approach a specific problem and come up with a solution. 
#•	Extensive Library, Third Party Packages and Community of Developers:
#Due to extensive libraries, large and active community of developers and third-party packages for various domains python is considered important among developers.
#These are some of the key features of Python that make it a popular choice for programming among developers.





#Question 2: Describe the role of predefined keywords in Python and provide examples of how they are used in a program.
#Answer 2: Keywords are the reserved words that holds the predefined meanings in python. They have special meanings and cannot be used as identifiers for e.g. variable names, function names etc. Along with that they are also case sensitive and cannot be redefined or overridden within a Python Program. 
#Some common examples of Predefined Keywords are:
#•	While (Loops): When we use a keyword from which a loop is created that runs as long as a condition is true that loop is known as while loop.

#Syntax:
row = 1
while row <=4:
  col = 1
  while col<= row:
    print("*", end ="")
    col = col +1
  print()
  row = row +1

#•	if, elif, else (Conditional Statements): When we use a keyword to create decision-making conditions in a program. For e.g.:

#Syntax:
l=[1,2,3,4,5]
for i in l:
  if i==1:
    print("*")
  elif i==2:
    print("**")
  elif i==3:
    print("***")
  elif i==4:
    print ("****")
else:
  print ("*****")

#While there are many examples of predefined keywords in python the above two are some good examples. Also, we have for, def, class, import, try, except, return, True, False, None, etc. keywords too.




#Question 3:  Compare and contrast mutable and immutable objects in Python with examples.
#Answer 3:  Generally, in python objects can be used as change able which means Modifiable or unchangeable which means Un-changeable. 
#The Contrast which we find in Mutable and Immutable objects in Python with examples are as follows:
#The example of mutable objects: Lists and Dictionaries. Mutable objects which are created can be altered after the creation. 
#Meanwhile, the example of Immutable Objects: Tuples and Strings in contrast which are immutable objects, once they are created cannot be modified and for any change you want in the objects you have to create a new object.
#With this distinction in mutability Python manages memory and object references which can affect performance, memory efficiency and behavior in concurrent programming.
#Mutable objects can also lead to unintended side effects when passed between functions, while Immutable objects offer more predictability and thread safety. 





#Question 4:  Discuss the different types of operators in Python and provide examples of how they are used.
#Answer 4: Python as a language uses Operators which are special symbols or keywords used to perform specific operations on values, variables or expressions. 
#Enabling the calculations, comparisons, logical evaluations and data manipulation within python programs. 
#There are different categories of operator such as:
#1.	Arithmetic Operators: It includes all the mathematical operations such as Addition (+), Subtraction (-), Multiplication (*), Division (/) and many other. 
#2.	Logical operators: Operators used for combining or negating conditions such as and, or, not. 
#3.	Comparison Operators: These operators are used to compare the values between 2 variables such as Equal to (==) checks whether the two values are equal or not, not equal to (! =) checks whether the two values are not equal, Lesser Than (<) checks if the left value is smaller than the right, Greater Than (>) checks if the left value is larger than the right.
#4.	Assignment operators: These are used for assigning and updating variable values such as (=, +=, -=, *=, /=)
#The main roles of these operators are to follow precedence and associativity rules which determines the sequence in which expressions are evaluated which ensures that more complex operations are executed correctly.




#Question 5: Explain the concept of type casting in Python with examples.
#Answer 5: 	Type Casting: It is also known as the process of transforming a value from one data type to another in Python. This is achievable through Python’s built-in functions like int (), float (), str (), dict (), tuple (), list ().  It allows the developer to explicitly change the data type of variables as needed for different tasks within a program.
#It is really important when performing some operations that require specific data types. For e.g. when a developer wants to convert a string input into an integer or converting a floating-point number to an integer to be used when whole numbers are needed which enables mathematical operations. In the same way we if a developer wants to convert a data into different structures like changing a list to a tuple for immutability or a string to a list for easier manipulation.
#It is crucial in ensuring that data types are compatible during operations in help to prevent errors and streamline data handling. Tasks which involve user input, arithmetic calculations or when passing data between functions type casting helps to ensure that python programs can handle a wide variety of data in a flexible and efficient manner.






#Question 6: How does conditional statements work in Python? Illustrate with examples.
A#nswer 6:  Conditional Statements in Python allows one or more conditions to get evaluated during the execution of specific blocks of code. When these conditions are typically expressed the developer gets the result in True or False by using comparison or logical expressions.
#Conditional Statements like if, “elif” which is a short form of “else if” are provided by Python and also to manage the flow of the program.  If statement checks the initial condition and elif allows additional conditions to be tested if the previous ones are false. If none of the conditions are met then only the else block will run.
#Also, conditional statements can be nested to handle more complex scenarios which enable the program to make multiple decisions within the same block of code which allows fine control over the execution flow based on the results of various conditions.



#Question 7: Describe the different types of loops in Python and their use cases with examples.
#Answer 7: Loops are used repeatedly to execute a block of code until a certain condition is met or a sequence is fully processed in Python which allows for automation and iteration also which makes a code more efficient when performing repetitive tasks.
#There are 2 types of loops which is provided by Python:
•#	For Loop: A for loop is used to iterate over a sequence (like a list, tuple or string) and execute code for each item in that sequence. When the number of iterations is known or when you need to process items in a collection. For e.g.
#Syntax
for i in range (4):
  for j in range (i+1):
    print ("*", end = "")
  print ()
•#	While Loop: This loop continues to execute as long as a specific condition remains true. This loop is used when the number of iterations is not predetermined and the loop relies on the evaluation of a condition that changes during the loop’s execution.
#Syntax
a = 1
while a <=4:
  i = 1
  while i<= a:
    print ("*", end ="")
    i = i +1
  print ()
  a = a +1

