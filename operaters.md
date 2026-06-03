04-JavaScript  Assignment – Operators

Section A – Basic Questions
______________________________
1. What are operators in JavaScript?
ans : javascript operators are
*Arithametic operators
*Assignment operators
*Logical operators
*Comparision operators
2. What is the difference between arithmetic operators and assignment operators?
ans:
Arithametic operators are used to perfoam mathametical operation on the oparend
Assignment operators are used to perfoam assign value of the variable
3. Explain the purpose of comparison operators with examples.
ans:
Comparision oprators are used to comapre two values are return boolean value
~~~js
log a=10
log b=5
console.log(a==b)
///
log a=19
log b="19"
console.log(a===b)
~~~
4. What is the difference between == and === in JavaScript?
ans :
This is a comparision oprater in javascript
The main differnce between equality operator and strict equality operator
equality operator - are checks for values equality only after values ,abstract equality,automatically converts operands
strict equality opraters are checks  both value and types,strict equality,do not coverts

5. What is the difference between != and !==?
ans
!= (in-equality operators)
The inequality operator checks if two values are not equal. If the values being compared are of different types
eg:Returns true if operands are not equal after conversion, and false if they are equal.
!==(strict in-equality operators)
The strict inequality operator checks if two values are not equal without performing any type conversion. 
eg:Returns true if the values have different types OR different values.
6. What are logical operators? Explain &&, ||, and !.
ans:
logical operators used to determine the logic between variables or expressions. While they are often used with boolean values
Logical and(&&)
logical or (||)
logical not(!)
logical and both condision must be true
logical or atleast one condision must be true
logical not (!true=false)(!false=true)
7. What is the purpose of the modulus (%) operator?
ans :
moduls operators involves in arithametic operator is used to find the left over value when the one number is divided by another
8. What is the increment operator? Explain pre-increment and post-increment.

 increment operators are used in progaramming language to increase the value of a variable.
 ~~~js
    log a=0
    console.log(a++) out=1
~~~
pre-incerement The value is incremented first, and then the new value is returned.
eg :
~~~js
let x = 5;
let y = ++x; // x 
console.log(x); // 6
console.log(y); // 6
~~~
post-increment The current value is returned first, and then the variable is incremented
~~~js
let a=10
console.log(a++) //a=10
~~~
9. What is the decrement operator?
 ans :
  decrement operators are used in progaramming language to decrese the value of a variable.
 ~~~js
  log a=11
  console.log(a--)out=10
  ~~~
10. What is operator precedence in JavaScript?
  :operators are higherprecedence are executed before those with lower precedence
   order= (),[*,/],[+,-]
Section B – Output Prediction
------------------------------
11. Predict the output of the following program:
let a = 10;
let b = 3;
console.log(a + b);
console.log(a - b); 
console.log(a * b); 
console.log(a / b); 
console.log(a % b);
~~~js
let a = 10;
let b = 3;
console.log(a + b); //13
console.log(a - b); //10
console.log(a * b); //30
console.log(a / b); //3
console.log(a % b);// 1
~~~
12. Predict the output of the following program:
let x = 5;
console.log(x++); 
console.log(x); 
~~~js
let x = 5;
console.log(x++); // 5
console.log(x); //6
~~~

13. Predict the output of the following program:
let x = 5;
console.log(++x); 
console.log(x); 
~~~js
let x = 5;
console.log(++x); //6
console.log(x); //6
~~~
14. Predict the output of the following program:
console.log(10 == "10");
console.log(10 === "10");
~~~js
console.log(10 == "10"); // true
console.log(10 === "10"); //false
~~~
15. Predict the output of the following program:
console.log(true && false);
console.log(true || false);
console.log(!true);
~~~js
console.log(true && false); //false
console.log(true || false); //true
console.log(!true);//false
~~~
16. Predict the output of the following program:
let a = 8;
a += 2;
a *= 3;
~~~js
let a = 8;
a += 2;
a *= 3;
console.log(a); //309
~~~
17. Predict the output of the following program:
console.log(5 > 3 && 10 < 20);
console.log(5 > 10 || 8 == 8);
~~~js
console.log(5 > 3 && 10 < 20); //true
console.log(5 > 10 || 8 == 8); //true
~~~
18. Predict the output of the following program:
console.log(10 + "5");
console.log("10" - 5);
~~~js
console.log(10 + "5"); // 105
console.log("10" - 5); // 5
~~~

