# GROOVY LANGUAGE

#### Collaborators
Tarık Fatih Pınarcı and
Alp Artun Güvendiren

- History of the language: who/when invented it, which languages influenced it, etc. (Tarık Fatih Pınarcı - Alp Artun Güvendiren)
- Why was it invented (Alp Artun Güvendiren)
- When/why shall we use it (Tarık Fatih Pınarcı)
- How to setup an environment to use it in different platforms (Tarık Fatih Pınarcı)
- Example codes (Tarık Fatih Pınarcı)
- Things that are specific to this language? (Alp Artun Güvendiren) 



## HISTORY OF THE LANGUAGE

 Apache Groovy is a Java-syntax-compatible object-oriented programming language for the Java platform. It is both a static and dynamic language with features similar to those of Python, Ruby, and Smalltalk. It can be used as both a programming language and a scripting language for the Java Platform, is compiled to Java virtual machine (JVM) bytecode, and interoperates seamlessly with other Java code and libraries. Groovy uses a curly-bracket syntax similar to Java's. Groovy supports closures, multiline strings, and expressions embedded in strings. Much of Groovy's power lies in its AST transformations, triggered through annotations.

Groovy 1.0 was released on January 2, 2007, and Groovy 2.0 in July, 2012. Since version 2, Groovy can be compiled statically, offering type inference and performance near that of Java. Groovy 2.4 was the last major release under Pivotal Software's sponsorship which ended in March 2015. Groovy has since changed its governance structure to a Project Management Committee in the Apache Software Foundation.

James Strachan first talked about the development of Groovy on his blog in August 2003. In March 2004, Groovy was submitted to the JCP as JSR 241 and accepted by ballot. Several versions were released between 2004 and 2006. After the Java Community Process (JCP) standardization effort began, the version numbering changed, and a version called "1.0" was released on January 2, 2007. After various betas and release candidates numbered 1.1, on December 7, 2007, Groovy 1.1 Final was released and immediately renumbered as Groovy 1.5 to reflect the many changes made.

In 2007, Groovy won the first prize at JAX 2007 innovation award. In 2008, Grails, a Groovy web framework, won the second prize at JAX 2008 innovation award.

In November 2008, SpringSource acquired the Groovy and Grails company (G2One). In August 2009 VMware acquired SpringSource.

In April 2012, after eight years of inactivity, the Spec Lead changed the status of JSR 241 to dormant.

Strachan had left the project silently a year before the Groovy 1.0 release in 2007. In Oct 2016, Strachan stated "I still love groovy (jenkins pipelines are so groovy!), java, go, typescript and kotlin".

On July 2, 2012, Groovy 2.0 was released, which, among other new features, added static compiling and static type checking.

When the Pivotal Software joint venture was spun-off by EMC Corporation (EMC) and VMware in April 2013, Groovy and Grails formed part of its product portfolio. Pivotal ceased sponsoring Groovy and Grails from April 2015. That same month, Groovy changed its governance structure from a Codehaus repository to a Project Management Committee (PMC) in the Apache Software Foundation via its incubator. Groovy graduated from Apache's incubator and became a top-level project in November 2015.

### TO CLARIFY:

- 2003: Developed by Bob McWhirter & James Strachan
- 2004: Commissioned into JSR 241 but it was abandoned
- 2005: Brought back by Jeremy Rayner & Guillaume Laforge
- 2007: Groovy version 1.0
- 2012: Groovy version 2
- 2014: Groovy version 2.3 (official support given for JDK 8)
- 2015: Groovy became a project at the Apache Software Foundation


Influenced by : Java, Python, Ruby, Smalltalk
Influenced : Kotlin



## WHY WAS IT INVENTED ?




## WHY WE SHOULD USE GROOVY ?

Here, are major reasons why you should use Groovy-

-  Groovy is an agile and dynamic language
-  Seamlessly integration with all existing Java objects and libraries
-  Feels easy and natural to Java developers
-  More concise and meaningful code compares to Java
-  You can use it as much or as little as you like with Java apps






Groovy is a pretty interesting programming language for Java developers, as it has become a perfect complement for this general purpose syntax. As a matter of fact, Groovy introduces interesting features to get where Java cannot. 

