## Abcd of JavaScript | Everything you need to know before starting with JS!

#### Hello, my name is Vivek Chudasama, and I wrote this post about JS Basic Intro and History in my own words. So, I hope you enjoyed reading it.
--------------------------------------------------------------------------------------------------------------

# Intro to Javascript

Javascript is a high-level, multi-paradigm object-oriented scripting language. It is the world's most well-known and widely used programming language, earning it the moniker "Web programming language." It is used to program website functionality.

--------------------------------------------------------------------------------------------------------------

# A brief history of Javascript

> - In 1995, Brendan Eich wrote the first version of Javascript, dubbed "Mocha," in just ten days.
- To attract Java developers, "Mocha" was renamed LiveScript, then Javascript in 1996. Javascript, on the other hand, has nothing to do with Java.
- When Microsoft introduced Internet Explorer, it included Netscape's Javascript and renamed it JScript.
- To standardize the language, ECMA published ECMAScript 1 (ES1), the first official JavaScript standard.
- ES5 was introduced with many exciting new features.
- ES6 was released: the most significant update to the language yet!
- ECMAScript switched to a yearly release cycle to ship fewer feature features every version.

--------------------------------------------------------------------------------------------------------------

# How to link Javascript to HTML?

> *   Go to your test site and create a Javascript file and name it script.js (or anything you want to) and save it.
*   In your index.html file, enter this code on a new line, just before the closing tag:

```
    <script src="script.js"></script>
```
--------------------------------------------------------------------------------------------------------------

# First Javascript program

> *   Open the `script.js` file and type this line of code and save it.
*   Open the test site and open the console (Ctrl + Shift + J or left click on the webpage and click on inspect, then open console.)
*   Now, you can see the output there! Yay!!!
```
console.log("Hello World!");
```    
 
--------------------------------------------------------------------------------------------------------------

# Variables and Values
>*   The container for storing data is called a variable.
*   The data stored in the variable is called a value.
    
--------------------------------------------------------------------------------------------------------------

# Declaring variables

> As Javascript has dynamic typing, we do not have to manually define the data type of the value stored in the variable.

**Syntax for declaration:**
```
var variableName = value;
let variableName = value;
const variableName = value;
```
## **Things to keep in mind while naming a variable**

> * Only use alphanumerics, $, and \_ for variable names.
* Never begin the name with a number and capital alphabet.
* Never use keywords like Name, Let, Switch, etc.
* As Javascript is case sensitive, do remember that variable names `pen`, `pEN`, and `pEn` would be considered different variables.
    

## **There are three ways to declare variables**

> *   **Var:** It is used for all types of variables but is outdated.
```
    var firstName = "Vivek";
```

> *   **Let:** It is preferred over `var` for declaring variables. Let allows us change the value stored in it.
```
    let firstName = "Vivek";
    firstName = "Chudasama";
```

> *   **Const:** It is used to store values that can't be changed. Const doesn't allow us to change the value stored in it.
```
    const PI = 3.14 ;
    PI = aaplePI;  // This gives an error
```    
--------------------------------------------------------------------------------------------------------------

# Datatypes

> There are two types of datatypes :
1.  Primitive
2.  Non-Primitive
    

> ## 1. Primitive Datatypes

>There are 7 primitive data types:
1.  **Number**: Floating point numbers.
 ```
let myNum = 3;
```
2.  **String**: Collection of characters.
```
let myName = "Vivek";
```    
3.  **Boolean**: Logical type that can be only true or false.
```    
let myBool = true;
```   
4.  **Undefined**: Value has been taken by a variable that isn't defined.
```
let x;
```
5.  **Null**: The empty value.
6.  **Symbol**: Value that is unique and cannot be changed.
7.  **BigInt**: Larger integers than the Number type can hold.
    
> ## 2. Non-Primitive Datatypes
1.  **Object**: It contains various key: value pairs.
```
    const human = {
      firstName: "ABC";
      Lastname: "XYZ";
      age: x;
    }
```
**Template literals**
```
    let firstName = "Vivek";
    let lastName = "Chudasama";
    let age = "23";
```    
## **To check the datatype of a variable, you can use `typeof` like given below**
> ```
      let code = 2678;
      console.log(typeof num); // This would show "Number" in console
    ```    

**We all know the concatenation technique**
>```
          console.log("My name is + " " + firstName + " " + lastName and I'm + " " + age + years old.");
          // My name is Vivek Chudasama and I'm 23 years old.
  ```
> Template literals involve the use of `` `...` `` instead of `"..."` and `${variable-name}` is used instead on inserting empty quotation marks and + sign and makes code clean.
```
    console.log("My name is ${firstName} ${lastName} and I'm ${age} years old.");
    // My name is Vivek Chudasama and I'm 23 years old.
```
--------------------------------------------------------------------------------------------------------------

# Conditionals
> In JavaScript we have the following conditional statements:
*   **if** to specify a block of code to be executed if a specified condition is true.
*   **else** to specify a block of code to be executed if the given condition is false.
*   **else if** to specify a new condition to test if the first condition is false.
```
let x = 5;    
    if(x == 3) {
      console.log("Three");
    } else if (x == 4) {
      console.log("Four");
    } else if (x == 5) {
      console.log("Five");
    } else {
      console.log("Not three, four or five");
    }
```

## Switch Statement
>*   Switch statement is used to check various conditions. It is like a long ladder of if and else if except the actual usage.
*   `break` is mandatory after each case. If the break is not used, the next block of code for the next case will be executed automatically.
**Syntax**
```
switch (expression) {
    case (expression output): 
      // Code
      break;
case (expression output):
      // Code
      break;
case (expression output): 
      // Code
      break;
    default: 
      // Code
    }
```
