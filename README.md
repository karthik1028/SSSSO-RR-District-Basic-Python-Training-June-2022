# SSSSO-RR-District-Basic-Python-Training-June-2022
Basic Python Training Organized by Sri Sathya Sai Seva Organization RR District in the month of June 2022.

## Timings
1. Saturday - Evening - 6pm to 8pm
2. Sunday - Morning - 8am to 10am

> Total - 4 hours of training sessions per week

# Setting up git and github, python 3.10, VS Code
1. [programming knowledge channel - How to Install Git on Windows 10 + Setting Up Git and GitHub on Windows 10](https://www.youtube.com/watch?v=bb_LoXAC-zE)
2. [How to install python 3.10 on windows 10/11](https://www.youtube.com/watch?v=AwIXfaGEN4c)
3. [How to install visual studio code on windows 10/11](https://www.youtube.com/watch?v=JPZsB_6yHVo)

## List of Topics that will be covered under this training <a name="top"></a>

1. [Let's begin the Python Show](#1)
	* [History of Python](#1.1)
	* [What is Python](#1.2)
	* [Applications of Python](#1.3)
	* [How does Python Programming Language support a Complex Problem Decomposition](#1.4)
	* [What is an interpreter](#1.5)
	* [How To Open and Run the Interpreter Which is installed](#1.6)
	* [Comparison of python with other Languages](#1.7)
	* [Famous and Most used versions of python](#1.8)
	* [Why should we learn Python](#1.9)
2. [About Python](#2)
	* [Writing python scripts in a file and running it in the command line
	interface](#2.1)
	* [Commenting in python](#2.2)
	* [Print function](#2.3)
	* [Header for Python script](#2.4)
	* [Indentation](#2.5)
	* [Continuation lines](#2.6)
3. [Data Types](#3)
	* [Integers](#3.1)
	* [Floating point](#3.2)
	* [Complex](#3.3)
	* [boolean](#3.4)
	* [frozen sets](#3.5)
	* [Conversion of one data type to another](#3.6)
	* [Exercise - 1](#3.7)
4. [Variables](#4)
	* [Python Variables](#4.1)
	* [Common conventions followed for variable names](#4.2)
	* [Creating good names](#4.3)
	* [Exercise - 2](#4.4)
5. [User Input](#5)
	* [Input function](#5.1)
	* [Command line parameters (arguments)](#5.2)
	* [Exercise - 3](#5.3)
6. [Operators](#6)
	* [Numeric](#6.1)
	* [Assignment](#6.2)
	* [Comparision](#6.3)
	* [Logical](#6.4)
	* [Membership](#6.5)
	* [Identity](#6.6)
	* [Exercise -  4](#6.7)
7. [strings](#7)
	* [Indexing](#7.1)
	* [Object Identity](#7.2)
	* [Program using builtin function](#7.3)
	* [Formatting with .format method](#7.4)
	* [Important points to remember](#7.5)
	* [builtin functions, methods of string](#7.6)
	* [Exercise - 5](#7.7)
8. [Escape sequences](#8)
    * '\n' - [Newline character](#8)
    * '\r' - [Return character](#8)
    * '\b' - [Backspace character](#8)
    * '\\' - [Backslash character](#8)
    * '\”' - [Double quote character](#8)
    * '\’' - [Single quote character](#8)
    * '\t' - [Tab character](#8)
    * '\a' - [Alarm character](#8)
    * [Exercise - 6](#8.1)	
9. Conditional statements
	* If
	* If else
	* Nested If elif else
10. Loops
	* While
	*  for
11.  Lists
	* list comprehension 
12. Tuples 
13. Dictionaries
14. File Handling
	* Read 
	*  Write
	* delete
15. Functions
16. Exception Handling
17. Modules
18. Namespace
19. Packages
20. Built in tools
21. repr()
22. difference between running the code in vs code and jupyter notebook
23. assert (basic debugging) - to set a breakpoint
24. What editors are required to use in python 

## Answers <a name="answers"></a>

1. [Exercise - 1](#E-1)
2. [Exercise - 2](#E-2)
3. [Exercise - 3](#E-3)
4. [Exercise - 4](#E-4)
5. [Exercise - 5](#E-5)
6. [Exercise - 6](#E-6)

## **1. Let's begin the Python Show** <a name="1"></a>

### **History of Python** <a name="1.1"></a>

**Python** was developed by ***Guido van Rossum*** and was released first on **February 20, 1991** (31 years ago). It is one of the most widely-used and loved programming languages. It is also a **free** and **open-source language** with very simple and clean syntax.

### **What is Python?** <a name="1.2"></a>

1. **Python** is a **general-purpose high-level** programming language. Being a general-purpose language, it can be used to build almost any type of application with the right **tools** or **libraries**. 
2. Its standard library is large and comprehensive. This makes it easy for **developers** to learn python. 
3. Additionally, python supports **objects**, **modules**, **threads**, **exception-handling**, and **automatic memory management** which will help in modeling real-world problems and building applications to solve those problems. 
4. Python is widely used among the latest and most emerging fields such as **Machine Learning**, **Deep Learning**, **Artificial Intelligence**, **Web Development**, **Web Scraping**, **Data Mining**, **Data Visualization**, **Data Science** and various other trending domains.

### **Applications of Python?** <a name="1.3"></a>

**Python** has grown to become an integral part of most of the recent web-based, desktop-based, graphic design, scientific, and computational applications. **The following are just a few applications of the enormous python language**. The List goes on and goes, as we keep exploring more and more fields, where python is used extensively. 

- GUI based desktop applications
  > Tkinter, PyQT, Kivy, WxPython, PyGUI these are most widely used and best Python graphical user interface frameworks available.

- Graphic design, image processing applications, Games.
  >OpenCV, Pillow, SimpleITK are some libraries of image processing .
  
- Web frameworks and applications.
  >Django, Flask, TurboGears, web2py and some other Python web framework are used for Python Web development.

- Business applications 
  > Python is also used to build ERP and e-commerce systems like Oodo, Tryton, OpenERP.

- Operating Systems
  >Linux, FreeBSD, Windows, macOS are the operating systems.

- Database Access 
  > MySQL, PostgreSQL, MongoDB are some database servers used by Python.

- Scientific and Numeric
  > Python has many libraries for scientific and numeric such as Numpy, Pandas, Scipy, Scikit-learn, etc.

- Prototyping 
  > Developers can quickly write test/validation code which gives the expected results for small to medium data sets.

- Software Development
  > Scons, Buildbot, Apache Gump, Round up, Trac.
  
<br />

[go to List of Topics](#top)

<br />

### **How does Python Programming Language support a Complex Problem Decomposition?** <a name="1.4"></a>

1. **Python** supports **multiple** programming paradigms and features a fully dynamic type system and automatic memory management, similar to Perl, Tcl etc. Like other dynamic languages. Python is often used as a **scripting language**.
2. If you have to work with several C libraries, and the usual is order of C is
	> write code -> compile it -> test it -> re-write -> re-compile the code -> re-test.
	* So, The cycle is slow. You need to develop **software** more quickly. Possibly, perhaps you have written a program that could use an **extension language**, and you do not want to design a language, write and debug an interpreter for it, then tie it into your application.

3. **Python** allows you to split up your big program (program with many lines of code) into modules that can be **reused**, even into other Python programs as well. It comes with a **large collection** of standard modules that you can use as the basis of your programs, instead of writing code for each and everything from scratch.
4. There are also built-in modules that provide things like file I/O, system calls, sockets, and even interfaces to graphical user interface toolkits like Tk.

<br />

### **What is an interpreter?** <a name="1.5"></a>

1. An **interpreter** is a program that reads and executes code line-by-line. This includes source code, pre-compiled code, and scripts. 
2. Common interpreters include Perl, Python, and Ruby interpreters, which execute Perl, Python, and Ruby code respectively. 
3. If we write a Python code in a text file with a name like hello.py. How does that code Run? There is a program installed on your computer named "python3" or "python", and its job is to look at and run your Python code. This type of program is called an "interpreter".

<br />

### **How To Open and Run the Interpreter which was installed?** <a name="1.6"></a>

1. There are 2 easy ways to open the interpreter:

	  - Open a command-line terminal or command prompt.
    - **Mac** : run the "Terminal" app in the Utilities folder.
    - **Windows**: Type "Command Prompt" in the search box, this opens the Windows command prompt terminal. In the terminal, type the command "python3" or "python" or sometimes "py". This runs the interpreter program directly.
    - press ```ctrl+d``` or ```ctrl+z``` or ```type exit()``` to exit the interpreter.

	  - If you have **Visual Studio Code** installed, at the top of the VS Code window, click on the **Terminal** option. And then click on the **New Terminal** option.

    - > In Visual Studio Code : Terminal > New Terminal

2. When commands are read from a **tty**, the interpreter is said to be in **interactive** mode. In this mode it prompts for the next command with the primary prompt, usually three greater-than signs **(‘>>> ‘)**. ```>>>``` this symbol is called as ```chevron prompt```. It means that python interpreter is in ```interactive mode```, waiting for user input.
 
3. For continuation lines it prompts with the secondary prompt, by default three dots **(‘...’)**. The interpreter prints a welcome message stating its version number and a copyright notice before printing the first prompt. The symbol ```...``` in this context, should not be compared (or) correlated with ```... <ellipsis>``` operator of python.

4. Continuation lines are needed when entering a multi-line construct. As an example, look at this if statement:

![](https://github.com/saikrishnavadali05/python3_ebook/blob/master/Images/Screenshot%202022-01-31%20110438.jpg?raw=true)


### **Comparison of python with other Languages?** <a name="1.7"></a>
  
Column | Python | Java   | C++    | C 
:----- | :----: | -----: | :----: | -----:
Code Executor | Interpreter| Compiler | Compiler | Compiler
Learning and Coding Difficulty Level | Very Easy | Medium | Medium  | Difficult
Number of Lines of Code (SLOC)  | Very less  | Less | Many | Extremely Many
Costs incurred to Build Applications  | Less Expensive  | Expensive | More expensive  | Most expensive
Availability of Learning and Reusable Resources  | Very High  | High | Less  | Less
  
<br />

[go to List of Topics](#top)

<br />
 
### **Famous and Most used versions of python?** <a name="1.8"></a>

There are multiple versions of python since its inception. 
Out of which, versions after ```Python 3.4 ``` are the most widely used ones.

1. 1989, Implementation of Python as a successor of ```ABC Programming Language``` started.
2. 1991, Python 0.9
3. 1994, Python 1.0
4. 2000, Python 2.0 (was popular, but no longer supported since Jan 1, 2020).
5. 2008, Python 3.0 (Famous)
6. 2022, Python 3.10 (Very Very Famous and Huge Developer Community)

* The main difference between version 2 and version 3 is **the stablity of the code has increased a lot** and there were a few changes in the syntax and also increase in **speed of execution of code**. So, Now version 2 has no support or resources so everyone should have latest version in their Local system.
  
 <br />

### **Why should we learn Python?** <a name="1.9"></a>
  
1. By the **start** of 2022 :
**PyPi** (Python Package Index) has > **3,50,000** Python packages (almost all of them are free and open source).
10 million+ (1 crore+) python developers are flourishing all around the world (Huge python developer community).

2. In the mid of 2021 :
**6,200** companies (around the world) have used (90% of their code is written only in) Python for their platforms.
**10,000+** Python job ads on **Glassdoor**.
**14,000+** Python openings on **Indeed**.

3. The number might have **doubled** by now (i.e., June 2022).

4. A Rapid growth is being observed in the world of Python.
Because, Python is **very easy to read, write and understand**.
Learning Python is not as difficult as it looks, but it’s definitely **worth your efforts**.
  
5. In #india, python developers are being paid well... What is the reason?

		4.27 lpa ----> 9.09 lpa ----> 11.5 lpa

6. The following are the average salaries based on different **experience** levels
	*	The average salary of an ***entry-level*** Py developer - ***₹427,293****.
	*	The average salary of a ***mid-level*** Py developer - ***₹909,818***.
	*	The average salary of an ***experienced*** Py developer - ***₹1,150,000***.

7. *The reason is simple and straight forward*. Many of the top companies use python extensively. The following list contains, but not limited to only software companies. In fact, python is being used even by Bio-scientists, Chemical Scientists, etc..

8. Examples of companies that use Python extensively are

> Top Financial Companies
* Goldman Sachs
* JP Morgan Chase
* PayPal

> Large Tech Companies
* Google #google
* Dropbox #dropbox
* Netflix #netflix
* Meta #Meta (Facebook), #instagram
* Uber
* Twilio
* Mozilla
* Reddit
* Increment

> US Government Agencies
* The Consumer Financial Protection Bureau (CFPB)
* NASA
* United States Central Intelligence Agency (CIA)
* Securities and Exchange Commission (US SEC)
* Department of the Navy and National Institute of Standards and Technology (NIST)

> Important Multi National Companies that use python extensively
* Nokia, HPE, Dell, Novell, emc2, vmware, mindtree, OLA, Persistent, GSLabs, Macropace, Xentrix, etc

The list goes on and on... all of them use python extensively.
Python programmers are very high in demand now-a-days..

> One easy way to become rich in the software industry is to learn and perform : **web development using python**.

9. Web Development using Python :
* Python
* Django / Flask
* HTML
* CSS
* JavaScript

The best and most productive field to flourish today is **web development** using python. Which is also popularly known as **Full Stack Python**

<br />

[go to List of Topics](#top)

<br />


## **About Python** <a name="2"></a>

 ### **python scripts and its execution** <a name="2.1"></a>
  
  1. A computer program is a sequence of instructions in a programming language that a computer can execute or interpret.
  2. The basic difference between a **scripting language** and other general purpose programming languages such as C, C++, JAVA is that scripting languages do not need an additional step of compilation and rather they are interpreted, whereas programming languages are compiled and hence need a compilation step to convert the high-level language to machine code.
  3. Scripting Languages are mainly written to automate many tasks with as less code as possible.
  4. Scripting languages support "script," which is small program written for a specific runtime environment. These are interpreted at runtime rather than compiled.
  5. The scripts of python are written in a file and must be saved with an extension .py. Then, at the time of execution, the python interpreter can understand that it is running the python file.
  6. The scripting language refers to dynamic high-level, general-purpose interpreted languages such as Python, Perl, etc.
  7. for executing the python file the command is **python filename.py**
  8. Example - The script present in python file
   ```python
      print("I like learning Python Language")
  ```
  execution of the python file
  <img src="https://github.com/Vissamsetty-Bharathrath/python3_ebook/blob/master/Training/17.jpg" alt="python scripts and its execution" width="600"/>
  
  <br />
  
  ### **Commenting in python** <a name="2.2"></a>
  
  1. **Comments** are text portions that clarify what the program does and how it functions. 
  2. The character used for commenting is ```#```.
  3. The Python interpreter ignores the following text from where the character ```#``` starts.
  4. Example
  ```python
      # print("I like learning Python Language")
  ```
  ```python
  #This is a comment
  #written in
  #more than just one line
  print("Hello, World!")
  ```
  
  ```console
  #output
  Hello, World!
  ```
  
  ```python
  '''
  This is a comment
  written in
  more than just one line
  
  Multiline comment
  '''
  print("Hello, World!")
  ```
 
   ```console
  #output
  Hello, World!
  ```
  
 <br />

### **Print function** <a name="2.3"></a>
  
  1. This is the basic function which is used to print the content on the screen. This function always give a **new line**
  2. Syntax for the **print** function
		> print (objects, sep = ':', end = '\n')
	    * objects can be more than one.
	    * Here, **sep** and **end** are **optional**. **sep** is used to seperate objects and **end** is used to tell what it should do at the end of statement.
3. Examples of the print function are
      ```python
        print("My name is Ramesh", "studying in IIT")
      ```      
   *  From the above print statement "My name is Ramesh" is expression -1 and "studying in IIT" expression -2.
   * Prints the expressions with spaces between them
      ```python
         print("My name is Ramesh", "studying in IIT", sep=':', end=' ')
      ```
  
   *  Prints the expressions with : between them and also new line is avoided from end.
  
4. After executing the two print statement examples the answers are
       <img src="https://github.com/Vissamsetty-Bharathrath/python3_ebook/blob/master/Training/19.jpg" alt="Print function" width="600"/>
  
 <br />
   
 [go to List of Topics](#top)

<br />
   
 ### **Header for Python script** <a name="2.4"></a>
  
  1. The **header** is very important for the program because when anybody wants to understand your program or if you want to revise this program in the future the header will be very helpful to tell how **code works**.
  
```python
#(**/*+-(**/*+-(**/*+-(**/*+-(**/*+-(**/*+-(**/*+-    % PYTHON %    (**/*+-(**/*+-(**/*+-(**/*+-(**/*+-(**/*+-
#
#
#
# Python Training - Chapter - 3 - Exercise 4 - Question -1 
#
# Description:
#  The code takes two integers and do arithmetic operations on the integers.
# 
#
# Usage:
#  python addition.py 
#
#
#(**/*+-(**/*+-(**/*+-(**/*+-(**/*+-(**/*+-(**/*+-    % PYTHON %    (**/*+-(**/*+-(**/*+-(**/*+-(**/*+-(**/*+-

#user input

number1 = int(input("Give first number "))
number2 = int(input("Give second number "))

#arithmetic operations

add = number1 + number2
sub = number1 - number2
multiply = number1 * number2
div = number1 / number2
expo = number1 ** number2

print("The results are")
print("addition ", add)
print("substraction ", sub)
print("multiply ", multiply)
print("division ", div)
print("exponentation ", expo)
``` 

* running script
> PS C:\Users\Documents\Training\code> python operations.py

```console
# output
  
Give first number 12
Give second number 2
  
The results are
addition  14
substraction  10
multiply  24
division  6.0
exponentation  144
```
<br />
   
### **Indentation** <a name="2.5"></a>

  1. **Indentation** plays a very important role in writing **python script**.
  2. The meaning of indentation is the proper **arranging** of the lines of code in the script.
  3. For arranging we can either use **Tab** or **Space**. But the right way is to use Tab which makes our code to write easily.
  4. Now let's understand with an example
  
  ```python
# Convert the command line parameters (arguments) to numbers
num1 = 7
num2 = 10

# Determine which number is largest and perform the subtraction
if num1 > num2:
    diff = num1 - num2
    print(num1, "-", num2, "=", diff)
else:
    diff = num2 - num1
    print(num2, "-", num1, "=", diff)
  ```
  
 * running script
> PS C:\Users\Documents\Training\code> python indentation.py 

```console
# output
  
10 - 7 = 3
```
  
  From the above example, we can see there is a white space after the ```if``` line it is given because the lines should be executed only when the ```If``` condition satisfies. Similarly for the 'else' condition. 
  
<br />
  
 ### **Continuation lines** <a name="2.6"></a>
 
  1. If we are writing one big statement that occupies more than one line then we will be using this character ```\```. 
  2. This character ```\``` should be the end of the line.
  3. For example 
   ```python
     print("My company \
     name is \
     Multiple Wishes.")
   ```
   when we run the script the output is
   <img src="https://github.com/Vissamsetty-Bharathrath/python3_ebook/blob/master/Training/11.jpg" alt="Continuation lines" width="600"/>

<br />   

[go to List of Topics](#top)

<br />

## **Data Types** <a name="3"></a>

1. **Variables** can hold values, and every value has a data-type. 
2. **Data-types** in Python can be either mutable or immutable. 
3. A **mutable** object can be changed after it is created, and an **immutable** object cannot. Objects of built-in types like (int, float, bool, str, tuple, frozenset) are immutable. Objects of built-in types like (list, set, dict) are mutable. Custom classes are generally mutable.

|  Class | Description |Immutable  |
| ------ | ------ | ------ |
| bool |Boolean value  |Yes  |
| int |Integer  |Yes |
|float  |Float point number  |Yes |
| list |Mutable sequence of objects  |No |
|tuple  | Immutable sequence of objects |Yes |
| str |Character string  |Yes
| dict |Associative mapping (dictionary)  |No |
| set |Unique set of values  |No |
| frozenset | Immutable form of set |Yes |

<br />
  
### **Integer data type** <a name="3.1"></a>

1. The **integer** data type has only numbers without decimals in it. The numbers are either positive or negative.
2. Examples:
```python
    No_of_wickets = 5
    overs_bowled = 4
```
<br />

### **Floating-point data type** <a name="3.2"></a>

1. The **floating** point data is the having decimal point after integers.
2.  2. Examples:
```python
strike_rate_of_batsman = 105.45
economy_of_bowler = 6.25
```
3. we can also represent the floating point with  **e** or **E**. **e** **E** means is the power of 10.
```python
strike_rate_of_batsman = 80e5
economy_of_bowler = 24E3
overs_bowled = 4.3
```
  * After we print the above variables the answers are
    <img src="https://github.com/Vissamsetty-Bharathrath/python3_ebook/blob/master/Training/21.jpg" alt="Floating_data_type" width="500"/>
  
<br />

### **Complex data type** <a name="3.3"></a>

  1. The **complex** data type is has an imaginary part in it. The imaginary part is represent with **j**.
  2. Examples
  ```python
  a = 3+7j
  b = 5-9j
  ```
 <br />
 
### **Boolean data type** <a name="3.4"></a>

  1. It has two values **True** and **False**
  2.  Examples
  ```python
  ram_age = 25
  shyam_age = 12
  print(ram_age > shyam_age)
  print(ram_age < shyam_age)
  
  Output
  True
  False
  ```    

<br />

### **Frozen sets** <a name="3.5"></a>
  
1. The method frozenset  in Python takes an iterable object as input and renders it immutable. Simply put, it renders iterable things unchangeable by freezing them.
2. In Python, a frozenset is the same as a set, except that frozensets are immutable, which implies that once generated, elements from the frozenset cannot be added or deleted. 
3. This method accepts any iterable object as input and turns it to an immutable object. The element order is not guaranteed to be kept.
  
 
```python
person = {"name": "Ram", "age": 21, "sex": "male"}

f_Set = frozenset(person)
print('The frozen set', f_Set)
```
  
```console
# output
The frozen set is: frozenset({'name', 'sex', 'age'})
  
```
 use of  dictionary as an iterable for frozen set, the set is created using just the dictionary's keys.
  
 
 ```python
 # converting a list into a frozenset using the frozenset() function.
  
list = ['sai', 'ram', 'shyam']
y = frozenset(list)
print(y)
 ```
  
 ```console
 # output

 frozenset({'sai', 'ram', 'shyam'})
 ```
<br />

### **Conversion of one data type to another** <a name="3.6"></a>

  1. We can **convert** from int to float, int to complex, float to int, float to complex.
  2. We can not convert the complex to int or float data types.
  3. Examples
```python                          
a = 34
b = 36.5 
c = 2 +5j   
                            
m = float(a) #convert from int to float 
n = complex(a) #convert from int to complex 
o = int(b) #convert from float to int:
p = complex(b) #convert from float to complex 

output
34.0
(34+0j)
36
(36.5+0j)
```
                            
<br />
 
 
### **Exercise - 1** <a name="3.7"></a>

  1. Tell the given **type** of the **variable** (single choice)
  
  ```python
name = "Mahesh"
b = type(name)
print(b)
    
  A. int
  B. <class 'int'> 
  C. <class 'str'>
  D. string
  ```
  2. which method is used to find the type of the variable for **a = 20** (single choice)
  
  ```python
  A. print(a)
  B. int(a) 
  C. str(a)
  D. type(a)
  ```
  3. Tell the correct **answers** from the following (multiple choice)
  
  ```python
  A. a = "10"
  B. b = "ram21" 
  C. c = 12
  D. 1_d = 6 
  ```
  4. assign the **value** to the **variable** and print it.(short answer)
 
 ```python
  wonders_of_world = 
  print()
  ```
  5. write a **word** in the for the **variable** and print it (short answer)
  
  ```python
  planet_near_to_sun=
  print()
  ```
  6. Write the **scientific notation** for given float number **0.002569** is (single choice)
  
  ```python
  A. 2569e-5
  B. 2.569e-3
  C. 256.9e-4
  D. 0.2569e-6 
  ```
  <br />
  
  [go to Answers](#answers)

<br />

  [go to List of Topics](#top)
  
  <br />

## **Variables** <a name="4"></a>
  
### **Python Variable** <a name="4.1"></a>

1. **Variable** is a name that is used to refer to a **memory location**. 
2. Variables are also known as **identifiers** and they are used to hold specific values. Variable names can be a group of both the **letters** and **digits**, but they have to begin with a letter or an underscore. 
> we need not mention the datatypes of the variables because python automatically detects the types of the variables, based on the values that you assign to those variables.
3. Variables names are **case sensitive**. For example, there are two variables **amount** and another variable is **Amount**. Both the variables are different, and both of them will be accessed and used seperately.
 
```python
x = 10
_x = 20
```
Here the variable ```x``` and ```_x``` refers to an integer object. Leading Underscore before variable/function/method name indicates to programmer that It is for internal use only, that can be modified whenever class want.

The following are some examples of a few variables 
```console
name = 'Ram'
Weight = 60
height = 80.50
```

We can get the data type of any object by using the ```type()``` function:
For Example : 
```python
## Print the data type of the variable x:

>>> x = 5
>>> print(type(x)) 
<class 'int'>
```
Here the output provided by the interpreter is :  ```<class 'int'>``` because an integer value is assigned to the variable ```x```.

<br />
  
### **Common conventions followed for variable names** <a name="4.2"></a>
  
The following are the two most common types of variable naming conventions followed across the globe
  1. **Snake Case** : This looks like instead of space we use **underscore(_)**. For example is **name_of_the_student**
  2. **Camel Case** : This looks like for each new word it starts with **capital letter**. For example is **NameOfTheStudent**
  
<br />

> **PEP8** is Python's official style guide and it recommends : Function names should be lowercase, with words separated by underscores as necessary to improve readability. i.e., **Snake Case**

### **Creating good names** <a name="4.3"></a>

1. Variable names should be *meaningful*, *self explanatory*, and also they should **represent the purpose for which they are created**.
2. Meaningful variable names can make our **code more readable**, **easier to debug code** and also **maintain it**. 
3. Some scenarios to explain why a proper naming convention is essential for **readability** of the code.
   -  ```n```  -                    We cannot get any information from this variable name ```n```.
   -  ```name```   -                able to understand but what name
   -  ```name_of_the_student```  -  very easy to understand and very appropriate for its purpose of usage.
  
<br />

### **Exercise - 2** <a name="4.4"></a>

  1. Create a variable having the name: ```student_name``` and assign the value ```Ramesh``` to that newly created variable.
  2. Given the problem to substract 5 from 10, using two variables with names: ```number1``` and ```number2``` and store the final result in ```number3```.Print the final output.   
  3. Write a script that defines and uses the following variables for writing a meaningful english line
  ```console
  colour = "blue"
  fruit = "Mango"
  number = 22
  article = "is"
  ```
* use the variables above to print the following statements exactly 
```console
sky is blue, Mango is yellow, age of suresh is 22 .
```  

<br />

[go to Answers](#answers)


<br />

[go to List of Topics](#top)

<br />



## **User input** <a name="5"></a>

  1. They are **two** possibilities in which the user can give inputs to the python programs. They are :
    1. Using ```input()``` function 
    2. Using **command line parameters (arguments)**.

### **input function**  <a name="5.1"></a>
 
  3. The ```input()``` function always takes the input given by user as a string by default. whatever input the user gives will automatically be converted to a string by the ```input()``` function.
  4. The user should perform **type casting** to get back the actual type of the input that he provided to the program.
  
  Examples for **input function** 
  ```python
  name_of_user = input("Name of the user: ")
  print(type(name_of_user))
  print(name_of_user)
  print()

  age_of_user = input("Age of the user: ")
  print(type(age_of_user))
  print(age_of_user)
  print()

  converted_age_of_user_to_integer = int(input("Age of the user: "))
  print(type(converted_age_of_user_to_integer))
  print(converted_age_of_user_to_integer)
  ```
  
  ```console
  output

  Name of the user: Ram
  <class 'str'>
  Ram
  
  Age of the user: 15
  <class 'str'>
  15
  
  Age of the user: 15
  <class 'int'>
  15
  ```
  
  <br />
  
 
### **Command line parameters (arguments)** <a name="5.2"></a>

 1. Command line parameters are also known as *Command line arguments*.
 2. The values or parameters that we would like to give as inputs within the program, are provided directly with the python script execution command, before we even run the program.
 3. A list of strings named ```argv``` is provided inside the code for values.
 4. Each value given in the command is consider as string and also have infinite number of values that are separated with spaces.
 5. To use ```argv``` we should import the module into the script
 ```python
  from sys import argv
  ```
 6. The variable ```argv[n]``` may be used to access each command line parameter in our program.
     - Here n is index of the value.
     - ```argv[0]``` is script name and ```argv[1]```, ```argv[2]```, etc are contains values.
     - Example
      PS C:\Users\Documents\Training\code> python test.py Ram 15 70.45
        1. test.py is ```argv[0]```
        2. They are three command line parameters (arguments)
          - Ram is ```argv[1]```
          - 15 is ```argv[2]``` 
          - 70.45 is ```argv[3]```
    
  Examples for **command line parameters (arguments)**
  Python script
  
  ```python
    from sys import argv
    num1 = argv[1]
    num2 = argv[2]
    num3 = int(argv[3])
    num4 = int(argv[4])
    addition1 = num1 + num2
    addition2 = num3 + num4
    print("The total addition1 result is", addition1)
    print("The total addition2 result is", addition2)
  ```
  running script
    
  > PS C:\Users\Documents\Training\code> python command_line_parameter.py  10 20 30 40
    
  ```console
  # Output
    
  The total addition1 is 1020
  The total addition2 is 70
  ```
  1. From the above script, the following are the few aspects to be remembered :
      * By default ```argv```, consider any input argument that we provide as a string. So, we should explicitly type cast the value that are passed to the program via ```argv```. We need to be clear of the data type that we will be type casting to within the program. So, the values that we send the program as input have to be  apt their to actual datatypes (they should be easily type casted back to their respective types).
     
 <br />
    
 ### **Exercise - 3** <a name="5.3"></a>
 
 1. Write the script asking the user to give two integers and multiply them.
 2. Take the command line parameter any name you want (C:> C:\Users\Documents\Training\code> python command_line_parameter.py Girish and print in the following paragraph.
```python    
Girish is very good boy who helps everyone and also Girish participates in all the sports and cultural meet. Girish hobbies are playing virtual games and also watching movies.
```
 3. Write the script for calculating area of trainagle ( ask user to enter base and height).
 4. Write the script of the student form(name_of_student, class_studying, college_name, city_lives) that accepts as command line parameters and prints as
 ```python
  student_name : Hareesh sai
  class        : 12th
  college_name : SSB
  city_lives   : Hyderabad
 ```
* Here ```student_name``` value has spaces so keep in quotations to print the whole value. 
 
 <br />

[go to Answers](#answers)
 
 <br />
 
 [go to List of Topics](#top)

<br />


## **Operators** <a name="6"></a>

### **Numeric Operators** <a name="6.1"></a>

> +, -, *, **, /, //, %

Examples
```python
  # Addition
  >>> 4 + 7
  11
  # Subtraction
  >>> 8 - 3
  4
  # Multiplication
  >>> 3 * 5
  15
  # Exponent 
  >>> 3 ** 3 
  27
  # Floor division
  >>> 44 // 8
  5
  # Integer division
  >>> 44 / 8
  5.5
  # modulus divison
  >>> 44 % 8
  4
```
  
python script
  
```python
current = 5
resistance = 100
voltage = current * resistance
print("The given current is", current, "and resistance is", resistance, "So the total voltage flows in the circuit is", voltage, "V")
```

```console
# output

  The given current is 5 and resistance is 100 So the total voltage flows in the circuit is 500 V
```
  <br />

### **Assignment Operators** <a name="6.2"></a>

> +=, -=, *=, **=, /=, //=, %= 
  
Examples
``` python
x += y # is same as x = x + y
x -= y # is same as x = x - y
x *= y # is same as x = x * y
x **= y # is same as x = x ** y
x /= y # is same as x = x / y
x //= y # is same as x = x // y
x %= y # is same as x = x % y
``` 

```python
x = 2
y = 3
x += y
print(x)
x = x - y
print(x)
x = x * y
print(x)
x = x ** y
print(x)
x/= y
print(x)
x //= y
print(x)
x %= y
print(x)
```
```console
# output
5
2
6
216
72.0
24.0
0.0
```

 
 <br />


[go to List of Topics](#top)

<br />

### **Comparison Operators** <a name="6.3"></a>

> <, >=, <=, ==, !=, >
               
Examples
```python
  # greater than
  >>> 7 > 4
  True
  # less than
  >>> 7 < 4
  False
  # greater than or equla to 
  >>> 7 >= 7
  True
  # less than
  >>> 7 <= 7
  True
  # equal to
  >>> 7 == 7
  True
  # not equal to
  >>> 7 != 7
  False
```

  <br />

### **Logical Operators** <a name="6.4"></a>
> and, or, not

  1. ```and``` if the both the statements are ```True``` then we get final answer as ```True```.	
  2. ```or``` if any one of the two statements is ```True``` then we get the final answer as ```True```.	
  3. ```not```	it gives inverse of the final answer, when final answer is ```False``` then it gives ```True```. 
 
Examples
```python
 a = 10
 b = 5
 print( a > b and b == 5)
 print( b < a or b == 2)
 print(not( a > b ))
 ```
 ```console
 # output
  
  True
  True
  False
``` 

 <br />
 
  
### **Membership Operators** <a name="6.5"></a> 

> in, not in

  1. ```in``` : if a value is **present** in the given list, ```in``` returns ```True```.
  2. ```not in``` : if a value is **not present** in the given list, ```not in``` returns ```True```.
  
Examples
```python
names = ["Ramesh", "Suresh", "Ganesh"]
print("Ramesh" in names) # in operator
```
```console
# output

True
```
 
```python
names = ["Ramesh", "Suresh", "Ganesh"]
print("Hareesh" in names) # not in operator
```
```console  
# output

True
```

 <br />
  
### **Identity Operators** <a name="6.6"></a> 

 > is, is not
 
  1. ```is``` 	if the objects of both the variables to be same, ```is``` shows the result to be ```True```.
  2. ```is not``` if the objects of both the variables are different, ```is not``` shows the result to be ```True```.
  
Examples
```python
a = ["Suresh", "Ganesh"]
c = a
b = ["Suresh", "Ganesh"]
  
print(a == b) # a is equal to b then returns True
print(a is c) # c is the same object as a it gives True  
print(a is b) # a is not the same object as b, has a same values returns False 
```

```console

# output

True
True
False  
  
```
  
```python
a = ["Suresh", "Ganesh"]
c = a
b = ["Suresh", "Ganesh"]
  
print(a != b) # a is equal to b then returns False.
print(a is not c) # c is the same object as a it gives False. 
print(a is not b) # a is not the same object as b, has a same values returns True. 
```
```console

# output

False
False
True
```
  
<br /> 

[go to List of Topics](#top)

<br />


 ### **Exercise - 4** <a name="6.7"></a> 
  
 1. Tell the answer for given Expression without running it using python interpreter
 ```python
 print(20 / 2)
 
 A. 10.0
 B. 10
 C. 10.00
 ```
 2. Go through the code without running it using python interpreter
 ```python
a = 5
b = 10
if a ** 2 > 50 and b < 50:
    print(a, b)
                            
A. 5 10
B. No Answer                         
C. 25 10                         
```
3. See the expression and give answer without running it using python interpreter
```python
number = (45 - 3 ** 3) / 6
print(number)
                          
A. 4.0
B. 3.0                       
C. 18.0  
```
4. Go through the code and give the all the values without running it using python interpreter
```python
a = 2
b = 10
c = 6
a += b  
b %=c   
print(a, b)
print(c > b)
print(a == (a + b + c) - 20)
d = a < c or a != 12
print(d)
```
5. Go through the code without running it using python interpreter
```python
x = "kumari"
y = "ma"
print(y not in x)
```
 
<br />

[go to Answers](#answers) 
 
<br /> 

[go to List of Topics](#top)

<br />

## **Strings** <a name="7"></a>

1. Strings can be enclosed in **single quotes** or **double quotes**.

> Example :- "Multiple_wishes" 'Multiple_wishes'

2. In the case of string handling, the operator ```+``` is used to concatenate two strings as the operation "Multiple"+" Wishes" returns "Multiple Wishes".

<br />

### **Indexing** <a name="7.1"></a>

1. To retrieve an element of the list, we use the **index** operator ```[ ]``` :

&nbsp;&nbsp;0&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;    2&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;    3&nbsp;&nbsp;&nbsp;&nbsp;    4&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;    5&nbsp;&nbsp;&nbsp;&nbsp;    6&nbsp;&nbsp;&nbsp;&nbsp;    7&nbsp;&nbsp;&nbsp;&nbsp;    - Indexing

&nbsp;&nbsp;↓   &nbsp;&nbsp;&nbsp;&nbsp; ↓&nbsp; &nbsp;&nbsp;&nbsp;   ↓&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;   ↓&nbsp;&nbsp;&nbsp;&nbsp;    ↓&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;    ↓&nbsp;&nbsp;&nbsp;&nbsp;    ↓&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;    ↓

'M',&nbsp;&nbsp; 'U', &nbsp;&nbsp;'L',&nbsp;&nbsp;&nbsp; 'T', &nbsp;&nbsp;'I', &nbsp;&nbsp;'P', &nbsp;&nbsp;'L', &nbsp;&nbsp;&nbsp;'E', 

&nbsp;&nbsp;↑   &nbsp;&nbsp;&nbsp;&nbsp; ↑&nbsp; &nbsp;&nbsp;&nbsp;   ↑&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;   ↑&nbsp;&nbsp;&nbsp;&nbsp;    ↑&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;    ↑&nbsp;&nbsp;&nbsp;&nbsp;    ↑&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;    ↑&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;

&nbsp;-8&nbsp;&nbsp;&nbsp;&nbsp;    -7&nbsp;&nbsp;&nbsp;    -6&nbsp;&nbsp;&nbsp;    -5&nbsp;&nbsp;&nbsp;    -4&nbsp;&nbsp;&nbsp;    -3&nbsp;&nbsp;&nbsp;    -2&nbsp;&nbsp;&nbsp;    -1&nbsp;&nbsp;&nbsp;   -Reverse indexing

Example :-
```python
name = multiple
print(name[3])
```
```console
	
#Output:
t
```
<br />

[go to List of Topics](#top)

<br />

### **Object Identity** <a name="7.2"></a>

1. In Python, every created **object** identifies **uniquely** in Python. 
2. Python provides the guaranteed that **no two objects will have the same identifier**. The built-in **id()** function, is used to identify the object identifier.
3. Example
```python
a = 50  
b = a  
print("Id of a variable is",id(a))  
print("Id of b variable is",id(b))  
# Reassigned variable a  
a = 500  
print("Id of a variable is",id(a))
```

```console
Output:
Id of a variable is 140734982691168
Id of b variable is 140734982691168
Id of a variable is 2822056960944
```
<br />	
	

### **Program using builtin function**: <a name="7.3"></a>

1. The below examples gives the idea of how to **access**, **update**, **format**, **slicing**, **concatenating** and **escape** strings
2. Example -1

```python
str1 = "Multiple_Wishes"
str2 = "Py_wishes"
print("Id number for str1 is ", id(str1), "\n" "Id number for str2 is ", id(str2))
# str1[1] = 'a' # illegal, since strings are (immmutable)
# new string created from old ones
str1 = str1[:1] + 'i' + str1[6:]
print("by indexing and adding i str1 is :", str1, str2)
print("Now str1,str2 id's are: ", id(str1), id(str2))
Name = "Multiple_Wishes"
print("Finding the letter index ", Name.index('e'))
print(Name.index('is'))
print('a' in Name)
print(Name.upper(), Name.lower())
print(Name.replace('p', 'b'))
Symbol = ";"
print(Symbol.join(('Multiple_Wishes', 'Hyd', 'India')))
Name = "Multiple_Wishes"
print("Printing name 3times: ", Name*3, "\n" "Length of name is: ",len(Name))
print(Name[0:10])
Str_name = "hello123"
print("Is Str_name contains numbers: ", Str_name.isalnum(), "\n" "Is string name contains Alphabets: ", Str_name.isalpha())
val = "123"
print(val.isdigit())
Name = "Multiple_Wishes"
print(Name.isalpha())
```
```console

#Output:
Id number for str1 is  1608101425520 
Id number for str2 is  1608101425264
by indexing and adding i str1 is : Mile_Wishes Py_wishes
Now str1,str2 id's are:  1608106224688 1608101425264
Finding the letter index  7
10
False
MULTIPLE_WISHES multiple_wishes
Multible_Wishes
Multiple_Wishes;Hyd;India
Printing name 3times:  Multiple_WishesMultiple_WishesMultiple_Wishes 
Length of name is:  15
Multiple_W
Is Str_name contains numbers:  True 
Is string name contains Alphabets:  False
True
False
```
* Function eval( ) evaluates the passed string as a Python expression and returns the result. For example, eval("1 + 2") interprets and executes the expression "1 + 2" and returns the result (3).

3. Example -2


```python
# Using Backslash to continue statements
a = 2 + \
1.5 * 3
print("a = ", a)
b = eval("5.2") + 3
print("b = ", b)
print(eval("4 < 10"))
print(eval("'Multiple_wishes '  * 5"))
print(eval("abs(-11)"))
print(eval('"Multiple_Wishes".upper()'))
# print(eval('os.getcwd()'))
c = eval("2.3") + 2
print("c = ", c, type(c))
d = "3.2" + "3"
print("d = ", d, type(d))
# use the implicit continuation inside parenthesis
e = ([5, 12, 13, 200])
print("e1 = ", e)
```

```console

#Output:
a =  6.5
b =  8.2
True
Multiple_wishes Multiple_wishes Multiple_wishes Multiple_wishes Multiple_wishes 
11
MULTIPLE_WISHES
c =  4.3 <class 'float'>
d =  3.23 <class 'str'>
e1 =  [5, 12, 13, 200]
```
<br />
  
[go to List of Topics](#top)

<br />

### **Formatting with .format method** <a name="7.4"></a>
   
1. Example:
```python
string_name = "multiple_wishes"
print(f"Name of the string is : {string_name}")
#or
print("Name of the string is : {}".format(string_name))
```
```console
#Output :
Name of the string is : multiple_wishes
Name of the string is : multiple_wishes
```
Here by using .format the string_name is insterted in ```{}```.

<br />
  
## **Important points to remember** <a name="7.5"></a>

1. Python includes methods for converting any value to a string, such as ```repr()``` and ```str()```.
2. The ```str()``` method is intended to yield **human-readable** representations of values, whereas ```repr()``` is intended to provide **interpreter-readable** representations . When providing output for end users, almost always use str.
3. The ```repr()``` function is mostly for **troubleshooting and exploration**. For example, if you think a string has non-printing characters or a float contains a little rounding mistake, ```repr()``` will disclose it but ```str()``` may not.
```python
s="genesis"
"""
   The string 'genesis' has the name s connected to it. When you call str(s), 
   the interpreter replaces s with 'genesis' and then calls str('genesis').
"""
print(str(s))
print(repr(s))
```
 
 ```console
 # output
 
 genesis
'genesis'
```

<br /> 

### **Python has builtin functions, methods & keywords for string. They are used for program:** <a name="7.6"></a>

- [Python Built in Functions](https://github.com/saikrishnavadali05/python3_ebook/blob/36c9f6d569020420975b78432e6f093a21c3829c/Methods&keywords/PYTHON_BUILTIN_FUNCTION.MD)
- [Python String Methods](https://github.com/saikrishnavadali05/python3_ebook/blob/36c9f6d569020420975b78432e6f093a21c3829c/Methods&keywords/STRING_BUILTIN_METHODS.md)
- [Python keywords](https://github.com/saikrishnavadali05/python3_ebook/blob/36c9f6d569020420975b78432e6f093a21c3829c/Methods&keywords/Python%20Keywords.MD)

<br />

[go to List of Topics](#top)

<br />
  
### **Exercise-5** <a name="7.7"></a>

 1. Write a script that can convert the given lower string to upper case string
 ```python
 Example - python   -   output looks PYTHON
 ```
 2. Write a script that can replace the first character in string 
 ```python
 Example - Cython  -   output looks Python
 ```
 3. Write a script that prints the following output( use center method)
 ```python
 #output
 
 ****Python****
 ```
 4. Go through the code and give the answer without running it in the python in interpreter
```python
string = "Hello, emma."
result = string.index("e")
print(result)
```

<br />  

[go to Answers](#answers)
<br />  

[go to List of Topics](#top)

<br />

 ## **Escape sequences** <a name="8"></a>
  
  1.  The character ```\``` represents the beginning of an escape sequence.
  2. Table of escape sequence
  
Sequences | represents 
:----- | :----: 
\b | backspace
\n | newline
\t | tab
\r | return
\a | bell
\\\ | backslash
\\" | double quote
\\' | single quote

3. examples of escape sequences statements

```python
>>> print("He's \"very good\" boy.\n")
He's "very good" boy.

>>> print("He's \"very good\" boy.")
He's "very good" boy.
>>> print("He\tis\tvery\tgood\tboy.")
He      is      very    good    boy.
```
    
<br />


  
### **Exercise - 6** <a name="8.1"></a>
  
  1. Write a script to print the following statements using escape sequences and output should be
```python
#output
Talk is 'cheap'. Show me the code.
I'm not a "great" programmer!I'm just a  good programmer with great habits.
If your ship doesn 't come in, \swim\ out to it?
```
  2. write a script to print the following shape using print statement
  ```python
           * 
       * python * 
     * is  *  a    * 
   * good  * programming * language * 
 * to * learn * for * beginners * 
 ```
 
 <br />

[go to Answers](#answers)
  
  <br />
  
  [go to List of Topics](#top)
  
  <br />
    
## **Answers**

### Exercie - 1 Answers <a name="E-1"></a>

1. C
2. D
3. A, B, C
4. 
```console
#output

wonders_of_world = 7
print(wonders_of_world)
```
5. 
```console
#output

planet_near_to_sun = "Mercury"
print(planet_near_to_sun)
```
6. B

  <br />
  
### Exercie - 2 Answers <a name="E-2"></a>

1. student_name = "Ramesh"
2. 
```console
#output

number1 = 10
number2 = 5
number3 = number1 + number2
print(number3)

```
3. 
colour = "blue"
fruit = "Mango"
number = 22
article = "is"

print("sky", article, colour +",", fruit, article, "yellow, age of suresh",  article, number , ".")

  <br />
  
### Exercie - 3 Answers <a name="E-3"></a>

1. Solution code
```console
number1 = int(input("Enter the first number "))
number2 = int(input("Enter the second number "))

multiplication = number1 * number2
print("The multiplication of two numbers is", multiplication)
```

2. Solution code
```console
from sys import argv

name = argv[1]

print(name, "is very good boy who helps everyone and also",name, "participates in all the sports and cultural meet.", name, "hobbies are playing virtual games and also watching movies.")
```

3. Solution code
```console
base = float(input("Enter the base of the triangle "))
height = float(input("Enter the height of the triangle "))

area_triangle = (base * height) / 2
print("The area of triangle is ", area_triangle)
```

4. Solution code
```console
name = argv[1]
year = argv[2]
name_of_college = argv[3]
lives = argv[4]


print("student_name :", name)
print("class        :", year)
print("college_name :", name_of_college)
print("city_lives   :", lives)
```

 <br />
 
### Exercie - 4 Answers <a name="E-4"></a>

1. A
2. B
3. B
4. 
12 4
True
False
False
5. False

 <br />
 
### Exercie - 5 Answers <a name="E-5"></a>

1. Solution code
```console
string = "python"
print(string.upper())
```

2. Solution code
```console
string = "Cython"

result = string.replace("C", "P", 1)
print(result)
```
3. Solution code
```python
string = "Python"

result = string.center(14,"*")
print(result)
```
4. 1

<br />

### Exercie - 6 Answers <a name="E-6"></a>

1. Solution code
```console
print("Talk is \'cheap\'. Show me the code.")
print("I\'m not a \"great\" programmer!I\'m just a \t good programmer with great habits.")
print("If your ship doesn \'t come in, \\swim\\ out to it?")
```
2. Solution code