Apache Groovy is an object-oriented dynamic programming language for Java virtual machine (JVM). What is it usually used for? Groovy is a Java enhancer because it provides greater flexibility and even introduces special features to applications (those that have already been developed can be improved or they can be made from scratch). Groovy is a Java-like syntax, but with the ease of more moldable languages like Python and Ruby. Groovy has several interesting features:

-  Support for static and dynamic typing: statically typed languages are those in which type checking is done at the compiling stage and not during execution. Java is a general purpose statically typed language. Dynamic typing syntaxes such as Groovy are those in which the check is performed during execution. Python is another example. Groovy allows developers to introduce this typing within Java.

- Concise, brief, direct syntax: this allows developers that use Groovy to develop projects faster and easier.   

- Relatively short learning curve: this is a relatively simple language like Python or Ruby. It is easy for developers to learn. 

- Support for unit testing: Groovy is a testing-oriented development language. In fact, it is a syntax that provides support for running tests in integrated development environments (IDEs), Ant or Maven, which are all application programming tools in Java.

- Native support for regular expressions: the Groovy syntax for creating regular expressions is really simple. This programming language has three operators for regular expressions:

-       The operator regex =~.

-       The operator match ==~.

-       The pattern operator ~String.

- Native syntax for lists and associative arrays: in programming, arrays are usually assigned to variables. These variables are often associated to data. Developers sometimes associate that information through various elements of the array through a common thread called index. That way of structuring information with programming is called associative array.

- Native support for markup languages like XML and HTML.

- Support for domain specific languages: a domain specific language is a programming language or a specification dedicated to solving specific problems, through a specific technique. A general purpose syntax such as Java, C or C++ is the opposite. Somehow it provides general structure to solve global situations. 




 ## How to setup an environment to use it in different platforms




## Install Groovy
### 1. Download
In this download area, you will be able to download the distribution (binary and source), the Windows installer and the documentation for Groovy.

For a quick and effortless start on Mac OSX, Linux or Cygwin, you can use SDKMAN! (The Software Development Kit Manager) to download and configure any Groovy version of your choice. Basic instructions can be found below.

#### 1.1. Stable
Download zip: Binary Release | Source Release

Download documentation: JavaDoc and zipped online documentation

Combined binary / source / documentation bundle: Distribution bundle

You can learn more about this version in the release notes or in the changelog.

If you plan on using invokedynamic support, read those notes.

#### 1.2. Snapshots
For those who want to test the very latest versions of Groovy and live on the bleeding edge, you can use our snapshot builds. As soon as a build succeeds on our continuous integration server a snapshot is deployed to Artifactory’s OSS snapshot repository.

#### 1.3. Prerequisites
Groovy 2.5 requires Java 6+ with full support up to Java 8. There are currently some known issues for some aspects when using Java 9 snapshots. The groovy-nio module requires Java 7+. Using Groovy’s invokeDynamic features require Java 7+ but we recommend Java 8.

The Groovy CI server is also useful to look at to confirm supported Java versions for different Groovy releases. The test suite (getting close to 10000 tests) runs for the currently supported streams of Groovy across all the main versions of Java each stream supports.

### 2. Maven Repository
If you wish to embed Groovy in your application, you may just prefer to point to your favourite maven repositories or the JCenter maven repository.

#### 2.1. Stable Release
Gradle	Maven	Explanation
'org.codehaus.groovy:groovy:2.5.9'

<groupId>org.codehaus.groovy</groupId> <artifactId>groovy</artifactId> <version>2.5.9</version>

Just the core of groovy without the modules (see below).

'org.codehaus.groovy:groovy-$module:2.5.9'

<groupId>org.codehaus.groovy</groupId> <artifactId>groovy-$module</artifactId> <version>2.5.9</version>

"$module" stands for the different optional groovy modules "ant", "bsf", "console", "docgenerator", "groovydoc", "groovysh", "jmx", "json", "jsr223", "servlet", "sql", "swing", "test", "testng" and "xml". Example: <artifactId>groovy-sql</artifactId>

'org.codehaus.groovy:groovy-all:2.5.9'

<groupId>org.codehaus.groovy</groupId> <artifactId>groovy-all</artifactId> <version>2.5.9</version>

The core plus all the modules. Optional dependencies are marked as optional. You may need to include some of the optional dependencies to use some features of Groovy, e.g. AntBuilder, GroovyMBeans, etc.

To use the InvokeDynamic version of the jars just append ':indy' for Gradle or <classifier>indy</classifier> for Maven.

