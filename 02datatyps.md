02-JavaScript Assignment – Data Types
Section A: Basic Questions
1. What are data types in JavaScript?
a:  java script contain two type of datatype
  * primitive data type 
  * non primitive data type

   primitive data types
   *sring
   *Number
   *boolen
   *undefiend
   *null
   *nan
   *symbol
   *bigint

   nonprimitive data type
   *array
   *object

2. List all primitive data types in JavaScript.
   a: primitive data types are inbuild datatype in javascript
     primitive data types
   *sring
   *Number
   *boolen
   *undefiend
   *null
   *nan
   *symbol
   *bigint
     

3. What is the difference between primitive and non-primitive data types?
  a:  primitive data types are inbuild datatype in javascript
      non-primitive data types are derived from primitivedatatype
4. What is the `typeof` operator? Give examples.
   a: the typeof operator returns the type of a variable or an experssion
5. What is the `undefined` data type?
   a : undefiend is a primitive datatype that represent value not assigned

6. What is `null` in JavaScript?
 a: null is a primitive data type that represend intentional absence of value
7. What is the difference between `null` and `undefined`?
 a : The primary deffrence between null and undefiend in java script is intent . undefiend means value not assigned at yet. null is repersent variable empty or has no value
8. What is the `boolean` data type? Give examples.
  a : boolean is a primitive data type that represent two values
      true  and false
      boolean are mainly used condisional statement like if and loop like while 
9. What is a `string` in JavaScript?
a : string is a primitive data type that represent textual data
   eg:"hello"
10. What is a `number` data type? Does JavaScript support integers and floats separately?
 a : Number is primitive data type used to represent both whole number(integer,floating-point)

Section B: Conceptual Questions

11. What is the `symbol` data type in JavaScript?
a : A symbol is primitive data type in java script that represent a unique and immutable identifier. its primary purpose is to serve as a property key object that will be never clash with other keys
12. What is `bigint` and why is it used?
a :Bigint is a javascript data type for handling and storing big integr values.bigint allows you to work with integer larger than the limit of numbers
13. What happens when you use `typeof null`?
a :when you use type of null in javascript the result is string "object"
14. Explain type coercion with examples.
  a : Type coercion in javascript is automatic or implict coverction of value from one data type to another to make an operation possible
15. What is implicit and explicit type conversion?
a :implict convertion (coercion) when java script automatically converts a value type to match the requirements of an operation
explictconvertion(casting) when a developer manually changes a value type using built-in java script function.
16. What is `NaN`? When does it occur?
a :NaN stands for Not-a-Number.it is a special numeric value used to reperent an undefiend or unrepresentable result from a mathamatical operation

Section C: Practical / Coding Questions

17. Write a program to check the data type of a variable.
a : let num ="107"
console.log(typeof(num));
18. Declare variables of all primitive data types and print their types.
a : 
```js
//  string
 ```js
  let text ="hello" ;
  console.log("type of text:",typeof text) 
  ```
  
  
  ```js
//   number
  let count =100;
  console.log("type of count:";typeof count)
  ```

 ```js
//   boolean

  let isTure = true;
  console.log("type of istrue:",typeof is true)
  ```


  ```js

//   null

   let emptyvalue = null;
  console.log("type of emptyvalue:",typeof emptyvalue) -->
  ```
  
```js
//   undefied
     let notassigend = ;
  console.log("type of notassigend:",typeof notassigend) 

  ```
  
19. Write a program to convert a string to a number.
a :
```js
let num ="107"
num=Number(num)
console.log(Number("107"));
20. Write a program to convert a number to a string.
 let num =107
num=String(num);
console.log(num)
console.log(typeof num)
```

21. What will be the output of:
```js
console.log(typeof 42);
a : number
console.log(typeof "Hello");
a : string
console.log(typeof true);
a : boolean
console.log(typeof undefined);
a : undefiend
console.log(typeof null);
a :object
22. Predict the output:
console.log(5 + "5");
 a: 55
console.log("5" - 2);
a : 3
console.log(true + 1);
a: 2

console.log(false + "hello");
a:falsehello
```

23. Create an object and an array, then check their data types using `typeof`.
```js
let obj ={};
let arr =[];
console.log(type of obj);
console.log(type of arr)
```
Section D: Advanced Thinking
24. Can a variable change its data type? Explain with example.
   a: yes javascript is dynamically typed,so a variable can hold differnt types at deffernt types at differnet times
   ```js
   //examples
   let x =10;
   console.log(typeof x);  number
    let x ="10";
   console.log(typeof x);  string
    let x = true;
   console.log(typeof x);  boolean
   ```
25. How does JavaScript handle large integers?
a : for every large integer situation js  used in bigint

  //examples
  ```js
  let big = 90000500077n;
  let bigger =big + 10n;
  console.log(bigger):   90000500087
  ```

