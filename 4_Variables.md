# What is Variable ?
Variables are the **containers** to store **data/Values** in it. or it can also be called as **"Identifiers"**
```
x = 20
```
Here **X** is Variable, which is holding the value 20
- Value -- Fixed ,           Variable - Changes 

# How Variable will going to create in python to hold the Values or data?
It will be done by 2 methods,

1 Write Operation
2 Read Operation 
# 1 Write Operation
- Whenever we assign any value/data to the variable **First it starts execute from RHS**
- next, it will check whether the variable contains **Value/Expression**
- if the **Variable** contains **Value**   ----> Python going to find its type of **value** then that **value** will be converted to                                                      **Binary format**.
- if the **Variable** contains **Expression**--> Python **First simplifies the Expression** and gets the **final value** for that and                                                      that **value** will be converted to **Binary format**.
- for that Binary format -- **(memory allocation adress)** will be assign and the same **memory address** will be given to the *variable* 
# 2 Read Operation 
Read operation is nothing but **once the memory allocation adress is given to the variable, Python will got the adress of the variable and it will take the binary value from that adress and convert it to decimal format and retrieve the result**.
```
Example --- x = 20 
            print(x) ---->> read Operation 
```

# DATA TYPES

1 **Numbers** 
Numbers are of 3 types
- **Integers** = 10, 20, 40...etc (*Integers are whole Numbers*)
- **Float** = 10.4, 33.5, 27.4...etc ( Float for any numbers which as decimals in it)
- **Complex** = 4+2j (Complex is for any expression which ha real and Imaginary Part)

2 **Boolean** --> Booleans are **True or False type**,whenever we need to do decision making that time we use **Boolean data type**.

  ---> True  -  1bit   1
  
  ---> False -  1bit   0  

3 **String**--> String is one of the data type in python --> Anything which is enclosed with Single/Double coated that we can call it as                 String 
                Example -- "Hello World"
                "Immanuel", "VN2 Data"
           
**FOR UNDERSTANDING DATA TYPES WILL SEE ONE EXAMPLE**
```
 Example ---> Will take any Entity
               Entity Name - Employee
               Attributes -   Emp_name,    Emp_id,    Emp_Adress,     is_permanent
               State -       "Immanuel",    101,      "Vijayapura",     True
               DATA TYPE -     String,     Integer       String        Boolean
```
## Varible Assignment

1 **Assigning single Value to the Multiple Variable** - 
Python allow us to assign a single value to the Multiple Variable 

``` Example --> a,b,c = 25 
Here, 25 is an Integer value and all three variables assigned to the same memory location.```

2 **Assigning Multiple Values to the Multiple Variables** -
Python allows us to assign Multiple values to the Multiple Variable in single syntax 

``` Example --> a, b, c = 2, 4.7, "Immanuel" ```


## TOKENS AND THEIR TYPES 
**Tokens** are the smallest elements of a program, which are meaningful to the compiler.
Following are the types of Tokens 
- Identifiers
- Operators
- literals
- Keywords
- Constant
```
Identifiers                Operators                  Literals
    X                         =                          20
```

1 **Identifiers** -Usually Identifier is a Variable. A python identifier is a name used to identify the Variable,Function,classes,modules
2 **Operators** - Operator are the special symbols in python that carryout arithmetic or logical computition.
3 **literals** - Literals are raw values or data that are stored in variables/constants.
4 **Keywords** - Keywords are the unique/reserved words with defined meaning, that we can only apply on for those functions, and we                        cannot use those keywords as a variables.
```
Different keywords as follows
False, None, True, and, as, assert, async, await, break, class, continue,
def, del, elif, else, execpt, finally, for, from, global, if, import, in, 
is, lambda, nonlocal, not, or, pass, raise, return, try, while, with, yield.
```
5 **Constants** - Constants are the special type of variables, whose values are cannot be changed.
``` Example ---> Pi - 3.14
             Gravity - 9.8 ```
 



