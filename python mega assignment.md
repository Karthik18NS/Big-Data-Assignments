Q1. Why do we call Python as a general purpose and high-level programming language?
ans: Python is an object-oriented, high-level programming language. Object-oriented means this language is based around objects (such as data) rather than functions, and high-level means it's easy for humans to understand.


Q2. Why is Python called a dynamically typed language?
ans: Python don't have any problem even if we don't declare the type of variable. It states the kind of variable in the runtime of the program. Python also take cares of the memory management which is crucial in programming. So, Python is a dynamically typed language


Q3. List some pros and cons of Python programming language?
ans: Pros:: Beginner-friendly,Large Community,Flexible and Extensible,Extensive Libraries,Embeddable
     Cons:: Issues with design,Slower than compiled languages,Security,Work environment,High memory consumption


Q4. In what all domains can we use Python?
ans: Since Python is the go-to programming language for domains such as artificial intelligence, machine learning and deep learning, it's no surprise that it's also a fundamental tool for any data scientist.


Q5. What are variable and how can we declare them?
ans: Variables are the basic unit of storage in a programming language. These variables consist of a data type, the variable name, and the value to be assigned to the variable. Unless and until the variables are declared and initialized, they cannot be used in the program.


Q6. How can we take an input from the user in Python?
ans:  Python input() function is used to take user input. By default, it returns the user input in form of a string.



Q7. What is the default datatype of the value that has been taken as an input using input() function?
ans: the input() function by default returns the value as string data type​.


Q8. What is type casting?
ans: Converting one datatype into another is known as type casting or, type-conversion.


Q9. Can we take more than one input from the user using single input() function? If yes, how? If no, why?
ans: Using split() method : 
This function helps in getting multiple inputs from users. It breaks the given input by the specified separator. If a separator is not provided then any white space is a separator. Generally, users use a split() method to split a Python string but one can use it in taking multiple inputs.


Q10. What are keywords?
ans: Keywords in Python are unique reserved words that cannot use a keyword as a variable, function, or other identifiers.


Q11. Can we use keywords as a variable? Support your answer with reason?
ans: no ,Suppose True keyword in python. If you use this keyword as variable, then compiler will get confused whether it is a variable or keyword.


Q12. What is indentation? What's the use of indentaion in Python?
ans: Indentation refers to the spaces at the beginning of a code line. Where in other programming languages the indentation in code is for readability only, the indentation in Python is very important. Python uses indentation to indicate a block of code.


Q13. How can we throw some output in Python?
ans: The basic way to do output is the print statement. To end the printed line with a newline, add a print statement without any objects. This will print to any object that implements write(), which includes file objects.


Q14. What are operators in Python?
ans: In Python, operators are special symbols that designate that some sort of computation should be performed. The values that an operator acts on are called operands. Here is an example: >>> >>> a = 10 >>> b = 20 >>> a + b 30.


Q15. What is difference between / and // operators?
ans: Both / and % are two different operators used in Python. These operators are mathematical operators and both have different uses.
/ Only perform the division operation in mathematics and returns results as the quotient.
While % is known as modulus.


Q16. Write a code that gives following as an output?
ans: print("iNeuroniNeuroniNeuroniNeuron")


Q17. Write a code to take a number as an input from the user and check if the number is odd or even?
a=int(input("enter the number"))
if a%2==0:
    print("Even")
else:
    print("Odd")


Q18. What are boolean operator?
ans: Boolean Operators are simple words (AND, OR, NOT or AND NOT) used as conjunctions to combine or exclude keywords in a search, resulting in more focused and productive results.


Q19. What will the output of the following?
```
1 or 0

0 and 0

True and False and True

1 or 0 or 0
```?
ans: 1,0,false,1



Q20. What are conditional statements in Python?
ans: The if statement is a conditional statement in python, that is used to determine whether a block of code will be executed or not. Meaning if the program finds the condition defined in the if statement to be true, it will go ahead and execute the code block inside the if statement.


