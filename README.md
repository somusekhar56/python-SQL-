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



















