JavaScript Assignment – String Methods()
Part A: Basic Questions
1. # What is a string in JavaScript?
In JavaScript, a string is a primitive data type used to represent and manipulate textual data. It consists of a sequence of characters, which can include letters, numbers, symbols, and even emojis
2. # How do you create a string using double quotes, single quotes, and backticks?
  Using Backticks: Wrap the string in `. You only need to escape the backtick itself if it appears inside the string.
  ~~~js
  alert(`i am anandhu `)
  ~~~
  Using Single or Double Quotes: Wrap the string in ' ' or " ", then use a backslash (\) to "escape" any matching quote character that appears inside the text.
  ~~~js
  alert("i am anandhu"
    alert('i am anandhu')
  )
  ~~~
3. # What is the difference between length and trim()?
In programming, length counts the total number of characters in a string, while trim() removes empty spaces from the beginning and end

4. # What does toUpperCase() do?
The toUpperCase() method converts all the characters in a string to uppercase (capital letters) and returns the result as a new string.
5. # What does toLowerCase() do?
The toLowerCase() method is a built-in function in several programming languages (most commonly JavaScript and Java) that converts all uppercase characters in a string into lowercase.
6. # What is the use of includes()?
The .includes() method in JavaScript checks if a specific value exists within an array or a string, returning true if it is found and false otherwise. It is commonly used for condition checks, search filters, and input validation.
7. # What is the difference between slice() and substring()?

8. # What does replace() do?
9. # What is the purpose of split()?
10. What is the difference between charAt() and bracket notation (str[0])?
11. What does indexOf() return if the value is not found?
12. Explain the use of startsWith() and endsWith().
13. What is the difference between trim(), trimStart(), and trimEnd()?
14. What does repeat() do?
15. # Explain template literals with an example.
Template literals (also known as template strings) are a modern way to handle strings in JavaScript, introduced in ES6. Instead of standard quotes, they use backticks (`) and allow you to embed variables and expressions directly into your text without messy concatenation.
~~~js
const newStr = `My name is ${name} and I am ${age} years old.`;
~~~
Part B: Output Prediction
1.
let str = "JavaScript";

console.log(str.length);
~~~js
output=10
~~~
2.
let str = "hello";

console.log(str.toUpperCase());
~~~js
output="HELLO"
~~~
3.
let str = "WELCOME";

console.log(str.toLowerCase());
~~~js
output = "welcome"
~~~
4.
let str = "Programming";

console.log(str.slice(0, 4));
~~~js
output="prog"
5.
let str = "Frontend";

console.log(str.includes("end"));

~~~js
output = true
~~~
6.
let str = "apple,banana,mango";

console.log(str.split(","));
7.
let str = "JavaScript";

console.log(str.charAt(2));
8.
let str = "I like cats";

console.log(str.replace("cats", "dogs"));
9.
let str = "   Hello World   ";

console.log(str.trim());
~~~js
out="hello world"
~~~
10. let str = "coding";
console.log(str.startsWith("co"));
Part C: Basic Programs
1. # Convert 'javascript' into uppercase.
~~~js
let text ="javascript"
console.log(text.toUpperCase());
~~~
2. # Convert 'HELLO' into lowercase.
~~~js
let text ="HELLO"
console.log(text.toLowerCase());
~~~
3. # Find the length of 'Frontend Development'.
~~~js
let str = "Frontend Development"
console.log(str.length);
//* length =20
~~~

4. # Print the first character of a string.
~~~js
let str = "string"
console.log(str[0]);
~~~

5. # Print the last character of a string.
~~~js

let str = "string"
let len =(str.length)
console.log(str[len-1]);
~~~

6. # Check whether 'Script' exists in 'JavaScript'.
~~~js
let str ="JavaScript"
console.log(str.includes("Script"));
~~~

7. Replace 'good' with 'awesome' in 'This is a good day'.
8. Remove spaces from the beginning and end of a string.
  ~~~js
  let str ="  JavaScript  "
console.log(str.trim())
  ~~~
9. Extract 'Java' from 'JavaScript'.
~~~js
let str ="JavaScript"
console.log(str.slice(0,4))
~~~
10. Convert 'HTML,CSS,JavaScript' into an array using split().
11. Print 'Hi' 5 times using repeat().
12. Check whether a string starts with 'Mr'.
13. Check whether a filename ends with '.pdf'.
14. Capitalize the first letter of 'hello world'.
~~~js
let str='hello world'
let len=(str.length)
let str$first = (str.slice(0,1))
let upper=(str$first.toUpperCase())
let lower=(str.slice(1,len))
console.log(`${upper}${lower}`);
~~~

15. Find the position of 'a' in 'JavaScript'.
~~~js
let str="javaScript"
console.log(str.indexOf("a"));
~~~

