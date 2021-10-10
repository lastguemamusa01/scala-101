# scala-101
scala 101 practices

scala means scalable language

scala palys a key role in the play fromework (apache spark in kafka)

easy integration and scalability in java

functional programming - natual fit for big data, simplicity

object oriented desing with functional programming, 

scala has functions and methods with the same syntax
methods are part of a class
a function is an object and can be assigned to a variable

every data in scala is object

inteoperabity with java, scala classes can call java methods and the can inherent from java classes

run on JVM

2001 start, martin ordersky released scala 2004

scala can be used IDE or scala build tools(SBT) - netbeans, eclipse and intellij

scala can be run in a REPL(Read-Eval-Print-Loop) session, this provides instant feedback on syntax

Intellij IDEA

both - fuctional and object oriented programming languages

the interpreter can run small code snippets

is statically typed allowing us to find errors at compile time

it is a pure object- oriented language with no primitive data types

it supports higher-order functions, nested functions and currying

scala has a lightweight syntax for anonymous functions(lambda functions)

generic classes, variance annotations, upper and lower type bounds

inner classes and abstract types as object memeber
compund types, explicitly typed self-references, implicit parameters and conversions
polymorphic methods

scala is easyly integrated with java

all java.lang classes are automatically imported by default. other classes can be explicitly imported

scala can call any java code, subclass an existing java class, and implement any java interface

a java code can call into scala code if the scala code subclasses a java class or implements a java interface

scala and java has interoperability

scala coding takes a minimalist approach

scala coding can be done using the console or IDE

java installed is requiered

is a strong statically typed general-purpose programming language which supports both object-oriented programming and functional programming.

scala syntax - grammar

scala semicolon is optional in the end, scala uses the endline symbol to know when a statement is done.

var is mutable variable and val is inmutable variables

Unit type is like void in java

can infer datatype - > var sum = 10+25.   -> automatically data type of int

semicolons are not mandatory 

scala worksheets

code and test - automatically invokes the scala interpreter and is going to provide realtime feedback
as we type in statments inside of our worksheet on the right hand side it prints out the output
every time we save it, it will automatically compile, call the interpreter to make sure enverything is good
show the result in the right , great for begineers
worksheet are same as REPL sessions
great for testing your code

REPL session

in command ->
scala    - to enter scala

:help  - to see all commands

object HelloWorld {
  | def main(args:Array[String]) {
  | println("hellow world")
  |}
  |}
  
-> you define the object hellow world result

HelloWord.main(null)   - to call the object you have created

val str = "Scala is the best!"

- string created

var x = 'a'
var y = true
3+5.   - get result

def add(a:Int, b:Int)Int
add(34,90).   -> to call methods

:quit.   - to get exit


or in you project folder of scala
input scala in terminal

:load variable.sc     - you can execute worksheet.  , if there is error it will show it


Type inference

is where the compiler determines the data type based on usage

Any have AnyVal and AnyRef

AnyRef - Object, Seq, List and String
AnyVal - Double, float, int, short, byte, chart , unit , boolean
Nothing

if your declaration of variable have value this will don the type inference

![image](https://user-images.githubusercontent.com/25869911/136673191-5562420d-44f1-432c-aba9-305ae16a08fc.png)

 type inference is only applied to your local variables - inside your object or definitions
 not applicable to recursive functions
 

Scala Variables

- variables are named memory locations 
- memori is reserved to hold the value of the variable
- each variable type is given a specfic amount of memory
- variables a re defined with keywords val and var
- a variable can be declared with or without a data type
- the compiler will infer the data type if it is omitted. if you ommited the data type, you must initialize that value when you declare it.
- variables names start with lowercase letters
- it is recommended to avoid an underscore in any names - it also is used as a wildcard symbol in scala
- all variable data types are classes 
- fields are variables that belong to objects
- method aparameters are used to pass variables from the calling program to the method
- local variable only access inside the method


Loop

do while, while, for, for comprehension( using yield , or list or vector, tuple)


Functions

- scala has functions and methods with the same syntax
- method are part of a class
- a function is an object and can be assigned to a variable
- anonymous functions are called lambda functions
- unit functions do not have an equal sign. (java is void functions)

- you can use recursive functions also 

Hige order functions

- function that that other function as parameter or they return a function
- a first-order function takes only data items

- closure function - is where a function whose return value depends on the value of a variable declared outside of that function
- give us the ability encapsulate algorithm inside of the function

Scala Operators

- scala has arithmetic, relational , logical , bitwise , and assignment operators
- Arithmetic operators : +. -. *. / , %
- relational operators : ==, != , >, <. >=. <=
- logical operators: &&, ||, !
- bitwise operators : &, | , ^, ~, <<, >>
- assigment operators: =, +=, -=, *=, /=, %=
- scala dont have ++, -- insted use  +=, -=
- scala math library has abs, sqrt, min,etc.
- cons operator -> val numbers = 1::2::3::4::Nil    - put values to create a list


Decision Statements in scala (If)

How to read from the console

- use Scala.ioStdIn. library
- readBoolean() , readByte, readChar, etc readLine


read from File in Scala

you can use tro or catch to handle errors

pattern matching - compare value or expression, process case statements - like switch statement in java


scala support collections

- set - iterable with not duplicable elements
- map - storing key-value pairs
- tuple - pairs are the smallest case of tuples. are useful when the function return more than one value with defferent data types
- in tuple, you can use zip method to create pairs
- array - must be fixed size, array buffer like vector or arraylist in java for not fixed size
- list - process same as array, element of the list cannot be changed using an assignment 

Classes, fields and methods

- when we create class - automatically create constructor, getters and setter of field declared.


- special type of class named singleton object - used to enforce a single instance of a class, static keyword in java static class
- singleton is defined as object, not a class. singlton object only have one instance

 - case class - are defined by adding the case keyword before the class keyword









