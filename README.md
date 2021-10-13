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







Scala 101 for data science

Spark – big data 

Postgre sql and scala

For Analytic – python and r, scala for scalability

Fuctional computing – compute by evaluating funcions and minimizing the need to maintain state.

Scala can work with jdbc support(relational databases)

Parallel processing – use multiple cores, support for parallel collections and especially important for scaling applications to large data volumes

Apache spartk – big data platform written in scala, supports scala, java, python and R. Distributed cluster processing

You can install scala and configure path to execute in commando scala whenever path you are.

Data Type : 
Byte, Short, Int , Long, Float, Double, Char

Scala command line - REPL

Types of collections :

Seq(Sequences) – Vectors, Streams, Lists, Queues, Strings, Stacks
Sets – HashSet, SortedSet, TreeSet, Bitset, ListSet
Maps – HashMaps, SortedMaps, TreeMaps, ListMpas

Multable collection can change
Immutable cannot change – just simulate creating new one

Array – mutable collection type - 

In commands  -  temps.    -> if temps are array, you can see all temps array methods

Vector are like array , support indexed access to data in a collection. Vectors are inmutables

Range – is a data structure for representing integer values. Start value to end value


Val myRange = 1 to 10  -> imutable collective of 1 to 10

Maps – groups key value pairs - immutable

Val capitals = Map(“Argentina” -> “Buenos Aires”, “Canada”->”Ottawa”, “Egypt”->”Cairo”)

Capitals.keys   ->  list of argentina, Canada
Capitals.values -> list of buenos aires, Ottawa

Maps in java, dictionaries in python and hashes ruby.

Capitals get “Argentina”  ->   buenos aires
When not found is None

Capitals(“Canada”)

Capitals contains “Egypt”  – true

Capitals getOrElse(“china”,”no capital found”)

Capitals + (“ireland”->”dublin”) – show the list with Ireland added

Capitals – “liberia” -> list of all but Liberia was removed

Expression

-	Computable statements
-	Numeric expressions – 
o	Arithmetic expressions  
	2+2
	100-80
	*, / , %
-	Relational expression
o	>, <=, &&, ||, !
-	Assign operator
o	var a = 10
o	c += a
o	*=, 

Put command c -> you can get value in command repl

Braces to multiple expressions - > 
println({
| val a = 2 *3
| a+4
|})



Scala functions 

Def myFunction(a:Int, b:Int) : Int {
| val c = a*b
| return c
| }

myFunction(2,3)

scala classes and objects

val y = Array(“england”, “liberia”)

y.sorted 
sorted version alphabetical order

class Location(var latitude:int, var lat_direction:Char, var longitude:Int, var long_direction:Char, var altitude:Int )

val loc1 = new Location(45,’N’,120,’W’,300)

loc1.altitude

class myPublicPrivate(val x:Int=0, val y:iNT=0, private val z:Int=0)

val myPP = new myPublicPrivate

myPP.      -> show the variable, but z is not showed because is private


parallel processing

parallel collection – multiple core processors
hyper-thread processors

for loop each time – typical – processing time is slow



parallel collection allows us to finish computation faster than sequential collections

scala make easy parallel processing 

parallel collections 

-	ParArrays, ParVector and ParHashMap

Convert sequence collections to parallel collections

val rage100 = 1 to 100
val prng100 = rng100.par


rng100.     – you can see all methods for parallel collection

-	Create parallel collections

import scala.collection.parallel.immutable.parVector

val pvec200 = ParVector.range(0,200)


val  v = (1 to 100).toArray
val pv = v.par

v.map(_ * 2)

pv.map(_ * 2)

parallel is much faster

.map -> functional programming concepts


Def square(x:Int): Int = { return x*x}

Square(4)

v.map(square(_))
pv.map(square(_))


filter collections

val v = (1 to 10000).toArray
val pv = v.par

v.length

val pvf = pv.filter(_ > 5000)

pvf.length

val pvf2 = pv.filterNot(_ > 5000)


def div3(x:Int) : Boolean = { val y:Int = (x % 3); return (y == 0) }

div3(3)


pv.filter(div3(_))

when use parallel collections

- collections with at least 10,000 of elements are good candidates
- for some types of collections, converting between sequential and parallel collections requires copying the content of collection

-	Best to avoid applying procedures with side effects
-	Side effects can lead to nondeterminism
-	Side effects could take affect in a different order each time an operation is executed 

-	In associative operations, the order of operations does not matter

-	If your computation depends on state information about the processing of a collection, and the order of operations matters, then do not use parallel collections


Postgre Sql


Use JDBC  and prepare statement, you can use as string

Scala and spark

-	Data science – functional programming is well suited to applying computations to data also OO language – allows create objects and methods that keep our data organized structure business problems.
-	Parallel collections – when working with large data sets. They allows take advantage of multiple CPUs. Big data – distributed processing framework like Spark

-	Advantage

