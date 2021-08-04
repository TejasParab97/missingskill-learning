# Javascript

### **(1) JAVASCRIPT HISTORY**

In 1991 linux was launched and tech revolution started. Microsoft and Apple were big players of market. Netscape browser was the only way to use internet, Microsoft build Internet Explorer and provided it for free for users. Java was very strong backend language but it was missing frontend part. To complete that void Netscape programmer named Brandan Eich developed a new programming language in just 10 days. It was originally named Mocha.Later, the marketing team replaced the name with 'LiveScript'. Later due to licensing issue JavaScript name came into existence. Around 95 % websites were created using Javascript. JavaScript has no connectivity with Java programming language.



<br>

<img src="Images and Screenshots/Javascript Images/javascript history.jpg">

<br>
<br>
<br>


### **(2) JAVASCRIPT FRAMEWORKS**

<br>

* There are some popular Frameworks which is collection of Javascript Libraries which provides pre-written code for Developers.

* Some popular frameworks of Javascript:

    (I) Node JS

    (II) Angular JS

    (III) React JS

    (IV)Vue JS

    (V) Ember JS

<br>
<br>

### **(3) CONTROL STRUCTURES & OPERATORS IN PROGRAMMING**

<br>

Control Structures:
- If else : Often used
- for : abstrcations
- switch case : better way available in js
- while : normal use
- do while : normal use

<br>

Operatores:

- Arithmetic Operators

    | Operator | Use | 
    |:---: |:---: |
    | + | Addition |
    | - | Subtraction |
    | * | Multiplication |
    | / | Division |
    | % | Modulus |
    | ++ | Increment |
    | -- | Decrement |

    * When Javascript intoroduced , they assigned (+) sign for concatenation so , In Arithmatic Operators , + is worked as concat as well as addition so you have to use it very carefully.
    * If datatype is number then it works as addition but, when you
    if one value is string and one value is number then, it works as concatenate. Except , + other operators works fine.Let's see one example

    <br>

    <img src="Images and Screenshots/Javascript Images/javascript variables/arithmatic diff between plus and multiply operator.png">

    <br>

    * To avoid this , you can apply just one simple trick:
    just add + sign before string. now, this plus sign work as casting and covert string into number.


    <img src="Images and Screenshots/Javascript Images/javascript variables/use plus sign as casting.png">

    


<br>


- Logical Operators

    | Logical AND | Value |
    |:-----------:|:------: |
    |true && false | false |
    |false && false | false |
    |false && true | false |
    |true && true | true |

    |Logical OR | Value |
    |:----------:|:------:|
   |false && true | true |
   |true && false | true |
    |true && true | true |
  |false && false | false |

  <br>

- Bitwise Operator

  | Operator | Use |
  | :-------:|:---:|
  | &| Bitwise AND|
  | ^ | Bitwise XOR |
  |~| Bitwise NOT |
  | << | Bitwise Leftshift |
  | >> | Bitwise RightShift |
  | >>> |Bitwise Rightshift with zero |


<br>
<br>

### **(4) Tech Debts**

<br>

  * (+) : works as concat & addition

  * (===) : Equality check

  * Type of Null : Object

  <br>
  <br>

### **(5) DATATYPES**

  <br>

 * There are two types of datatypes:

  <br>

(I) Primitive Datatypes (Copy By Value)

| Datatype | Use | 
|:--------:|:---:|
| string | Represents a character |
| Number | Represents numeric values |
| Boolean | Represents True or False |
| Undefined | Represents Undefined value |
| Null | Represents Null |

<br>

<img src="Images and Screenshots/Javascript Images/javascript variables/primitive variables.png">



<br>
<br>

(II) Non-Primitive Datatypes(Copy By Reference)

| Datatype | Use | 
|:--------:|:----:|
| object   | Represents instance through which we can access members|
| Array | Represents group of values |
| RegExp | Represents regular expression |

<br>

<img src="Images and Screenshots/Javascript Images/javascript variables/non-primitive variables.png">

<br>
<br>

* In Javascript , Non-primitive datatypes , all the values are truthy. even empty objects and arrays are also truthy beacuse , they are containers.
But, In Premitive datatypes , there are some exception cases:

   * Number => 0 , NaN(Not a Number) are falsy values.
   * String => "" (Empty string) are falsy values.
   * Undefined are falsy values.
   * NULL is falsy value.

Except these all other primitive values are Truthy.

