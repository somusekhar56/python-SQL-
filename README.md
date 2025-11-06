#  1 Error and Exception Handling:
In Python, errors happen when something goes wrong in your program.
To prevent the program from crashing, we use exception handling to catch and handle those errors gracefully.
* try Code that may raise an error
* except Handles the error
* else runs only when no error occurs
* finally always runs (used for clean-up actions)
# What is the use of the finally block?
The finally block always executes, whether an exception occurs or not.
Commonly used for resource cleanup (e.g., closing files or DB connections).
# Common Types of Errors
# 1 Syntax Errors – mistakes in code structure:
When we say “compile-time error” in Python, it usually refers to syntax errors — issues the interpreter detects before running the program.
<img width="1152" height="174" alt="image" src="https://github.com/user-attachments/assets/ca57a950-1c08-4a80-8079-b2f707b30714" />
# 2 Runtime Errors (Exceptions) – occur while the program is running:

<img width="1081" height="251" alt="image" src="https://github.com/user-attachments/assets/4c026aef-089b-45db-9675-661928d9d237" />

# 3 Division with Exception Handling:
<img width="1038" height="270" alt="image" src="https://github.com/user-attachments/assets/39ac5976-cb7d-4203-885d-66698657fd45" />

# 2 Higher-Order Functions (map, flatmap, etc.) 
A Higher-Order Function is a function that can take another function as an argumentor can return a function as a result. Examples of built-in HOFs: map(), filter(), reduce(), sorted(), flatmap()
# Using map() with a function
<img width="1152" height="334" alt="image" src="https://github.com/user-attachments/assets/04ca8a27-7202-4d16-b990-472cf240293c" />

# Using map() with a lambda function:
<img width="1071" height="129" alt="image" src="https://github.com/user-attachments/assets/9e15bb60-c1a4-4e5a-ab1d-d5fd20bdbb1a" />

# Usingflatmap() (Concept): 
<img width="1148" height="124" alt="image" src="https://github.com/user-attachments/assets/df5bbd56-6dd9-413b-8a30-efe8cb046145" />

# Simulating flatMap Behavior:
Flattening using list comprehension
<img width="1152" height="151" alt="image" src="https://github.com/user-attachments/assets/1730512c-a055-459b-89ac-ecbb14c421cb" />

# filter()
Filters items based on a condition.
<img width="881" height="177" alt="image" src="https://github.com/user-attachments/assets/3d572e5d-8b8e-4766-b479-e5f1f6a06f24" />

# reduce()
Reduces a list to a single value.
<img width="1063" height="154" alt="image" src="https://github.com/user-attachments/assets/ca320f36-3904-4203-9de7-669d36a02777" />

# SQL
Aggregation Functions (SUM, AVG, COUNT, MIN, MAX) and Clauses (WHERE, GROUP BY, HAVING, ORDER BY)
# SUM()
Adds up numeric values SUM(marks)
<img width="1002" height="438" alt="image" src="https://github.com/user-attachments/assets/8a3dd01b-5a68-416a-a137-0e8e2e5b3cec" />
# AVG()
Returns the average value AVG(marks)
<img width="1012" height="477" alt="image" src="https://github.com/user-attachments/assets/480e8f62-6ca9-4a4d-a820-23060decf0fa" />
# COUNT()
Counts the number of rows COUNT(id)
<img width="1006" height="398" alt="image" src="https://github.com/user-attachments/assets/951d3abb-1e3b-4846-96a3-36a7a71bb098" />
# MIN()
Returns the smallest value MIN(marks)
<img width="909" height="403" alt="image" src="https://github.com/user-attachments/assets/1c26e86f-f000-470c-b306-0e9ba1377526" />
# MAX()
Returns the largest value MAX(marks)
<img width="972" height="400" alt="image" src="https://github.com/user-attachments/assets/5248464c-d693-405e-9583-f07a8d4fc66f" />

# Group by:
The GROUP BY clause is used to group rows that have the same values in one or more columns.It is usually used with aggregate functions like SUM(), COUNT(), AVG(), MAX(), MIN() to summarize data.
<img width="991" height="523" alt="image" src="https://github.com/user-attachments/assets/71ccb74f-45f0-4883-83ce-e9d9b271a515" />

# Having clause:
The HAVING clause in SQL is used to filter groups of records created by the GROUP BY clause.Unlike WHERE, which filters individual rows, HAVING filters aggregated data (like SUM, COUNT, AVG, MAX, MIN).
<img width="902" height="486" alt="image" src="https://github.com/user-attachments/assets/a151e98d-16e1-461a-bef8-1f47162c6590" />

# Order by:
The ORDER BY clause is used to sort the result set of a query.By default, it sorts in ascending order (ASC). You can also sort in descending order (DESC).It can sort by one or more columns.

# Ascending order (ASC)

<img width="943" height="455" alt="image" src="https://github.com/user-attachments/assets/45d53a90-94d6-4309-ba19-1cacc280a5a6" />
# Descending order (DESC)
<img width="1010" height="488" alt="image" src="https://github.com/user-attachments/assets/48bf19a4-cad5-4aef-b6c1-e167809e88f4" />




# Window Functions: 
Window Functions in SQL are powerful analytical functions that perform calculations across a set of rows related to the current row, without collapsing them into a single row (unlike GROUP BY).

# 1.RANK()
if two have same salary, next rank is skipped.
RANK() assigns the same rank for ties (Bob & Charlie = 1), but skips the next rank (no rank 2 in IT).
<img width="998" height="525" alt="image" src="https://github.com/user-attachments/assets/65ade414-455a-4350-9a8c-a0c1c7fc616d" />

# 2 DENSE_RANK()
Like RANK(), but without skipping numbers.
<img width="1002" height="504" alt="image" src="https://github.com/user-attachments/assets/52940a4f-a2fc-46d6-a633-6b9e4d7187db" />

# 3 ROW_NUMBER()
Gives a unique number to each employee within their department.
<img width="987" height="517" alt="image" src="https://github.com/user-attachments/assets/fa53fc56-2421-496e-9c39-76674bad4056" />

# 4. AVG() as a Window Function
Shows each employee’s department average alongside their salary.
<img width="993" height="515" alt="image" src="https://github.com/user-attachments/assets/fa28bad9-6aa3-4147-9e6a-d5570ace958e" />

# 5 NTILE()
Divides employees into 3 salary bands
<img width="984" height="580" alt="image" src="https://github.com/user-attachments/assets/3f3f1e16-5a77-4950-b9dc-cbff064f9063" />

# Object-Oriented Programming (OOP):
Object-Oriented Programming (OOP) is a programming paradigm based on the concept of objects — which bundle data (attributes) and behavior (methods) together.











































