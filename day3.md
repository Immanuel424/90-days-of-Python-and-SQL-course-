# INTERVIEW QUESTIONS FOR INTRODUCTION CLASS

 0. Introduce yourself.
 1. Tell me about Python?
 2. Why Python is so popular now a days?
 3. Features of Python
 4. Advantages and Disadvantages of Python
 5. Interpreted vs Compiled time programming languages. Explain in detail
 6. .py vs .pyc files
 7. How compilation will happen internally. Explain in detail
 8. Why Python is Dynamically typed programming Language. Explain
 9. Python is Platform independent.Explain?
10. Different ways to write python program. Interactive, IDLE, CommandPrompt, IDE   Advantages, Disadvantages
11. sourcecode vs bytecode
12. Register instruction set
13. High Level vs Low level programming Language
14. Python architecture
15. Explain Garbage Collection mechanism in detail.

# Tell me about Python?
**Python** is a general Purpose, **Dynamic**, Highlevel, **Interpreted** programming language, it was created by Guido van Rossum during 1985- 1990 
- **General Purpose** - is a programming language that can create all types of programs.
- **Dynamic** - Python is dynamically typed, which means we don't need to declare the type of a variable. we can assign values of any type to   a variable, and the type is determined at runtime based on the assigned value. For example, we can assign an integer to a variable and   later assign a string to the same variable without any explicit type declarations.

# Why Python is so popular now a days?
- Becuase it is easy to learn and Use, and its is code readability, easy to understand the syntax
- Programmers can express logical concepts in fewer lines or in simple syntax, compare to C++ or JAVA
- Because of its Versatile Nature -Python is a versatile language that can be used for a wide range of applications. It has extensive       libraries and frameworks that support web development, data analysis, machine learning, automation, and more.
- It Exist Inbuilt functions for almost all of the frequntly used concepts.
- it supports for big libraries like (numpy pandas, selenium, Django, OpenCV,jupyternotebook,spiderebook)

# Features of Python
**Interpreted** - 
- There are no separate compilation and execution steps like C and C++, Java
- Directly run the program from the source code.
- Internally, Python converts the source code into an intermediate form called **bytecodes** then which reads and executes the code line   by line by translating and Execute the program immediatly.

**Platform Independenet**
- Python programs can be developed and executed on multiple operating system platforms.
- Python can be used on Linux, Windows, Macbook, Solaris and many more.

**Free and Open Source** - it is free to download and easiy to use 

**High Level Language**
- High-level languages are designed to be human-readable and programmer-friendly.

**Simple** 
- Closer to learning Mathematics basics in English medium. Easy to Learn
- More emphasis on the solution to the problem rather than the syntax

**Robust** 
- Exceptional handling features
- Memory management techniques in built

**Easy-to-learn**
- Python has few keywords, simple structure, and a clearly defined syntax. This allows the student to pick up the language quickly.

**Easy-to-read**
- Python code is more clearly defined and visible to the eyes.

**Easy-to-maintain**
- source code is fairly easy-to-maintained

**Databases**
- Python provides interfaces to all major commercial databases.

# Advantages and Disadvantages of Python
  ```
               Advanatges                                                       Disadvanatages
 - Python Supports all Functions and Performs Easily      - it has limited support for **mobile app development** and browser-based apps
 - Python Code run Line by Line                           - Runs the Program Slowly as compares to other languages
 - Pyhton Syntax is Very Simple                           - Memory Consumption Compared to other languages 
 - Pyhton GUI Provide better Functionality as 
   compared to other langauges 
 - Phython is Easy to Maintain
 ```
 
 # Interpreted vs Compiled time programming languages. Explain in detail?
``` 
**Interpreted Programming Language**
   Interpreted languages, as the name suggests, are executed by an interpreter. When an interpreted language program is run, the            interpreter reads the source code line by line, translates each line into bytecode, and executes it immediately.
   **Some examples of interpreted languages include Python, JavaScript, Ruby, and PHP**
   Key Characteristics of Interpreted Language is 
   1 Readability and Portability
   2 Dynamic Typing
   3 Immediate Feedback and Debugging
   4 Slower Execution Speed
   
**Compiled Programming Language**
   Compiled languages, on the other hand, go through a separate compilation step before execution. The source code is first passed          through a compiler, which translates the entire code into machine code or bytecode in a single process. This compiled code is then        executed directly by the computer's hardware or a virtual machine
   **Examples of compiled languages include C, C++, Java, and Go**
   Key Characteristics of Compiled Language is 
   1 Performance
   2 Static Typing
```
# .py vs .pyc files
**.py**
- .py is the file that we create and it contain exact sourcecode of the program
**.pyc**
- .pyc(pycache) contains the bytecode  of the Program we get this file after compiling the .py file 
   its not created for all the files we run ....when we import any file then it will create 
   
# How compilation will happen internally. Explain in detail
- The process of compilation in programming languages involves transforming human-readable source code into machine-executable             instructions. While the specific steps may vary depending on the language and compiler implementation.
1 Lexical Analysis:It is a fundamental step in which a sequence of characters(sourcecode) is divided into meaningful units called tokens.
2 Syntax Analysis:
3 Semantic Analysis:
4 Intermediate Code Generation:
5 Optimization
6 Code Generation
7 Linking 
8 Executable Program

