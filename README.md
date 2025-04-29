Assignment-NO.3-PIAIC-Python-Data-types-
📄 Assignment on Data Types in Python
1. What are Data Types?
Data Types define what kind of value a variable can hold.
Example: number, text, list, etc.

In Python, data types are mainly divided into:

2. Primitive Data Types
Primitive means basic/simple data types that hold single values.

Examples of Primitive Data Types:

Data Type	Example	Description
int	a = 5	Integer numbers (positive/negative)
float	b = 3.14	Decimal numbers
bool	c = True / c = False	Boolean (True or False)
str	d = "Hello"	String (text)
3. Non-Primitive Data Types
Non-Primitive means complex/collection of multiple values.

Examples of Non-Primitive Data Types:

Data Type	Example	Description
list	e = [1, 2, 3]	Collection of items, ordered
tuple	f = (1, 2, 3)	Like list but unchangeable
set	g = {1, 2, 3}	Unordered, no duplicate items
dict	h = {"name": "Abid", "age": 30}	Key-value pairs
4. Indexing in Python
Indexing means accessing a specific element inside a list, string, or tuple by its position.

Python indexing starts from 0.

Example:

python
Copy
Edit
my_list = [10, 20, 30, 40]
print(my_list[0])   # Output: 10
print(my_list[2])   # Output: 30
Example with string:

python
Copy
Edit
my_string = "Hello"
print(my_string[1])  # Output: 'e'
5. Slicing in Python
Slicing means cutting a part of list, string, or tuple.

Format:
list[start : stop : step]

Start = starting index (included)

Stop = ending index (not included)

Step = jump size

Example:

python
Copy
Edit
my_list = [1, 2, 3, 4, 5, 6]
print(my_list[1:5])  # Output: [2, 3, 4, 5]
Example with step:

python
Copy
Edit
print(my_list[0:6:2])  # Output: [1, 3, 5]
6. F-Strings in Python
F-strings are used to insert variables inside a string easily.

Format:
Prefix the string with f and write variables inside {}.

Example:

python
Copy
Edit
name = "Abid"
age = 25
print(f"My name is {name} and I am {age} years old.")
Output:

pgsql
Copy
Edit
My name is Abid and I am 25 years old.
📋 Conclusion:
Primitive = Single simple values (like int, float, bool, str).

Non-Primitive = Collections of values (like list, tuple, set, dict).

Indexing = Picking one item by position.

Slicing = Cutting out a piece of list/string.

F-String = Easiest way to use variables inside a text.

📚 Bonus Practice Tasks:
Make a list of your 5 favorite fruits and print the second fruit using indexing.

Slice a string "MachineLearning" to get "Machine".

Use an f-string to print your name and your favorite hobby.

