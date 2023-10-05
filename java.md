# Java


* Java is not just a language, but a whole ecosystem, millions of ready-made modules that you can use in your program. 
* Thousands of online communities and message boards where you can get help or advice.




#### Identifier
---

* A name in java program is called identifier. 
* It may be class name, method name, variable name and label name

<br>

#### Reserver Words
---
* In java some identifiers are reserved to associate some functionality or meaning such type of __reserved__  __identifiers__ are called reserved words.
* Reserved words  = Reserved Literal (3) + Keywords (50) = 53 
* data types + flow control + modifiers + exception handling + Class related + Object related
> Reserved Literal -- true, false, null

>Keywords -- class, interface, if, else, int , float, public, throws, catch
<br>


#### Data Type
---
* Data types specify the different sizes and values that can be stored in the variable.
* Java language is considered as strongly typed programming language
* There are two types of data types in Java: 
    * Primitive -- int, byte, short, long, double, float, boolean, char
    * Non Primitive  -- class, arrays, interfaces etc 

<br>

#### Literals
---
* Any constant value which can be assigned to the variable is called literal.

<br>

#### Array
---

* An array is an indexed collection of fixed number of homogeneous data elements.
* The main advantage of arrays is we can represent multiple values with the same name so that readability of the code will be improved.
* The main disadvantage of arrays is: Fixed in size that is once we created an array there is no chance of increasing or decreasing
  the size based on our requirement that is to use arrays concept compulsory we should know the size in advance which may not possible always. 

> __We can resolve this problem by using collections.__

> Every array in java is an object hence we can create by using new operator.

<br>



#### Variable
---

##### Types of Variables
* Based on the type of value represented by a variable all variables are divided into 2 types.
    1. Primitive variables
    2. Reference variables

 > Primitive variables:
  <br>
  Primitive variables can be used to represent primitive values.

 > Reference variables:
    <br>
    Reference variables can be used to refer objects. 


* Based on the behaviour and position of declaration all variables are divided into the following 3 types.
    1. Instance variables
    2. Static variables
    3. Local variables

    <br>
    <br>

    > Instance variables: 
    * Instance variables will be stored on the __HEAP__ memory as the part of object.
    * Instance variables can be accessed directly from Instance area. But cannot be     accessed directly from static area.
    * For the instance variables it is not required to perform initialization, JVM will always provide default values.

    <br>
    <br>

    > Static variables:
    * If the value of a variable is not varied from object to object such type of variables is not recommended to declare as instance variables.
    * We have to declare such type of variables at __class level__ by using __static__ modifier.
    * Static variables will be created at the time of class loading and destroyed at the time of class unloading hence the scope of the 
      static variable is exactly same as the scope of the .class file.
    * Static variables will be stored in __Method area__
    * Static variables can be accessed from both instance and static areas __directly__.
    * Static variables also known as class level variables or fields.

    ```
    java Hello
        1. Start JVM.
        2. Create and start Main Thread by JVM.
        3. Locate(find) Hello.class by main Thread.
        4. Load Hello.class by main Thread. // static variable creation
        5. Execution of main() method.
        6. Unload Hello.class // static variable destruction
        7. Terminate main Thread.
        8. Shutdown JVM
    ```
    > Hello is a class


    <br>
    <br>

    > Local variables:
    * Some times to meet temporary requirements of the programmer we can declare variables inside a method or block or constructors such
      type of variables are called local variables or automatic variables or temporary variables or stack variables.
    * Local variables will be stored inside __Stack Memory__.
    * The local variables will be created as part of the block execution in which it is declared and destroyed once that block execution completes.
    * For the local variables JVM won't provide any default values,  __compulsory__ we should perform initialization explicitly before using that variable.


<br>


#### Var-Arg Methods
---






---


<br>