<img src="Images and Screenshots/Javascript Images/javascript variables/boolean examples.png">


<br>
<br>


* If you add (!) mark in front of variable name , javascript automatically converts variable into boolean value. if you add two (!!) mark then it converts truth value into falsy values & vise versa.

<img src="Images and Screenshots/Javascript Images/javascript variables/var value convert in boolean.png">

<br>
<br>


### **(6) VARIABLES**

<br>

* In Programming , there are two types of variables:

<br>

-  Static Variables
  
   * In Static Variable , once you define variable you must compile it.
   * Java , C++ , Rust , etc. are use static variables.

  <br>

- Dynamic Variables

   * In Dynamic Variable , when you declare variable , compiling is not mandatory. It is evaluated at the runtime.
   * Javascript , Python , Ruby , etc. are use dynamic variables.

   <br>
   


   |  var   |  let   |  const   |
   |:---:|:---:|:---:|
   |can be redeclared|let can be declared|cannot be declared|
   |can be reinitialized|can be reinitialized|cannot be reinitialized but non primitive values can be updated|
   |functional scope|lexical scope|lexical scope|
   |Introduce in ES5|Introduced in ES6|Introduced in ES6|
   |variables get hoisted|variables dosen't get hoisted|variables dosen't get hoisted|

   <br>
   <br>

   ### **(7) PRIMITIVE(COPY BY VALUE) & NON-PRIMITIVE(PASS BY REFERNCE)**

   <br>

* In Primitive variables , they are holding the value. It holds the memory location,where values are stored. 
Primitive variables are using copy by value approach. In simple words, In copy by value , variables are just like xerox machine , when we copy value from passing variable , but it dosen't made changes in passing variable.
    ```javascript
    let name = 'sameer';
    let name2 = name;
    name2 = 'xyz';
    console.log(name, name2);
    ```

   <br>

* In non-primitive variables, they are not copying the value. variables stored values in some memory container and then they passed to another variable by reference.
In Pass by reference approach, variables are works like Debit/credit cards where we can access multiple cards for same account, so account no. is your reference. when we referencing variable then passing variable also change.
    ```javascript
    const person = {
      name: 'John Cena',
      age: 80
    };
      const captain = person;
      person.age = 25;
      console.log(captain, person);
    ```

<br>

<img src="Images and Screenshots/Javascript Images/premitive and non premitive.jpg">

<br>
<br>
<br>

### **(9) ARRAYS AND OBJECTS**

<br>

*  Objects are nothing but , Key-Value pairs. In Javascript, Array is also an Object. Where , Index are keys of array.
* In Javascript , If you add (.) in front of any variable then, variable turned into class same way , if you add dot(.) in front of array then it becomes array class.
* Array and Objects are holds both Primitive as well as Non-Primitive data.
* In Javascript Array , Index works as a key.
* In Object , Keys are always Strings. and key values can be any type of variable.
* There are two ways of creating object:

  * By adding key and key value
  * By using dot notation 

  <br>

  <img src="Images and Screenshots/Javascript Images/javascript variables/create object 2.png">
  <img src="Images and Screenshots/Javascript Images/javascript variables/create object with array.png">


<br>
<br>

### **(10) FUNCTIONAL AND LEXICAL SCOPE**

* By Default , Java starts with Global functional scope.
* In Javascript (ES5) when we use **var** for variable then variable get hoisted but, not assigned value.
* In ES6 , Javascript introduced **let** & **const**. let can be reinitialize but, cannot be redeclared. In const, it has to be initialize as well as declare it because, const cannot be reinitialized neither redeclared.
* Functional Scope:
  * The variables declared inside the function cannot be accessed outside. Functional Scope starts with new function.

  * there are two scopes in functional:
  1. Local Scope:

     - variables declared within the function can only access by function

     - when we add **var** keyword in function then function becomes Local scope so we cannot access the values of outside function.

  2. Global Scope: 
     
     - variables declared outside of the function can access by any function

     - The functions which does not have **var** keyword then , that function has also global scope.

    <br>

    <img src="Images and Screenshots/Javascript Images/program/fuctional scope practicals/global and local scope.png">

    <br>
    <br>


* Lexical Scope:

   * Lexical Scope starts with anything which has a curly braces.
   
      e.g. If{...}Else{...}Function{}

      <br>

      <img src="Images and Screenshots/Javascript Images/program/lexical scope practicals/lexical scope prac 2.png">

  


 











        