Q21. What is use of 'if', 'elif' and 'else' keywords?
ans: If Elif Else Statements
The if/elif/else structure is a common way to control the flow of a program, allowing you to execute specific blocks of code depending on the value of some data
if statement
If the condition following the keyword if evaluates as true, the block of code will execute. Note that parentheses are not used before and after the condition check as in other languages.
else statement
You can optionally add an else response that will execute if the condition
elif statement
Multiple conditions can be checked by including one or more elif checks after your initial if statement. Just keep in mind that only one condition will execute.


Q22. Write a code to take the age of person as an input and if age >= 18 display "I can vote". If age is < 18 display "I can't vote"?
ans: a=int(input("enter the age "))
     if a>=18:
        print("I can vote")
     elif a<18:
        print("I can't vote")   


Q23. Write a code that displays the sum of all the even numbers from the given list.
```
numbers = [12, 75, 150, 180, 145, 525, 50]
```?
ans: 
sum=0
for i in numbers:
    if i%2==0:
        sum=sum+i
print(sum)



Q24. Write a code to take 3 numbers as an input from the user and display the greatest no as output.
ans: a=int(input("Enter The Number"))
     b=int(input("Enter The Number"))
     c=int(input("Enter The Number"))

     if a>b and a>c:
            print(a)
     elif b>a and b>c:
            print(b)
     elif c>a and c>b:
            print(c)              



Q25. Write a program to display only those numbers from a list that satisfy the following conditions

- The number must be divisible by five

- If the number is greater than 150, then skip it and move to the next number

