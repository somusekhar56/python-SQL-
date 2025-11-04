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

Group by:
The GROUP BY clause is used to group rows that have the same values in one or more columns.It is usually used with aggregate functions like SUM(), COUNT(), AVG(), MAX(), MIN() to summarize data.
<img width="991" height="523" alt="image" src="https://github.com/user-attachments/assets/71ccb74f-45f0-4883-83ce-e9d9b271a515" />


# Window Functions: 
Window Functions in SQL are powerful analytical functions that perform calculations across a set of rows related to the current row, without collapsing them into a single row (unlike GROUP BY).



