Section C – Write Programs
___________________________
19. Write a program to add two numbers and display the result.
~~~js
let a =20
let b= 30
console.log(a+b);
~~~

20. Write a program to calculate the area of a rectangle using operators.
Hint: a = l * b  Area(a) = Length(l) * Breadth(b)
~~~js
let length =10
let breadth =20
area = length * breadth
console.log(area);
~~~

21. Write a program to swap two numbers using a third variable.
~~~js
let a= 5
let b=6
let temb =b
b=a
a=temb
console.log(a);
console.log(b);
~~~
22. Write a program to swap two numbers without using a third variable..
~~~js
let x = 5;
let y = 6;
[x,y] = [y,x];
console.log(x);
console.log(y);
~~~

23. Write a program to calculate annual interest.
I = (PRT)/100
I = annual interest
P = principal amount
R = rate
T = time period(duration)
~~~js
let P =prompt ("enter principle amount")
let R =prompt (" enter interset rate")
let T =prompt ("enter time duration") 
let calculater = (P*R*T)/100
alert(calculater)
~~~

24. Write a program to convert Celsius to Fahrenheit.

~~~js
let celsius =prompt ("enter temperature in celsius:") 
fahrenheit = (celsius*9/5+32)
alert(fahrenheit)
~~~


25. Create a BMI calculator.
BMI = Weight(kg) / (height(m) * height(m))
~~~js
let weight = Number (prompt("enter weight in kg"))
let height = Number( prompt("enter height in mtr"))
let BMI = weight / (height*height)
alert(`your BMI is: ${BMI}`)
~~~

26. Create a discount percentage calculator.
discountPercentage = ((MRP – sellingPrice) * 100) / MRP

~~~js

let mrp = Number(prompt("enter mrp"))
let sellingPrice = Number(prompt("enter selling price"))
let discountPercentage = ((mrp-sellingPrice)*100)mrp
alert(discountPercentage)
~~~


Section D – Advanced / Conceptual Questions
--------------------------------------------
27. Explain type coercion in JavaScript with examples.
a :In JavaScript, type coercion is the automatic or implicit conversion of a value from one data type to another (such as a string to a number). It happens behind the scenes when you use operators on different data types instead of throwing an error.There are two primary categories of type conversion in JavaScript:Implicit Coercion: Automatically performed by the JavaScript engine.Explicit Conversion: Manually performed by the developer using built-in methods like Number(), String(), or Boolean().
~~~js
string coercion
When a number is added to a string, JavaScript coerces the number into a string and concatenates them
let a = "anandhu"+12
 console.log(a) // anandhu12
Number coercion with arithametic operators
let subtraction = "10" - 2;   // 8 (string "10" becomes number 10)
let multiplication = "5" * "2"; // 10 (both strings become numbers)
let invalid = "hello" * 2;    // NaN (non-numeric string cannot be a number)
~~~
28. Why does "5" + 2 produce a different result from "5" - 2?
a : In JavaScript, the difference in results is due to implicit type coercion—the language's automatic conversion of one data type to another to perform an operation Addition (+) triggers concatenation,Subtraction (-) triggers numeric conversion: "5" + 2 becomes "5" + "2", resulting in the string "52"."5" - 2 converts "5" to the number 5, performing 5 - 2 and resulting in the number 3.
29. What is short-circuit evaluation in logical operators?
ans : Short-circuit evaluation is a programming concept where logical operators (&& or ||) stop evaluating further operands as soon as the outcome of the entire expression is determined. It optimizes performance by skipping unnecessary computations if the first part of a condition already reveals the final true/false result.
*Logical AND (&&): If the first expression is false, the entire expression is false, so the second expression is skipped.
*Logical OR (||): If the first expression is true, the entire expression is true, so the second expression is skipped
  
30. Predict the output of the following program:
console.log(true + true); 
console.log(false + 1);
~~~js
console.log(true + true); // 2 
console.log(false + 1); //1
true value = 1
false value = 0
~~~
31. Explain truthy and falsy values in JavaScript.
```js
Falsy Values
A falsy value is a value that translates to false when evaluated in a boolean context. There are only a few specific falsy values in JavaScript:
eg:false: The keyword itself.
  *"", '', ``: Any empty string.
  * null,undefiend,nan
  
  Falsy Values
  A truthy value is simply any value that is not on the falsy list. When encountered in a boolean context, these are treated as true. 
  eg * Objects and Arrays: Even empty ones like [] and {} are truthy.
     *Non-empty strings: Including "0", "false", or even a string with just a space " "
     *Functions: Any defined function 



