03-JavaScript Assignment – Variables
Section A: Theory & Basics
1. What is a variable in JavaScript?
a : variables are name space in the memeroy location
eg : let a =10

2. What is the difference between declaration, initialization, and re-assignment?
a: declaration - means reserving a space in memeroy
   intitilization - initilazation is very first time a variable given value,while
   reassignment means updatea lready initilized variable with a new value
   ```js
   let a = 10 / initiliazion
       a = 20 / re assignment
    console.log(a) 
    ```
      
3. What are let, var, and const? What is the difference between them?
a : let - this key word used to declare variable
  *can not be redeclared
  *can be reassigned
  ~~~js
  let score=10
      score=20
 console.log(score)  20
 ~~~
 var- variables creating using var key word can be redeclered and res assigned
 ~~~js 
  let a = 10 / initiliazion
  let a = 30  /re declered
      a = 20 / re assignment
 console.log(a)
 ~~~
 const- const are used to manage constant values
*can neither  be redeclarde not be reassigned
  ~~~js
  let a=10
  console.log(a) /10
  ~~~
4. Create a greeting alert. (Hint: use prompt, variable message, and alert.)
~~~js
a : let a= prompt("what is your name")
    alert(a)
~~~
5. What are the naming conventions in javascript

a:
   * variables are case sensitive
   * variable can be single character,multipe character,alphanumeric
   * only two symbols can be use in a variable names, underscore,dollor(a_b,a$b)
   * variable name cannot start with numbers
   * variable cannot have a space
Section B: Practical Problems
6. Create variables for age, city, and isStudent. Print them in one sentence.
   a :
~~~js
let age =21
let city = "kochi"
let isstudent = "anandhu"
console.log(`${age} ${city} ${isstudent} `);
~~~
7. Swap the values of two variables using a temp variable. (Hint: let x = 11, let y = 5, swap the values so that x is 5 and y is 11) 
a :
~~~js  
let x =11
let y =5
let temb = y
 y = x
 x = temb
 console.log(x);
 console.log(y);
 ~~~
 
8 Change a variable from number to string and print both values.
 a :
 ~~~js
let num = 123
let str= String(num)
console.log(str);
console.log(typeof(str));
~~~

9. Combine firstName and lastName using template literals.
a:
~~~js
let firstName = "Anandhu"
let lastName = "Es"
console.log(`${firstName}  ${lastName}`)
~~~
10. Identify valid and invalid variable names.
~~~js
let 1anan= "anandhu"    invalid
let an an = "anandhu"   invalid 
let Ana12 = 10  valid
let An_12 = 10  valid
let An$12 = 10  valid
~~~