# Why Python is Dynamically typed programming Language. Explain
- Python is considered a dynamically typed programming language because variable types are determined and checked at runtime, rather than   being explicitly declared at compile time. In Python, you can assign values of different types to variables without explicitly           specifying their types.
- x = 20                            Int v = 10
- x  = "immanuel"

# Python is Platform independent.Explain
- Python programs can be developed and executed on multiple operating system platforms.
- Python can be used on Linux, Windows, Macbook, Solaris and many more.

# Different ways to write python program, Interactive, IDLE, CommandPrompt, IDE Advantages, Disadvantages**

**Interactive Mode**

Advantages:
- Allows you to execute Python code line by line and see immediate results.
- Useful for experimenting, testing small code snippets, and learning Python interactively.
- Provides a quick and easy way to explore Python's features and test ideas.

Disadvantages:
- Not suitable for writing larger programs or organizing complex code structures.
- Lack of file management capabilities, making it difficult to save and reuse code.
- Limited in terms of project management and code organization features.

**IDLE (Integrated Development and Learning Environment)**

Advantages:
- Comes bundled with Python and provides a basic integrated development environment.
- Offers features like code highlighting, code completion, and a Python shell for interactive testing.
- Suitable for beginners and small-scale projects with simpler requirements.

Disadvantages:
- Lacks advanced features found in more powerful IDEs.
- May feel limited in terms of customization and extensibility options.
- Not as robust or feature-rich as dedicated IDEs.

**Command Prompt (Terminal)**

Advantages:
- Provides a lightweight and efficient way to run Python programs.
- Suitable for running scripts and automated tasks from the command line.
- Useful for executing Python programs in a server environment or through scripts.

Disadvantages:
- Lacks the convenience of an integrated development environment.
- Limited in terms of code editing features and interactivity.
- Requires manual management of files and dependencies.

**Integrated Development Environments (IDEs)**

Advantages:
- Offers a comprehensive set of features for writing, testing, and debugging code.
- Provides code editors with syntax highlighting, code completion, and debugging tools.
- Offers project management features, version control integration, and code refactoring capabilities.
- Allows for efficient code navigation and organization.

Disadvantages:
- Can be resource-intensive and slower to start compared to simpler tools.
- May have a steeper learning curve, especially for beginners.
- Some IDEs are not as lightweight and may consume more system resources.

# sourcecode vs bytecode
```
         SOURCECODE                                      BYTECODE 
- Easily readable and understandable         - Not intended for human reading
- Not directly executable                    - Executable by the Python interpreter
- Not compiled                               - Generated through compilation process
- Typically larger                           - Typically Smaller
- can be Modified and Updated                - Not Intended for manual Modification 
- Distributed as source code files           - Distributed as compiled bytecode files
```

# Register instruction set
- Register are fast acess memory Location that holds temporory data during the execution of Instructions, it handles internally by the     Python Interpreter to execute the code Efficiently. 

# High Level vs Low level programming Language
```
     High Level Language                                                  Low Level Language 
- Generally more readable and closer to human language         - Less readable and closer to machine language
- Automatic memory management (garbage collection)             - Manual memory management
- Easier to learn and use for beginners                        - Steeper learning curve and more technical requirements
- Examples - Python, Java, C#, JavaScript,C, C++               - Examples - Assembly language, Machine code language 
```

# Python architecture

**Source Code**: Python programs are written in plain text files with a .py extension. These files contain the instructions and lo         written by the programmer

**Interpreter**: The Python interpreter is responsible for executing Python programs. It reads the source code, converts it into           instructions that the computer can understand, and executes them line by line.

**Compiler**  : The Python interpreter includes a compiler that converts the source code into a lower-level representation called           bytecode. Bytecode is a set of instructions that can be executed by the Python Virtual Machine (PVM).

**Bytecode**   : Bytecode is a binary format that represents the compiled Python code. It is stored in .pyc or .pyo files (compiled         Python files) for faster execution in subsequent runs.

**Python Virtual Machine (PVM)** : The PVM is a runtime environment that executes the bytecode. It interprets the instructions and         performs the necessary operations, such as memory management, object creation, and exception handling.

**Standard Library**: Python comes with a comprehensive standard library that provides a wide range of modules and functions for cotasks.   The standard library covers areas such as file handling, networking, math operations, and more.

**Extension Modules**: Python allows the integration of extension modules written in other languages like C or C++. These modules provide   additional functionality and can be used alongside Python code.
```
**This combination enables the execution of python program across different platforms and facilitates the development of versatile         application**
```

# Explain Garbage Collection mechanism in detail.
- Garbage collection is an automatic memory management mechanism in programming languages that helps reclaim memory that is no longer       needed for the program. It relieves the programmer from manually allocating and deallocating memory, reducing the risk of memory leaks   and memory-related bugs. 




   
   
  

  
  