- If the number is greater than 500, then stop the loop
```
numbers = [12, 75, 150, 180, 145, 525, 50]?
ans:
 for i in numbers:
    if i>500:
        break
    elif i>150:
        continue
    elif i%5==0:
        print(i)        


Q26. What is a string? How can we declare string in Python?
ans:In computer programming, a string is a sequence of characters. For example, "hello" is a string containing a sequence of characters 'h', 'e', 'l', 'l', and 'o'.We use single quotes or double quotes to represent a string in Python


Q27. How can we access the string using its index?
ans:Indexing: One way is to treat strings as a list and use index values.


Q28. Write a code to get the desired output of the following
string = "Big Data iNeuron"
desired_output = "iNeuron"
ans:string[9:]

Q29. Write a code to get the desired output of the following
string = "Big Data iNeuron"
desired_output = "norueNi"
ans:string[::-1]

Q30. Resverse the string given in the above question.
ans:string[::-1]


Q31. How can you delete entire string at once?
ans:Whereas you can remove the entire string variable using the del command.


Q32. What is escape sequence?
ans:An escape character is a backslash \ followed by the character you want to insert.

Q33. How can you print the below string?
'iNeuron's Big Data Course'
ans:a='iNeuron\'s Big Data Course'

Q34. What is a list in Python?
ans:A list is an ordered data structure with elements separated by a comma and enclosed within square brackets.

Q35. How can you create a list in Python?
ans:To create a list in Python, we use square brackets ( [] ). Here's what a list looks like: ListName = [ListItem, ListItem1, ListItem2, ListItem3, ...]


Q36. How can we access the elements in a list?
ans:To access values in lists, use the square brackets for slicing along with the index or indices to obtain value available at that index.


Q37. Write a code to access the word "iNeuron" from the given list.
lst = [1,2,3,"Hi",[45,54, "iNeuron"], "Big Data"]
ans:print(lst[4][2])


Q38. Take a list as an input from the user and find the length of the list?
ans: my_list = list(input('Enter space-separated words: ').split())
     print(len(my_list))
     print(my_list)


Q39. Add the word "Big" in the 3rd index of the given list.?
lst = ["Welcome", "to", "Data", "course"]
ans:lst.insert(3,'Big')
    lst


Q40. What is a tuple? How is it different from list?
ans:The primary difference between tuples and lists is that tuples are immutable as opposed to lists which are mutable. Therefore, it is possible to change a list but not a tuple.The contents of a tuple cannot change once they have been created in Python due to the immutability of tuples. 


Q41. How can you create a tuple in Python?
ans:A tuple is created by placing all the items (elements) inside parentheses () , separated by commas. The parentheses are optional, however, it is a good practice to use them. A tuple can have any number of items and they may be of different types (integer, float, list, string, etc.).


Q42. Create a tuple and try to add your name in the tuple. Are you able to do it? Support your answer with reason.?
ans:no,Tuples are unchangeable, meaning that you cannot change, add, or remove items once the tuple is created.


Q43. Can two tuple be appended. If yes, write a code for it. If not, why?
ans:No,Tuple is immutable, although you can use the + operator to concatenate several tuples. The old object is still present at this point, and a new object is created.


Q44. Take a tuple as an input and print the count of elements in it?
ans:my_tuple = tuple(input('Enter space-separated words: ').split())
    print(len(my_tuple))
    print(my_tuple)


Q45. What are sets in Python?
ans:The sets are an unordered collection of data types. These are mutable, iterable, and do not consist of any duplicate elements.


Q46. How can you create a set?
ans:You can create an empty set in python by using the set() function. One can think an empty set can be created using the curly braces {}, but notice that python interprets empty curly braces as a dictionary. 


Q47. Create a set and add "iNeuron" in your set?
ans:thisset = {"apple", "banana", "cherry"}
    thisset.add("iNeuron")
    print(thisset)
    type(thisset)


Q48. Try to add multiple values using add() function?
ans: tset.add() takes exactly one argument 


Q49. How is update() different from add()?
ans:We use add() method to add single value to a set. We use update() method to add sequence values to a set. Here Sequences are any iterables including list , tuple , string , dict etc.


Q50. What is clear() in sets?
ans:The clear() method removes all elements in a set.


Q51. What is frozen set?
ans:Frozen set is just an immutable version of a Python set object. While elements of a set can be modified at any time, elements of the frozen set remain the same after creation. Due to this, frozen sets can be used as keys in Dictionary or as elements of another set.


Q52. How is frozen set different from set?
ans:A set is a mutable object while frozenset provides an immutable implementation. Additionally, the collections library includes the Counter object which is an implementation of a multiset, it stores both the unique items and a count as to how many times it has been added to the container.


Q53. What is union() in sets? Explain via code?
ans:The union() method returns a new set with elements from the set and all other sets (passed as an argument).
If the argument is not passed to union(), it returns a shallow copy of the set.
A = {'a', 'c', 'd'}
B = {'c', 'd', 2 }
C = {1, 2, 3}

print('A U B =', A.union(B))
print('B U C =', B.union(C))
print('A U B U C =', A.union(B, C))


Q54. What is intersection() in sets? Explain via code?
ans:intersection() method returns the intersection of set A with all the sets (passed as argument).

If the argument is not passed to intersection(), it returns a shallow copy of the set (A).
A = {2, 3, 5, 4}
B = {2, 5, 100}
C = {2, 3, 8, 9, 10}

print(B.intersection(A))
print(B.intersection(C))
print(A.intersection(C))


Q55. What is dictionary in Python?
ans:Dictionaries are Python's implementation of a data structure that is more generally known as an associative array. A dictionary consists of a collection of key-value pairs. Each key-value pair maps the key to its associated value.


Q56. How is dictionary different from all other data structures?
ans:A dictionary is a general-purpose data structure for storing a group of objects. A dictionary has a set of keys and each key has a single associated value. A dictionary has a set of keys and each key has a single associated value.


Q57. How can we delare a dictionary in Python?
ans:The first way is by using a set of curly braces, {}, and the second way is by using the built-in dict() function.


Q58. What will the output of the following.
var = {}
print(type(var))?
ans:it will define the class of a given variable


Q59. How can we add an element in a dictionary?
ans:thisdict = {
  "brand": "Ford",
  "model": "Mustang",
  "year": 1964
}
thisdict["color"] = "red"
print(thisdict)


Q60. Create a dictionary and access all the values in that dictionary?
ans:thisdict.values(),by refering to above example


Q61. Create a nested dictionary and access all the element in the inner dictionary?
ans:people = {1: {'Name': 'John', 'Age': '27', 'Sex': 'Male'},
          2: {'Name': 'Marie', 'Age': '22', 'Sex': 'Female'}}

for p_id, p_info in people.items():
    print("\nPerson ID:", p_id)
    
    for key in p_info:
        print(key + ':', p_info[key])


Q62. What is the use of get() function?
ans:The get() method returns the value of the item with the specified key.


Q63. What is the use of items() function?
ans:The items() method returns a view object. The view object contains the key-value pairs of the dictionary, as tuples in a list. The view object will reflect any changes done to the dictionary


Q64. What is the use of pop() function?
ans:Python list pop() is an inbuilt function in Python that removes and returns the last value from the List or the given index value.


Q65. What is the use of popitems() function?
ans:The popitem() method removes the item that was last inserted into the dictionary.The popitem() method removes a random item. The removed item is the return value of the popitem() method, as a tuple, see example below.


Q66. What is the use of keys() function?
ans:The keys() method returns a view object. The view object contains the keys of the dictionary, as a list.


Q67. What is the use of values() function?
ans:The values() method returns a view object. The view object contains the values of the dictionary, as a list. The view object will reflect any changes done to the dictionary


Q68. What are loops in Python?
ans:Looping means repeating something over and over until a particular condition is satisfied.


Q69. How many type of loop are there in Python?
ans:The three types of loops in Python programming are while loop, for loop, and nested loops.


Q70. What is the difference between for and while loops?
ans:The for and while loops are both conditional statements. A for loop is a single-line command that will be executed repeatedly. While loops can be single-lined or contain multiple commands for a single condition.


Q71. What is the use of continue statement?
ans:The continue keyword is used to end the current iteration in a for loop (or a while loop), and continues to the next iteration. 


Q72. What is the use of break statement?
ans:The break statement is frequently used to terminate the processing of a particular case within a switch statement.


Q73. What is the use of pass statement?
ans: The pass statement is used as a placeholder for future code. When the pass statement is executed, nothing happens, but you avoid getting an error when empty code is not allowed. Empty code is not allowed in loops, function definitions, class definitions, or in if statements.


Q74. What is the use of range() function?
ans:The range() function returns a sequence of numbers, starting from 0 by default, and increments by 1 (by default), and stops before a specified number.


Q75. How can you loop over a dictionary?
ans:You can loop through a dictionary by using a for loop. When looping through a dictionary, the return value are the keys of the dictionary, but there are methods to return the values as well.


============================================================CODING PROBLEMS=====================================================================

Q76. Write a Python program to find the factorial of a given number?
ANS:num = 7
# To take input from the user
#num = int(input("Enter a number: "))

factorial = 1

# check if the number is negative, positive or zero
if num < 0:
   print("Sorry, factorial does not exist for negative numbers")
elif num == 0:
   print("The factorial of 0 is 1")
else:
   for i in range(1,num + 1):
       factorial = factorial*i
   print("The factorial of",num,"is",factorial)


Q77. Write a Python program to calculate the simple interest. Formula to calculate simple interest is SI = (PRT)/100?
ans:
def simple_interest(p,t,r):
	print('The principal is', p)
	print('The time period is', t)
	print('The rate of interest is',r)
	
	si = (p * t * r)/100
	
	print('The Simple Interest is', si)
	return si
	
simple_interest(8, 6, 8)


Q78. Write a Python program to calculate the compound interest. Formula of compound interest is A = P(1+ R/100)^t?
ans:
def compound_interest(principal, rate, time):

	# Calculates compound interest
	Amount = principal * (pow((1 + rate / 100), time))
	CI = Amount - principal
	print("Compound interest is", CI)

# Driver Code
compound_interest(10000, 10.25, 5)


Q79. Write a Python program to check if a number is prime or not?
ans:
num = 407
# To take input from the user
#num = int(input("Enter a number: "))

if num == 1:
    print(num, "is not a prime number")
elif num > 1:
   # check for factors
   for i in range(2,num):
       if (num % i) == 0:
           print(num,"is not a prime number")
           print(i,"times",num//i,"is",num)
           break
   else:
       print(num,"is a prime number")
       
# if input number is less than
# or equal to 1, it is not prime
else:
   print(num,"is not a prime number")


Q80. Write a Python program to check Armstrong Number?
ans:Armstrong Number:the sum of cubes of each digit is equal to the number itself.

# Python program to check if the number is an Armstrong number or not

# take input from the user
num = int(input("Enter a number: "))

# initialize sum
sum = 0

# find the sum of the cube of each digit
temp = num
while temp > 0:
   digit = temp % 10
   sum += digit ** 3
   temp //= 10

# display the result
if num == sum:
   print(num,"is an Armstrong number")
else:
   print(num,"is not an Armstrong number")


Q81. Write a Python program to find the n-th Fibonacci Number?
ans:Fibonacci Number:Every number after the first two is the sum of the two preceding ones, which is known as Fibonacci's sequence.For example, consider the following series:

0, 1, 1, 2, 3, 5, 8, 13, 21, 34, 55, 89, 144, … and so on.

def fibonacci(n, second_last, last):
	if n-1 == 0:
		return second_last
	else:
		new_last = second_last + last
		second_last = last
		return fibonacci(n-1, second_last, new_last)


if __name__ == "__main__":
	print(fibonacci(10, 0, 1))


Q82. Write a Python program to interchange the first and last element in a list?
ans:# Python3 program to swap first
# and last element of a list

# Swap function
def swapList(newList):
	size = len(newList)
	
	# Swapping
	temp = newList[0]
	newList[0] = newList[size - 1]
	newList[size - 1] = temp
	
	return newList
	
# Driver code
newList = [12, 35, 9, 56, 24]

print(swapList(newList))


Q83. Write a Python program to swap two elements in a list?
ans:# Python3 program to swap elements
# at given positions

# Swap function
def swapPositions(list, pos1, pos2):
	
	list[pos1], list[pos2] = list[pos2], list[pos1]
	return list

# Driver function
List = [23, 65, 19, 90]
pos1, pos2 = 1, 3

print(swapPositions(List, pos1-1, pos2-1))


Q84. Write a Python program to find N largest element from a list?
ans:# Python program to find N largest
# element from given list of integers

# Function returns N largest elements
def Nmaxelements(list1, N):
	final_list = []

	for i in range(0, N):
		max1 = 0
		
		for j in range(len(list1)):	
			if list1[j] > max1:
				max1 = list1[j];
				
		list1.remove(max1);
		final_list.append(max1)
		
	print(final_list)

# Driver code
list1 = [2, 6, 41, 85, 0, 3, 7, 6, 10]
N = 2

# Calling the function
Nmaxelements(list1, N)


Q85. Write a Python program to find cumulative sum of a list?
ans:# Python code to get the Cumulative sum of a list
def Cumulative(lists):
	cu_list = []
	length = len(lists)
	cu_list = [sum(lists[0:x:1]) for x in range(0, length+1)]
	return cu_list[1:]

# Driver Code
lists = [10, 20, 30, 40, 50]
print (Cumulative(lists))


Q86. Write a Python program to check if a string is palindrome or not?
ans:# function which return reverse of a string

def isPalindrome(s):
	return s == s[::-1]


# Driver code
s = "malayalam"
ans = isPalindrome(s)

if ans:
	print("Yes")
else:
	print("No")


Q87. Write a Python program to remove i'th element from a string?
ans:# Python3 program for removing i-th
# indexed character from a string

# Removes character at index i


def remove(string, i):

	# Characters before the i-th indexed
	# is stored in a variable a
	a = string[: i]

	# Characters after the nth indexed
	# is stored in a variable b
	b = string[i + 1:]

	# Returning string after removing
	# nth indexed character.
	return a + b


# Driver Code
if __name__ == '__main__':

	string = "geeksFORgeeks"

	# Remove nth index element
	i = 5

	# Print the new string
	print(remove(string, i))


Q88. Write a Python program to check if a substring is present in a given string?
ans:# Take input from users
MyString1 = "A geek in need is a geek indeed"

if "need" in MyString1:
	print("Yes! it is present in the string")
else:
	print("No! it is not present")


Q89. Write a Python program to find words which are greater than given length k?
ans:Input : str = "hello geeks for geeks 
          is computer science portal" 
        k = 4
Output : hello geeks geeks computer 
         science portal
Explanation : The output is list of all 
words that are of length more than k.


# Python program to find all string
# which are greater than given length k

# function find string greater than length k


def string_k(k, str):

	# create the empty string
	string = []

	# split the string where space is comes
	text = str.split(" ")

	# iterate the loop till every substring
	for x in text:

		# if length of current sub string
		# is greater than k then
		if len(x) > k:

			# append this sub string in
			# string list
			string.append(x)

	# return string list
	return string


# Driver Program
k = 3
str = "geek for geeks"
print(string_k(k, str))


Q90. Write a Python program to extract unquire dictionary values?
ans:# Python3 code to demonstrate working of
# Extract Unique values dictionary values
# Using set comprehension + values() + sorted()

# initializing dictionary
test_dict = {'gfg': [5, 6, 7, 8],
			'is': [10, 11, 7, 5],
			'best': [6, 12, 10, 8],
			'for': [1, 2, 5]}

# printing original dictionary
print("The original dictionary is : " + str(test_dict))

# Extract Unique values dictionary values
# Using set comprehension + values() + sorted()
res = list(sorted({ele for val in test_dict.values() for ele in val}))

# printing result
print("The unique values list is : " + str(res))


Q91. Write a Python program to merge two dictionary?
ans:
dict_1 = {1: 'a', 2: 'b'}
dict_2 = {2: 'c', 4: 'd'}

print(dict_1 | dict_2)


Q92. Write a Python program to convert a list of tuples into dictionary.

Input : [('Sachin', 10), ('MSD', 7), ('Kohli', 18), ('Rohit', 45)]
Output : {'Sachin': 10, 'MSD': 7, 'Kohli': 18, 'Rohit': 45}
ans:
# Python code to convert into dictionary

def Convert(tup, di):
	for a, b in tup:
		di.setdefault(a, []).append(b)
	return di
	
# Driver Code
tups = [('Sachin', 10), ('MSD', 7), ('Kohli', 18), ('Rohit', 45)]
dictionary = {}
print (Convert(tups, dictionary))


Q93. Write a Python program to create a list of tuples from given list having number and its cube in each tuple.

Input: list = [9, 5, 6]
Output: [(9, 729), (5, 125), (6, 216)]
ans:
# Python program to create a list of tuples
# from given list having number and
# its cube in each tuple

# creating a list
list1 = [9,5,6]

# using list comprehension to iterate each
# values in list and create a tuple as specified
res = [(val, pow(val, 3)) for val in list1]

# print the result
print(res)


Q94. Write a Python program to get all combinations of 2 tuples.

Input : test_tuple1 = (7, 2), test_tuple2 = (7, 8)
Output : [(7, 7), (7, 8), (2, 7), (2, 8), (7, 7), (7, 2), (8, 7), (8, 2)]
ans:
# Python3 code to demonstrate working of
# All pair combinations of 2 tuples
# Using list comprehension

# initializing tuples
test_tuple1 = (7, 2)
test_tuple2 = (7, 8)

# printing original tuples
print("The original tuple 1 : " + str(test_tuple1))
print("The original tuple 2 : " + str(test_tuple2))

# All pair combinations of 2 tuples
# Using list comprehension
res = [(a, b) for a in test_tuple1 for b in test_tuple2]
res = res + [(a, b) for a in test_tuple2 for b in test_tuple1]

# printing result
print("The filtered tuple : " + str(res))


Q95. Write a Python program to sort a list of tuples by second item.

Input : [('for', 24), ('Geeks', 8), ('Geeks', 30)] 
Output : [('Geeks', 8), ('for', 24), ('Geeks', 30)]
ans:
# Python program to sort a list of tuples by the second Item

# Function to sort the list of tuples by its second item


def Sort_Tuple(tup):

	# getting length of list of tuples
	lst = len(tup)
	for i in range(0, lst):

		for j in range(0, lst-i-1):
			if (tup[j][1] > tup[j + 1][1]):
				temp = tup[j]
				tup[j] = tup[j + 1]
				tup[j + 1] = temp
	return tup


# Driver Code
tup = [('for', 24), ('is', 10), ('Geeks', 28),
	('Geeksforgeeks', 5), ('portal', 20), ('a', 15)]

print(Sort_Tuple(tup))


Q96. Write a python program to print below pattern.

* 
* * 
* * * 
* * * * 
* * * * * 
ans:# Python 3.x code to demonstrate star pattern

# Function to demonstrate printing pattern
def pypart(n):
	
	# outer loop to handle number of rows
	# n in this case
	for i in range(0, n):
	
		# inner loop to handle number of columns
		# values changing acc. to outer loop
		for j in range(0, i+1):
		
			# printing stars
			print("* ",end="")
	
		# ending line after each row
		print("\r")

# Driver Code
n = 5
pypart(n)


Q97. Write a python program to print below pattern.

    *
   **
  ***
 ****
*****
ans:
# Python 3.x code to demonstrate star pattern

# Function to demonstrate printing pattern
def pypart2(n):
	
	# number of spaces
	k = 2*n - 2

	# outer loop to handle number of rows
	for i in range(0, n):
	
		# inner loop to handle number spaces
		# values changing acc. to requirement
		for j in range(0, k):
			print(end=" ")
	
		# decrementing k after each loop
		k = k - 2
	
		# inner loop to handle number of columns
		# values changing acc. to outer loop
		for j in range(0, i+1):
		
			# printing stars
			print("* ", end="")
	
		# ending line after each row
		print("\r")

# Driver Code
n = 5
pypart2(n)


Q98. Write a python program to print below pattern.

    * 
   * * 
  * * * 
 * * * * 
* * * * * 
ans:# Python 3.x code to demonstrate star pattern

# Function to demonstrate printing pattern triangle
def triangle(n):
	
	# number of spaces
	k = n - 1

	# outer loop to handle number of rows
	for i in range(0, n):
	
		# inner loop to handle number spaces
		# values changing acc. to requirement
		for j in range(0, k):
			print(end=" ")
	
		# decrementing k after each loop
		k = k - 1
	
		# inner loop to handle number of columns
		# values changing acc. to outer loop
		for j in range(0, i+1):
		
			# printing stars
			print("* ", end="")
	
		# ending line after each row
		print("\r")

# Driver Code
n = 5
triangle(n)


Q99. Write a python program to print below pattern.

1 
1 2 
1 2 3 
1 2 3 4 
1 2 3 4 5
ans:# Python 3.x code to demonstrate star pattern

# Function to demonstrate printing pattern of numbers
def numpat(n):
	
	# initialising starting number
	num = 1

	# outer loop to handle number of rows
	for i in range(0, n):
	
		# re assigning num
		num = 1
	
		# inner loop to handle number of columns
			# values changing acc. to outer loop
		for j in range(0, i+1):
		
				# printing number
			print(num, end=" ")
		
			# incrementing number at each column
			num = num + 1
	
		# ending line after each row
		print("\r")

# Driver code
n = 5
numpat(n)


Q100. Write a python program to print below pattern.

A 
B B 
C C C 
D D D D 
E E E E E 
ans:# Python 3.x code to demonstrate star pattern

# Function to demonstrate printing pattern of alphabets
def alphapat(n):
	
	# initializing value corresponding to 'A'
	# ASCII value
	num = 65

	# outer loop to handle number of rows
	# 5 in this case
	for i in range(0, n):
	
		# inner loop to handle number of columns
		# values changing acc. to outer loop
		for j in range(0, i+1):
		
			# explicitly converting to char
			ch = chr(num)
		
			# printing char value
			print(ch, end=" ")
	
		# incrementing number
		num = num + 1
	
		# ending line after each row
		print("\r")

# Driver Code
n = 5
alphapat(n)




    




