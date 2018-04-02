* **Why did you choose this subject?**
    * _I have heard a lot about python in the last several years. When I have attended meet ups in the past, it has come up in conversation as a desired language._
*  **How were you first made aware of it?** 
    * _In 2016 I did a search for the top programming languages and python came up as one of the top 3_
* **What problem does it solve?**
    * _Simplifies programing. Makes it easy to do complext things in simple programing lines.It has many collections/libraries of preprogrammed code included in the language so it works well with several other languages and allows you to write complicated programs very easily.  There are also several online libraries which help expand its abilities. It is used in Web Dev, Gaming, Desktop GUIs, Scientific Programing, and Network Programming._

* **How does it solve the problem (conceptually)?**
        *_It allows for super simple syntax to be used and things like dynamic variable assignment makes it easy to resuse variable names, make changes faster. Gives programmers access to a large library of preprogrammed capabilities._
* **Why does one use it?**
    *_Because it is an easy language to learn and grasps programing concepts with._
* **What are the alternatives?**
    * _There are several alternatives. Java, JS, Ruby, and many many others_

* **What is it similar to, if anything?**
    *_It is similiar to JS in someways. It is an object oriented language so that may be the similiarities that I see_

* **What is the history of this technology?**
    * _**Who built it and why?** _It was created in 1991 by a Dutch Programmer named Guido van Possum. It was named after a TV show. Many examples included jokes from the show (which I love because it incorporated something he loved). It incorporates aspects of C++, JAVA, PERL, and Lisp. It was originally written in C_
    * **Who is maintaining it?-** _it is still being maintained by the owner. In the last few years a 3rd version of the language has been released which is not completely compatible with previous versions of the software.  The python site says “Firstly, if you are deploying to an environment you don't control, that may require use of a specific version, rather than allowing you a free selection from the available versions. Secondly, if you want to use a specific third party package or utility that doesn't yet have a released version that is compatible with Python 3, and porting that package is a non-trivial task, you may choose to use Python 2 in order to retain access to that package.”_
    
* **What is your opinion on the technology after having built something with it?**
    * _The syntax for python is fun. There are somethings that become much easy to remember the use case of. For example when defining a function we can use "def"_

* **What are the biggest conceptual hurdles (if any) you encountered when researching this?**
    * _There were no real hurddles, there is alot of information on the web about this language and it seems to be a popular language in the DC job market_
* **What resources do you recommend for interested students?** 
    * _The videos below were a good place to start_
* **What article or forum was most helpful to you in learning this?**
    * _There are so many articles that were helpful_
* **What are 3 interview questions one might be asked about this technology?**
    * What are the top three benifits of coding in python? "I've always thought Python was easier to learn, so it's more accessible to most beginning coders. That was actually the thing that convinced me to learn it in the first place. Secondly, it has much better readability than C++ or Java. I also like that when I run into a problem, there is usually more than one tried and true way to resolve it."
    * How do you identify bugs in your code? "I use PyChecker to find bugs in the source code. I prefer it to other programs because it also points out the complexity of the bug."
    * Do you ever multithread? "I usually think multithreading creates more problems than it solves. Sure, it lets the system access more than one thread at a time, but at the cost of memory and CPU. It also makes the code more difficult to debug. I've also experienced deadlocks when I multithread, so I tend to avoid it."


##So....What is it? 
Python is an open source easy to read and powerful language. It is high level language which allows programmers to focus on what to do rather than how to do it. The language is easy to read. Rather than semicolons it uses white space to delaminate code and is written with recognizable words and characters so it is easy to read.  
Set up?
 It does not need to be compiled to run. It does need an interpreter in order to run on any computer.  

### General Notes on Python 

Order of operations matters (PEMDAS) and use parenthesis whenever working with arithmetic use braces. 

nameing convention for a variable has an underscore “

to do a string  is just a single or double quote but if you actually  want the quote to print you  can use “/“

new line is “/n”

** Lists: **
uses [] and each item goes in quotes 
works like an array. Uses: 
- append 
- insert 
- remove
- sort
- reverse 
- del

If you combine lists, the changes you make to the root effect the combined list

** Tupples: ** 
Can not be changed after being created unlike a list you can convert from one to the other: 

example:

boat_tuple = (“speed”, “sail”) // this creates the tuple
new_tuple = list(boat_tuple) // this turns it into a list 
new_list = tuple(new_tuple) // this turns it back into a tuple 

** Functions: **
len(example)- returns the length of a tuple 
min(example)- alphabetic or numeric
max(example)- same as above 

** Dictionaries: ** 
These are similiar to lists but can not be joined. (similar to an object in JS) Values with a unique key with a value to each key we are storing: 

Example:  

```
family_nicknames = {
“Sekou”:  “kou”,
“Naseema”: “Seema”,
“Fajr”: “Fudge”
}
```

to call:
  print(family_nicknames[ “Naseema”]) 

functions you can use: 

get (  gets a value for the selected input. syntax is print(family_nicknames.get( “Naseema”))

keys (provides a list of keys syntax is :print(family_nicknames.keys())

values (provides a list of the values:   print(family_nicknames.values())

** Conditionals: **
Main statements used are “if” “else” and “elif” are what we use to define certain conditionals.  so the code will run if the condition is met.  Once a condition is met, nothing else will execute.

The terms of the conditions are: 
- == equal
- != not equal 
- > greater than
- >= breather than or equal to 
- < less then  
- <= less then or equal to 

example: 

age 30 
 ```
if age >= 30 :
	print(“this will be the time of your life”)
else :
	print(“you have some learning to do”)
```
ELIF——> introduces another condition. 

logical operators, 
And, OR, NOT allows for multiple circumstances are met in the if statement 

FOR LOOPs:

FUNCTION:  We use this to re-use and write more readable code. 

use def to define a function. put in name then the perimeter of what you want to use. Remember you have to take scope into account here as well. Make sure you are defining the variable outside of the function if you want to use it elsewhere. 

 Example: 

def  addNumber(firstNum, lastNum):
	sumNum = firtsNum + lastNum
	return sumNum

to call do:
print(addNumber(1,5)

### USER INPUT: 
if we want to grab the data that a user inputs we can use: 

print(“Hello, what is your name”)
name =sys.stdin.readline()
print(“Hello”, name)

### STRING MANIPULATION: 
We can call the last, first, or select parts of the string using : and the integer associated with the part of the string

if we make a string we can call a few things like 

long_string = “this is a test’
print(long_string[0:4]
-catpitilize
-find
-confirm letters (isalph)
-replace words with others 
-confirm number isalnum
-and more
-split


### FILE IO(input/output
we can open a file:
test_file = open(test.txt, wb(command to write)

we can output the mode with 
print(test_file.mode)

test_file.write(bytes(“write me to the file”, UTF-8))

to open for reading and writing: 
test_file = open(“test.txt”, “r+”

object oriented program allows us to define attributes (color hight )using variable  insides of classes and the abilities will be functions. 

The class will be the blueprint for creating what we are working on. examples: 

class Animal:  proceeding with two underscores make it private. use functions that make it available . Self populates first and that is a point of reference referring to itself. 

__name = “” (equivalent to none)
—- height = 0
—-weight 0
—-sound = 0

def set_name(self, name) :
	self._name = name

def get_name(self);
	return self .__name

the youtube page:
https://youtu.be/N4mEzFDjqtA

Dice reference 
https://youtu.be/zlZvRlvHC7I


