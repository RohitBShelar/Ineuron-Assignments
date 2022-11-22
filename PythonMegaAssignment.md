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

Q20. What are conditional statements in Python?

Ans: Conditional statements in python helps evalute particular conditions and then transfer the control to the following lines. 

Q21. What is use of 'if', 'elif' and 'else' keywords?

Ans:if…elif…else are conditional statements that provide you with the decision making that is required when you want to execute code based on a particular  condition.

Q22. Write a code to take the age of person as an input and if age >= 18 display "I can vote". If age is < 18 display "I can't vote".

Ans:
age=int(input("Enter age:"))
if age>=18:
  print("I can vote")
else:
  print("I cant vote")

Q23. Write a code that displays the sum of all the even numbers from the given list.

numbers = [12, 75, 150, 180, 145, 525, 50]

Ans:
numbers = [12, 75, 150, 180, 145, 525, 50]
sum=0
for number in numbers:
     if number%2==0:
          sum=sum+number
print("Sum of even numbers:",sum)   

Q24. Write a code to take 3 numbers as an input from the user and display the greatest no as output.

Ans:
num_list=list(map(int,input("Enter three nos separated by space:").split()))
max=num_list[0]
for i in num_list:
  if int(i)>max:
    max=int(i)

print("Greatest number is :", max)

Q25. Write a program to display only those numbers from a list that satisfy the following conditions

The number must be divisible by five

If the number is greater than 150, then skip it and move to the next number

If the number is greater than 500, then stop the loop

numbers = [12, 75, 150, 180, 145, 525, 50]

Ans: 

for num in numbers:
  if num%5==0:
    if num > 150:
      continue
      if num>500:
        break
    else:
      print(num)
      
 output:
 75
150
145
50

Q26. What is a string? How can we declare string in Python?

Ans: string is data type in python that can consist of alh

Q27. How can we access the string using its index?

Ans:
We can access the characters in a string by referring to its index number inside square brackets [] .
Eg 
s="rohit"
print(s[3])

output: i


Q28. Write a code to get the desired output of the following

string = "Big Data iNeuron"
desired_output = "iNeuron"

Ans:
string = "Big Data iNeuron"
string_list=string.split()
print(string_list[2])

Q29. Write a code to get the desired output of the following

string = "Big Data iNeuron"
desired_output = "norueNi"

Ans:
string = "Big Data iNeuron"
string_list=string.split()
print(string_list[2][-1::-1])

Q30. Resverse the string given in the above question.

Ans:
string = "Big Data iNeuron"
print(string[-1::-1])

Q31. How can you delete entire string at once?

Ans:
name="rohit shelar"
del name

Q32. What is escape sequence?

Ans:
An escape sequence is a sequence of characters that, when used inside a character or string, does not represent itself but is converted into another character or series of characters that may be difficult or impossible to express directly, like newline (\n), tab (\t), and so on.
In the escape sequence, a character is preceded by a backslash (\\) followed by the character you want to represent for the new line. We have something like this \\\n.
This character serves as an escape sequence initiator, and every character (one or more) following it is considered an escape sequence.

Q33. How can you print the below string?

'iNeuron's Big Data Course'

Ans: print("iNeuron's Big Data Course")

or 

print("iNeuron\'s Big Data Course")

Q34. What is a list in Python?

Q35. How can you create a list in Python?

Q36. How can we access the elements in a list?

Q37. Write a code to access the word "iNeuron" from the given list.

lst = [1,2,3,"Hi",[45,54, "iNeuron"], "Big Data"]
Q38. Take a list as an input from the user and find the length of the list.

Q39. Add the word "Big" in the 3rd index of the given list.

lst = ["Welcome", "to", "Data", "course"]
Q40. What is a tuple? How is it different from list?

Q41. How can you create a tuple in Python?

Q42. Create a tuple and try to add your name in the tuple. Are you able to do it? Support your answer with reason.

Q43. Can two tuple be appended. If yes, write a code for it. If not, why?

Q44. Take a tuple as an input and print the count of elements in it.

Q45. What are sets in Python?

Q46. How can you create a set?

Q47. Create a set and add "iNeuron" in your set.

Q48. Try to add multiple values using add() function.

Q49. How is update() different from add()?

Q50. What is clear() in sets?

Q51. What is frozen set?

Ans:
The frozenset() function returns an immutable frozenset object initialized with elements from the given iterable.
Frozen set is just an immutable version of a Python set object. While elements of a set can be modified at any time, elements of the frozen set remain the same after creation.
Due to this, frozen sets can be used as keys in Dictionary or as elements of another set. But like sets, it is not ordered (the elements can be set at any index).

Q52. How is frozen set different from set?

Ans:
Frozen set is just an immutable version of a Python set object. While elements of a set can be modified at any time, elements of the frozen set remain the same after creation.

Q53. What is union() in sets? Explain via code.

