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

2 **Boolean** 

Booleans are **True or False type**.
whenever we need to do decision making that time we use **Boolean data type**. 

3 **String**

String is one of the data type in python --> Anything which is enclosed with Single/Double coated that we can call it as String 
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

