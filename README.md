# Ineuron-Assignments
Q1)Why do we call Python as a general purpose and high-level programming language?

Ans: Python is a generat purpose language as it is used for building softwares in a wide variety of application domains.
     It is a high level language as it can be easily comprehended by humans.
     
Q2. Why is Python called a dynamically typed language?

Ans:Dynamic typing means that the type of the variable is determined only during runtime.Theres no need for initial declaration of data type.

Q3. List some pros and cons of Python programming language?

Ans:
Pros:-
Beginner-friendly	
Large Community	
Embeddable
Flexible and Extensible	
Extensive Libraries	
Highly Scalable	
Portable
IoT Opportunities

Cons:-
Security
Issues with design
Slower than compiled languages
High memory consumption 
Dynamically-typed language
Complex multithreading
Garbage collection leads to potential memory losses

Q4. In what all domains can we use Python?

Ans:-Python is used in the following domains:
Scientific Applications.
Business Applications.
Data Science
Artificial Intelligence.
Systems Programming.
Web Software.

Q5. What are variable and how can we declare them?

Ans:A variable in Python is a reserved memory location to store values. In other words, a variable in a python program gives data to the computer for processing. Declaring and re-declaring a variable in Python is as easy as writing names and assigning values to it.
There is no binding in Python to declare variables before we use it. We also need not explicitly declare variables with their data type. When we assign a value to Python variables, they are automatically declared.
We use the “=” operator for value assignment.
Eg:
If we want to declare a variable that should hold the marks we have, which is 10, we can do it in the following way –
marks=10

Q6. How can we take an input from the user in Python?

Ans:input() function is used to take user input. 
By default, it returns the user input in form of a string.
Eg:
name = input("Please Enter Your Name: ") 
age = input("Please Enter Your Age: ")
print("Name & Age: ", name, age )

Q7. What is the default datatype of the value that has been taken as an input using input() function?

Ans: string is the default datatype of input function which can be typecasted to any other type

Q8. What is type casting?

Ans:The conversion of one data type into the other data type is known as type casting.

Q9. Can we take more than one input from the user using single input() function? If yes, how? If no, why?

Ans:input() allows us to take only a single line string input which can be used to accept multiple values either space or comma separated and then can be separated using a split() function
input().split(separator)

Q10. What are keywords?

Ans:— Keywords in Python are reserved words that can not be used as a variable name, function name, or any other identifier.
Eg:Value Keywords: True, False, None.
Operator Keywords: and, or, not, in, is.
Control Flow Keywords: if, elif, else.
Iteration Keywords: for, while, break, continue, else.
Structure Keywords: def, class, with, as, pass, lambda.
Returning Keywords: return, yield.
Import Keywords: import, from, as.

Q11. Can we use keywords as a variable? Support your answer with reason.

Ans:  Keywords can't be used as a variable name as they are explicitly used for their predefined function.

Q12. What is indentation? What's the use of indentaion in Python?

Ans:Indentation is the leading whitespace (spaces or/and tabs) before any statement in Python. The reason why indentation is important in python is that the indentation serves another purpose other than code readability. Python treats the statements with the same indentation level (statements with an equal number of whitespaces before them) as a single code block.

Q13. How can we throw some output in Python?

Ans:Python provides the print() function to display output to the standard output devices. 
print(object(s), sep=separator, end=end, file=file, flush=flush)
Any and many number of objects which shall be converted to string before printing

Q14. What are operators in Python?

Ans:Operators are used to perform operations on variables and values.
Python divides the operators in the following groups:

Arithmetic operators(+,-,*,/)
Assignment operators(=)
Comparison operators(<,>,==)
Logical operators(&, Or)
Identity operators
Membership operators
Bitwise operators

Q15. What is difference between / and // operators?

Float Division("/"): Divides left hand operand by right hand operand.
5/2 = 2.5
Division works in Python the way it's mathematically defined.
x/y= float(x/y)

While,
Floor Division("//"): The division of operands where the result is the quotient in which the digits after the decimal point are removed. But if one of the operands is negative, the result is floored , i.e., rounded away from zero (towards negative infinity).
5//2=2
-11//3 = -4

Q16. Write a code that gives following as an output.

iNeuroniNeuroniNeuroniNeuron

Ans: print("iNeuron"*4)

Q17. Write a code to take a number as an input from the user and check if the number is odd or even.

Ans: 
num=int(input("Enter num:"))
if num%2==0:
  print("Number is even")
else:
  print("Number is odd")

Q18. What are boolean operator?

Ans:Boolean Operators are those that result in the Boolean values of True and False. 
These include and, or and not. While and & or require 2 operands, not is a unary operator. Boolean operators are most commonly used in arithmetic computations and logical comparisons.

Q19. What will the output of the following?

1 or 0

0 and 0

True and False and True

1 or 0 or 0

Ans:
1 or 0 = 1

0 and 0 = 0

True and False and True= False

1 or 0 or 0= 1