### 3. SDKMAN! (The Software Development Kit Manager)
This tool makes installing Groovy on any Bash platform (Mac OSX, Linux, Cygwin, Solaris or FreeBSD) very easy.

Simply open a new terminal and enter:

$ curl -s get.sdkman.io | bash
Follow the instructions on-screen to complete installation.

Open a new terminal or type the command:

$ source "$HOME/.sdkman/bin/sdkman-init.sh"
Then install the latest stable Groovy:

$ sdk install groovy
After installation is complete and you’ve made it your default version, test it with:

$ groovy -version
That’s all there is to it!

### 4. Other ways to get Groovy
#### 4.1. Installation on Mac OS X
##### 4.1.1. MacPorts
If you’re on MacOS and have MacPorts installed, you can run:

sudo port install groovy
##### 4.1.2. Homebrew
If you’re on MacOS and have Homebrew installed, you can run:

brew install groovy
##### 4.2. Installation on Windows
If you’re on Windows, you can also use the NSIS Windows installer.

#### 4.3. Other Distributions
You may download other distributions of Groovy from this site.

#### 4.4. Source Code
If you prefer to live on the bleeding edge, you can also grab the source code from GitHub.

#### 4.5. IDE plugin
If you are an IDE user, you can just grab the latest IDE plugin and follow the plugin installation instructions.

### 5. Install Binary
These instructions describe how to install a binary distribution of Groovy.

First, Download a binary distribution of Groovy and unpack it into some file on your local file system.

Set your GROOVY_HOME environment variable to the directory you unpacked the distribution.

Add GROOVY_HOME/bin to your PATH environment variable.

Set your JAVA_HOME environment variable to point to your JDK. On OS X this is /Library/Java/Home, on other unixes its often /usr/java etc. If you’ve already installed tools like Ant or Maven you’ve probably already done this step.

You should now have Groovy installed properly. You can test this by typing the following in a command shell:

groovysh
Which should create an interactive groovy shell where you can type Groovy statements. Or to run the Swing interactive console type:

groovyConsole
To run a specific Groovy script type:

groovy SomeScript



### Here Is The Instructions For Installing Groovy

- Step 1) Ensure you have Java installed. https://www.guru99.com/install-java.html


- Step 2) Go to http://groovy-lang.org/download.html and click installer.


![](images/img1.png)


Note: You can also install Groovy using the Zip file or as an Eclipse IDE. In this tutorial, we will stick to Windows Installer


- Step 3) Launch the downloaded installer. Select language and click OK.




![](images/img2.png)


- Step 4) Launch. In welcome screen, click NEXT


![](images/img3.png)


- Step 5) Agree with the license terms


![](images/img4.png)


- Step 6) Select components you want to install and click next


![](images/img5.png)


- Step 7) Select Installation Directory and click Next


![](images/img6.png)


- Step 8) Choose Start Menu Folder and Click Next


![](images/img7.png)


- Step 9) Once install is done, let the paths default and click next


![](images/img8.png)


- Step 10) Click Next.


![](images/img9.png)


- Step 11) In start Menu search for Groovy Console


![](images/img10.png)



## EXAMPLE CODES

### Groovy Hello World Example

Consider we want to print a simple string "Hello World" in Java. The code to achieve this would be

```
public class Demo {
    public static void main(String args[]) {
        System.out.println("Hello World");
    }
}
```

The above code is valid in both Java and Groovy as Groovy is a superset of Java. But the advantage with Groovy is that we can do we away with class creation, public method creation, etc and achieve the same output with a single line code as follows:

```
println "Hello World." 

```

There is no need for semicolons

There is no need for parenthesis

System.out.println is reduced to println


### Groovy Variables


In Java, static binding is compulsory. Meaning the type of a variable has to be declared in advance.


```
public class Demo {
    public static void main(String args[]) {
        int x = 104;
        System.out.println(x);
        //x = "Guru99";
    }
}

```
In the above example type of variable (integer) is declared in advance using the keyword "int". If you were to declare a floating point number you use the keyword float.