Ans:
The union() method returns a set that contains all items from the original set, and all items from the specified set(s).
You can specify as many sets you want, separated by commas.
It does not have to be a set, it can be any iterable object.
If an item is present in more than one set, the result will contain only one appearance of this item.

x = {"a", "b", "c"}
y = {"f", "d", "a"}
z = {"c", "d", "e"}
result = x.union(y, z)
print(result)

Output:{'a', 'e', 'c', 'b', 'f', 'd'}

Q54. What is intersection() in sets? Explain via code.

Ans:
The intersection() method returns a set that contains the similarity between two or more sets.
Meaning: The returned set contains only items that exist in both sets, or in all sets if the comparison is done with more than two sets.
x = {"a", "b", "c"}
y = {"c", "d", "e"}
z = {"f", "g", "c"}
result = x.intersection(y)
print(result)

Output:
{'c'}

Q55. What is dictionary in Python?

Ans: A dictionary is a collection which is ordered*, changeable and do not allow duplicates.

 Dictionaries are used to store data values in key:value pairs.

Q56. How is dictionary different from all other data structures.

Q57. How can we delare a dictionary in Python?

Q58. What will the output of the following?

var = {}
print(type(var))

Ans;<class 'dict'>

Q59. How can we add an element in a dictionary?

Ans:Adding an item to the dictionary is done by using a new index key and assigning a value to it
thisdict = {
  "brand": "Ford",
  "model": "Mustang",
  "year": 1964
}
thisdict["color"] = "red"

Q60. Create a dictionary and access all the values in that dictionary.

Ans:
thisdict = {
  "brand": "Ford",
  "model": "Mustang",
  "year": 1964
}
all_values = thisdict.values()

Q61. Create a nested dictionary and access all the element in the inner dictionary.

Ans:
students = {
    123: {'name' : 'Alice', 'age': '23'},
    321: {'name' : 'Bob', 'age': '34'}
}
name1 = students[123]['name']
name2 = students[321]['name']
age_alice=students[123]['age']
age_Bob=students[321]['age']
print(name1)
print(name2)
print(age_alice)
print(age_Bob)

Q62. What is the use of get() function?

Ans:
The get() method returns the value of the item with the specified key.
dictionary.get(keyname, value to be displayed if key doesnt exist)

Q63. What is the use of items() function?

Ans:The items() method returns a view object that displays a list of dictionary's (key, value) tuple pairs.
marks = {'Physics':67, 'Maths':87}
print(marks.items())

#Output: dict_items([('Physics', 67), ('Maths', 87)])

Q64. What is the use of pop() function?

Q65. What is the use of popitems() function?

Q66. What is the use of keys() function?

Q67. What is the use of values() function?

Q68. What are loops in Python?

Q69. How many type of loop are there in Python?

Q70. What is the difference between for and while loops?

Q71. What is the use of continue statement?

Q72. What is the use of break statement?

Q73. What is the use of pass statement?

Q74. What is the use of range() function?

Q75. How can you loop over a dictionary?

Ans:

Coding problems
Q76. Write a Python program to find the factorial of a given number.

Ans:
num=int(input("enter num:"))
factorial=1
for i in range(1,num+1):
  factorial=factorial*i

print(f"Factorial of {num} ={factorial}")

Q77. Write a Python program to calculate the simple interest. Formula to calculate simple interest is SI = (PRT)/100

Ans:
def simple_interest(p,t,r):
    si = (p * t * r)/100
    print('The Simple Interest is', si)
 
simple_interest(1000, 5, 7)

Q78. Write a Python program to calculate the compound interest. Formula of compound interest is A = P(1+ R/100)^t.

Ans:
 
def compound_interest(principle, rate, time):
    Amount = principle * (pow((1 + rate / 100), time))
    CI = Amount - principle
    print("Compound interest is", CI)
    
compound_interest(20000, 10, 6)

Q79. Write a Python program to check if a number is prime or not.

Ans:
num=int(input("enter num:"))
if num%2==0:
  print("Number is Even")
else:
  print("Number is Odd")

Q80. Write a Python program to check Armstrong Number.

Ans:
num=input("enter num:")
s=0
n=len(num)
for i in num:
  s=s+ pow(int(i),n)
if int(num)==s:
  print("Armstrong number")
else:
  print("Not an Armstrong number")


Q81. Write a Python program to find the n-th Fibonacci Number.

Ans:
terms=int(input())
a,b=0,1
while True:
  print(a)
  a,b=b,a+b
  if a ==terms:
    break

Q82. Write a Python program to interchange the first and last element in a list.

Ans:l = [1000,298,3579,100,200,-45,900]
l[0],l[-1]=l[-1],l[0]
print(l)

Q83. Write a Python program to swap two elements in a list.

Ans:
l = [1000,298,3579,100,200,-45,900]
p1=2
p2=4
l[p1-1],l[p2-1]=l[p2-1],l[p1-1]
print(l)


Q84. Write a Python program to find N largest element from a list.

Ans:
def N_largest_elements(num_list,N):
     print(sorted(num_list)[-N:])