o	Spark is distrubted processing framework written in scala.  Fast processing, fast tha Hadoop for analytics.
o	Libraries for analytics
o	Stream processing for near real-time analysis, it is fault tolerant(servers can fail an dprocessing can still continue)
o	Scalable – easily add servers to a spark cluster,  specially useful in cloud enviroments, easy to add nodes or servers to a cluster

Spark provides packages for distrubted processing that allow us to do data science over big data-sized data sets. Give the ability to the parallel and distributed processing capabilities of the entire cluster servers

Spark has data structure called resilient distributed datasets(RDDs) 
-	Immutable distributed collection
-	Organized into logical partitions
-	Fault-tolerant collection
-	RDDs may keep data in memory or persisted

Rdds is like parallel collections  
-	Groups of data of the same type or structure
-	Data processed in parallel
-	Fater than working with sequential operations

Rdds differences from parallel collections
-	Rdds are partitioned by a hash function. Parallel collections  are broken into subsets and distributed across cores or threads within a single server at run time
-	Rdds are distributed across multiple servers. Paralle collections work across a single server
-	Rdd data can be easily persisted to permanent storage

Rdd of pairs and four partitions

Partition 1 ,2 ,3 and 4
Pairs of string and integers

Spark REPL 

In spark/bin
Execute command
./spark-shell

Show scala repl

import scala.util.Random

val bigRng = scala.util.Random.shuffle(1 to 100000)

val bigPRng = sc.parallelize(bigRng)    -> convert to Rdd of integers

bigPRng.      -> see what can you do all, statistics(mean, min, max, popStdev(Popularity standard deaviation))


mapping functions

bigPRng.take(25)    ->  first 25 numbers

val bigPRng2 = bigPRng.map(_ * 2)

val republic = sc.textFile(“Users/minku/Downloads/pg1497.txt”)

republic.tak(25).foreach(println)


republic    -> show the info of the value  -> textfiLE


-	Line is anonymous function
val linesWithSocrates = republic.filter(line => line.contain(“Socrates”))   - rdd can create another rdd


Statics over Rdds 

Spark -> big data -> use statitics, 

Descriptive statistics – help us to understand what is the shape of our data. 
Another Branch of statistics -Hypothesys and make predictions. 


import org.apache.spark.mllib.stat.Statistics


we have 1 to 100000 RDD data

sample – subset that’s randomly selection from RDD

val x = bigPRng2.takeSample(true,1000) – random sample

if we start with same number it will be always same values

val x = bigPRng2.takeSample(true,1000, 1234) 

descriptive statistics

bigPRng2.mean.  (min,max,)

bigPRng2.stats.   -> return count, mean, stdev, max, min

-	correlations – 

val series1 = Array.fill(100000)(Random.nextDouble)
val series2 = Array.fill(100000)(Random.nextDouble)

two random series

parallelize the series - rdds

val pseries1 = sc.parallelize(series1)
val pseries2 = sc.parallelize(series2)

val myCorrelation:Double = Statistics.corr(pseries1, pseries2,”pearson”)   -

highly correlated when is > 0 and < 0 is lowly correlated.

Zero is no correlations

Val distTest = Statistics.kolmogorovSmirnovTest(pseries1,”norm”,0,1)

Rdd – distributed data structures – run across multiple nodes
A single-node cluster is useful for development and testing
Big data production enviroments should consider multiple node clusters



Scala and Spark DataFrames

 Dataframes – kind of relational tables, data structure that is organized into rows, and they have named columns

Import org.apache,spark.sql.SparkSession

Val spark = SparkSession.builder().appNmae(“DataFrameExercise”).getOrCreate()

-	create dataframes

employee.txt file contents : 

id,last_name,email,gender,department,start_date,salary,job_title,region_id
1,'Kelley','rkelley0@soundcloud.com','Female','Computers','10/2/2009',67470,'Structural Engineer',2


Val df_emps = spark.read.option(“header”,”true”).csv(“/Users/minku/Downloads/employee.txt”)

De_emps.take(10)

Df_emps.schema

Df_emps.show.   -> more like table like , only show 20, ctrl r to exit

Df.emps.columns. -> to see what columns we have

We can use sql to grouping and filtering operations

Temporary views

Df_emps.createOrReplaceTempView(“employees”).   – create data structure called employees that we can use SQL on that.

Val sqldf_emps = spark.sql(“SELECT * FROM employees”)

Val sqldf_emps_by_dept = spark.sql(“SELECT department, count(*) FROM employees GROUP BY department”)


Sqldf_emps_by_dept.show().   -> to see the sql select 

Joining tables (joining dataframes)

df_emps.show(). - employee
df_cr.show().  – country

val df_joined = df_emps.join(df_cr,”region_id”)

df_joined.show()


-	working with json files to convert to dataframe –

create first spark sessions


val df_json_dd = spark.read.json(“/users/minku/downloads/dept_div.json”)

df_json_dd.show()


data frames is for data scientist to working with spark and scala

data frames are table-like data structures

spark is very easy to load data from CSV, json and other formats

we can use SQL to filter and aggregate data in data frames and support for joins

additional packages(for scala)

saddle for data manipulation
breeze for numeric and scientific processing
Scala-like JDBC for additional support for SQL