If you try to assign a String value to an int (uncomment line #5), you will get the following error

```
Demo.java:5: error: incompatible types: String cannot be converted to int
x = "Guru99";

```

In contrast, Groovy supports Dynamic Typing. Variables are defined using the keyword "def," and the type of a variable does not need to be declared in advance. The compiler figures out the variable type at runtime and you can even the variable type.

Consider the following groovy example,

```
def x = 104
println x.getClass()
x = "Guru99"
println x.getClass()

```

Output

```
class java.lang.Integer
class java.lang.String

```
In Groovy, you can create multiline strings. Just ensure that you enclosed the String in triple quotes.

```
def x = """Groovy
at
Guru99"""
println x

```
Output

```
Groovy
at
Guru99

```

Note: You can still variable types like byte, short, int, long, etc with Groovy. But you cannot dynamically change the variable type as you have explicitly declared it.

Consider the following code:

```
int x = 104
println x
x = "Guru99"

```

It gives the following error.


```
104
Caught: org.codehaus.groovy.runtime.typehandling.GroovyCastException: Cannot cast object 'Guru99' with class 'java.lang.String' to class 'int'
org.codehaus.groovy.runtime.typehandling.GroovyCastException: Cannot cast object 'Guru99' with class 'java.lang.String' to class 'int'
    at jdoodle.run(jdoodle.groovy:3)
    at java.base/jdk.internal.reflect.NativeMethodAccessorImpl.invoke0(Native Method)
    at java.base/jdk.internal.reflect.NativeMethodAccessorImpl.invoke(NativeMethodAccessorImpl.java:62)
    at java.base/jdk.internal.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43)
Command exited with non-zero status 1

```


### Groovy-Operators
An operator is a symbol which tells the compiler to do certain mathematical or logical manipulations.

Groovy has the following five types of operators –

- Arithmetic operators: Add (+), Subtract (-), Multiplication (*), Division(/)
- Relational operators: equal to (==), Not equal to (!=), Less than (<) Less than or equal to (<=), Greater than (>), Greater than or equal to (>=)
- Logical operators: And (&&), Or(||), Not(!)
- Bitwise operators: And(&), Or(|), (^), Xor or Exclusive-or operator
- Assignment operators: Negation operator (~)


### Groovy-Loops

In Java, you would define a loop as follows


```
public class Demo {
    public static void main(String args[]) {
        for (int x = 0; x <= 5; x++) {
            System.out.println(x);
        }
    }
}

```

Output

```
0
1
2
3
4
```
You can achieve the same output in Groovy using upto keywords

```
0.upto(4) {println "$it"}

```

You get the same output as above. $it is a closure that gives the value of the current loop.

Consider the following code


```
2.upto(4) {println "$it"}

```

It gives an output

```
2
3
4
```

You can also use the "times" keyword to get the same output


```
5.times{println "$it"}

```

Consider, you want to print 0,2,4,6 with for loop in Java


```
public class Demo {
    public static void main(String args[]) {
        for (int x = 0; x <= 5; x=x+2) {
            System.out.println(x);
        }
    }
}
```

Output:

```
0
2
4
6
```

You can use the step method for the same

```
0.step(7,2){println "$it"}
```

### Declaring Lists/Maps
Groovy is an optionally typed language, you can use the def keyword to declare variables. For example declaring lists or maps is as simple as:

```
def myList = []
def myMap = [:]
```

***********************************************************
### String Interpolation
 Interpolation is the act of replacing a placeholder in the string with its value upon evaluation of the string.

In Groovy, placeholders are surrounded by ${}or prefixed with $ for dotted expressions.

In the previous snippet we can see an example of string interpolation. But here is another one:

```
try{
    throw new Exception()
}catch(Exception e){
    println "Error during operation. Cause: ${e}"
}
```
### Casting
Groovy makes casting very easy and readable with the as operator. To use this operand the casted class must implement the asType()method. This already happens for standard classes like lists, enumerators, etc.

For example:
```
enum Employee {
    MIKE,
    HANNA
}

String name = "JOHN"

try{
    name as Employee
}catch(Exception e){
    println "Could not find employee ${name}. Cause: ${e}"
}
```
### Json to Classes
I work a lot with Web Services with Json responses so inevitably I have had to map responses to Groovy classes. This comes out of the box with Groovy and it's extremely easy, just pass a Json through the class constructor.
```
String response = '{name:"John", position: "Developer", age: 32}'

// Json response to map
def employeeMap = new JsonSlurper().parseText(response)
// Consider an Employee class with the attributes name, position and age
Employee employee = new Employee(employeeMap)
```
That's it. We just built an employee object from a Json string.

The other way around is just as simple:
```
def json = JsonOutput.toJson(employee)
// json == '{name:"John", position: "Developer", age: 32}'
```
### Assertions
Groovy has the same assert statement as Java, but way more powerful - hence it's name - Power Assertions.

The difference being its output in case the assertions resolves to false. For example:
```
def contacts = ['John', 'Anna']

assert contacts.isEmpty()

//Output:
//ERROR org.codehaus.groovy.runtime.powerassert.PowerAssetionError:
//assert contacts.isEmpty()
//       |        |
//       |        false
//       [John, Anna]
```
This allows you to very easily understand what has made the assertion fail.

### Defining variables
Groovy is optionally type, this means that you can define a variable with its type or simply use the keyword def. This applies as well when declaring List or Maps, their types are optional. For example:
```
String name
int age
def address
List friends = ['John', 'Anna']
Map family = ['Mother':'Mary', 'Father':'Joseph']

def getFamilyMember("Mother"){ ... }
```
For those of you who know Javascript, this is similar to the keyword var.

This gives you incredible flexibility, however be cautious when using it. It might make it harder on your team or someone else using your code to read it and understand what is expected as input or output.

### Hashing
If you've ever used Java, you probably know how verbose it is to hash a string - unless you're using a third-party library.

Groovy 2.5 brings us some useful methods to the String class. Calculating hashes is as simple as calling a method on a String. Groovy makes it simple:
```
def password = "thisIsMyPassword"

def md5 = password.md5()
def sha256 = password.sha256()
//For other algorithms use digest() method
def sha1 = password.digest('SHA-1')
...
```
### Operators
Groovy supports the most common operators found in other languages. But that's not enough the are some more interesting operators Groovy provides. Here are a few:

##### Elvis operator
This is a shorter version of the ternary operator. This is very useful, for example, when the condition could evaluate to null.
```
// Instead of this
def user = person.name ? person.name : 'Guest'
// Use this
def user = person.name ?: 'Guest'
```
##### Safe navigation operator
Another operator that can be used to check if a variable is null is the Safe Navigation Operator.
```
def user = person?.name
// user == null
Use this operator when you want to avoid NullPointerExceptions. In case the object you're accessing is null, this operator will return a null instead of throwing a NullPointerException.
```
##### Spread Operator
The spread operator (.*) is used to execute an action on all items of a Collection, instead of using a loop or a closure as we've seen before. For example:
```
def numbers = [1,2,3,4,5,6]
*numbers // == [1,2,3,4,5,6]

def people = [
    new Person(name: 'John', age: '25'),
    new Person(name: 'Anna', age: '21')
]

def friends = people*.name // friends = ['John', 'Anna']
```
### Traits
Traits are a structural construct of the language which allows:

-              composition of behaviors

-              runtime implementation of interfaces

-              behavior overriding

-              compatibility with static type checking/compilation

I like to think of traits as interfaces where you can actually implements methods. It's very useful when you have a very complex and structured application and you want to keep things clean.

It's definetly something I've missed in the early Java.

Here's an example:
```
trait Sociable {
    void greet() { println "Hello!" }
}

class Person implements Sociable {}

Person p = new Person()
p.greet() // Hello!
```
### Regular Expressions
Groovy natively supports regular expressions and it's quite simple. It has 3 operators for regular expressions:

- ~ this is the pattern operator, its the simple way to create an instance of java.util.regex.Pattern:
```
def pattern = ~"^abc{2}\d"
// pattern instanceof Pattern == true
```
- =~ this is the find operator which will look for a pattern in a string and returns a Matcher:
```
def pattern = ~"abc{2}\d"
def found = "abcc5" =~ pattern
// found instanceof Matcher == true
```
- and finally the match operator ==~ which returns true if the string is a strict match of the regex:
```
def found = "abcc5" ==~ pattern
// found == true
```
*******************************





## KEY FEATURES THAT ARE SPECIFIC TO GROOVY
### Advantages and Disadvantages of Groovy
Let’s explore some of the well-known advantages and disadvantages of Groovy.

#### Advantages:
- Dynamic typing (enables you to program faster, at least primarily). 
- Currying/partial software (enabling you to a replica of the function with more than one arguments set). 
- Tooling support to get useful APIs applying @DelegatesTo.  
- Native associative array/key-value mapping support (you are able to generate an associative array literal).  
- String interpolation (better building among strings showing values).  
- Regex’s getting first-class residents.