Q85. Write a Python program to find cumulative sum of a list.

Ans:
num_list=[1,2,3,4,5,6,7,8,9,10]
sum=0
for i in num_list:
    sum=sum+i
    print(sum)

Q86. Write a Python program to check if a string is palindrome or not.

Ans:
string = "rohhor"
s=""
for j in range(len(string)):
  s=''.join(string[j])+s
if s==string:
    print("palindrome") 
else:
    print("not palindrome")
    
Q87. Write a Python program to remove i'th element from a string.

Ans:
string = "rohit"
i=2
s=""
for j in range(len(string)):
  if j==i-1:
    continue
  else:
    s=s+''.join(string[j])

print(s)

Q88. Write a Python program to check if a substring is present in a given string.

Ans:
string = "my name is rohit"  
substring = "name"
s = string.split()
if substring in s:
    print("substring is present")
else:
    print("substring is not present")


Q89. Write a Python program to find words which are greater than given length k.

ANS:
def string_k(k, str):
    string = []
    text = str.split(" ")
    for word in text:
        if len(word) > k:
            string.append(word)
            
    return string   
k = 3
str ="my name is rohit"
print(string_k(k, str))

Q90. Write a Python program to extract unique dictionary values.

Ans:list(set([i for i in dict1.values()]))

Q91. Write a Python program to merge two dictionary.

Ans:
1)def Merge(dict1, dict2):
    return(dict2.update(dict1))
2)def Merge(dict1, dict2):
    res = {**dict1, **dict2}
    return res
3)def Merge(dict1, dict2):
    res = dict1 | dict2
    return res

Q92. Write a Python program to convert a list of tuples into dictionary.

Input : [('Sachin', 10), ('MSD', 7), ('Kohli', 18), ('Rohit', 45)]
Output : {'Sachin': 10, 'MSD': 7, 'Kohli': 18, 'Rohit': 45}

Ans:
tuple_list=[('Sachin', 10), ('MSD', 7), ('Kohli', 18), ('Rohit', 45)]
tuple_dict={}
for i in range(len(tuple_list)):
  tuple_dict[tuple_list[i][0]]=tuple_list[i][1]
print(tuple_dict)



Q93. Write a Python program to create a list of tuples from given list having number and its cube in each tuple.

Input: list = [9, 5, 6]
Output: [(9, 729), (5, 125), (6, 216)]

Ans:
test_list= [9,5,6]
print([(a, a*a*a) for a in test_list])


Q94. Write a Python program to get all combinations of 2 tuples.

Input : test_tuple1 = (7, 2), test_tuple2 = (7, 8)
Output : [(7, 7), (7, 8), (2, 7), (2, 8), (7, 7), (7, 2), (8, 7), (8, 2)]

Ans:
test_tuple1 = (7, 2)
test_tuple2 = (7, 8)
print( [(a, b) for a in test_tuple1 for b in test_tuple2] +  [(a, b) for a in test_tuple2 for b in test_tuple1])

#test_tuple = [9,5,6]
#print( [(a, b) for a in test_tuple for b in test_tuple if a!=b])
#[(9, 5), (9, 6), (5, 9), (5, 6), (6, 9), (6, 5)]

Q95. Write a Python program to sort a list of tuples by second item.

Input : [('for', 24), ('Geeks', 8), ('Geeks', 30)] 
Output : [('Geeks', 8), ('for', 24), ('Geeks', 30)]

Ans:
a=[('for', 24), ('Geeks', 8), ('Geeks', 30)] 
print(sorted(a,key= lambda x:x[1]))

OR
a=[('for', 24), ('Geeks', 8), ('Geeks', 30)] 
for i in range(0, len(a)):
         
        for j in range(0, len(a)-i-1):
            if (a[j][1] > a[j + 1][1]):
                temp = a[j]
                a[j]= a[j + 1]
                a[j + 1]= temp
print(a)

Q96. Write a python program to print below pattern.

* 
* * 
* * * 
* * * * 
* * * * * 

Ans:

for i in range(1,6):
    print("*"*i,end="")
    print()

Q97. Write a python program to print below pattern.

    *
   **
  ***
 ****
*****

Ans:
j=1
for i in range(5,0,-1):
    print(" "*i,end="")
    print("*" * j)
    j+=1
    
Q98. Write a python program to print below pattern.

    * 
   * * 
  * * * 
 * * * * 
* * * * * 

Ans:

j=1
for i in range(5,0,-1):
    print(" "*i,end="")
    print("* " * j)
    j+=1

Q99. Write a python program to print below pattern.

1 
1 2 
1 2 3 
1 2 3 4 
1 2 3 4 5

Ans:
for i in range(1,6):
  for j in range(1,i+1):
    print(j,end="")
  print()
  
Q100. Write a python program to print below pattern.

A 
B B 
C C C 
D D D D 
E E E E E 

Ans:
a=['A','B','C','D','E']
for i in range(len(a)):
  print(a[i]*(i+1))
