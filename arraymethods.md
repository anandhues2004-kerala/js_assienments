07 JavaScript Assignment – String Methods()

Part A: Basic Questions
1. # What does the length property of an array return? 
    The length property of an array returns the total number of elements or items it contains. In languages like JavaScript, it returns an integer that is always one greater than the highest index in the array (because indexing starts at 0).

2. # What is the difference between push() and unshift()? 
    The primary difference between pop() and shift() is the position from which they remove an element: pop() removes the last element, while shift() removes the first element of an array. Both return the removed item

3. # What is the difference between pop() and shift()? 
    The primary difference is the position they target: pop() removes an element from the end of an array, while shift() removes an element from the beginning. 
4. # Which method is used to merge two arrays? 
    Use the concat() method (e.g., arr1.concat(arr2)) or the spread operator (e.g., [...arr1, ...arr2]) to create a new merged array.
   
5. # Which method converts an array into a string? 
   toString(): Converts an array into a single string with elements separated by commas.
6. Which method converts a string into an array? 
7. # What is the purpose of slice()? 
   The purpose of the slice() method is to extract a specific portion of a sequence (such as an array or a string) and return it as a new sequence, without modifying the original
8. # What is the purpose of splice()? 
   The purpose of the splice() method (commonly used in JavaScript) is to modify the contents of an array in place by removing, replacing, or adding elements.
   ```
    The syntax looks like this: array.splice(start, deleteCount, item1, item2, ...)
  ```
9. # Does includes() return true or false? 
     In JavaScript, the .includes() method always returns a boolean value—either true or false

    
10. Which methods modify the original array and which do not?
```js
+---------------------------+-------------------------------+
| MODIFY Original Array     | DO NOT MODIFY Original Array |
+---------------------------+-------------------------------+
| push()                    | map()                        |
| pop()                     | filter()                     |
| shift()                   | slice()                      |
| unshift()                 | concat()                     |
| splice()                  | join()                       |
| sort()                    | includes()                   |
| reverse()                 | indexOf()                    |
| fill()                    | find()                       |
| copyWithin()              | findIndex()                  |
|                           | every()                      |
|                           | some()                       |
|                           | reduce()                     |
|                           | forEach()                    |
+---------------------------+-------------------------------+
````


Part B: Predict the Output

11.let arr = [10,20,30];
console.log(arr.length);
```js
output = 3
```


12.let arr1 = ["A","B"];
      let arr2 = ["C","D"];

console.log(arr1.concat(arr2));
```js
 [ 'A', 'B', 'C', 'D' ]
```


13.let colors = ["Red","Blue"];

colors.push("Green");

console.log(colors);
```js
["red","Blue","Green"]
```
14.let fruits = ["Apple","Orange","Mango"];

fruits.pop();

console.log(fruits);
```js
[ 'Apple', 'Orange' ]
```

15.let nums = [1,2,3,4];

nums.shift();

console.log(nums);
```js
[ 2, 3, 4 ]

```


16.let arr = ["JavaScript","Python"];

arr.unshift("Java");

console.log(arr);
```js
[ 'Java', 'JavaScript', 'Python' ]
```


      
17.let animals = ["cat","dog","lion"];

console.log(animals.includes("dog"));
```js
true
```


18.let nums = [10,20,30,40,50];

console.log(nums.slice(1,4));
```js
[ 20, 30, 40 ]
```


19.let arr = [1,2,3,4,5];

arr.splice(2,2);

console.log(arr);
```js
[ 1, 2, 5 ]
```


20.let names = ["John","Alex","Sam"];

console.log(names.toString());
```js
John,Alex,Sam
```

21.let text = "HTML,CSS,JS";

console.log(text.split(","));

Part C:
 # Find the Error


23.let fruits = ["Apple","Orange"];

fruits.pop("Mango");

console.log(fruits);
```js
let fruits = ["Apple","Orange"];
fruits.pop();
console.log(fruits);
in pop method does not argument requried

```

24.let arr = [1,2,3];

console.log(arr.include(2));
~~~js
let arr = [1,2,3];

console.log(arr.includes(2));
javascript not conatin include() method
~~~


25.let text = "Hello World";
console.log(text.splite(" "));


26.let arr = [10,20,30];
console.log(arr.lenght);
~~~js
let arr = [10,20,30];
console.log(arr.length);
error is length spelling not correct
~~~

# Part D: Simple Programming Problems
27. # Create an array containing 5 student names and print its length. 
```js
let arr=["sanju","dube","noor","karthik","Bravies"]
console.log(arr);
console.log(arr.length);
```
28. # Create two arrays of numbers and merge them using concat(). 
```js
let arr1=["sanju","dube","noor","karthik","Bravies"]
let arr2 =["10","20","30","40","50"]
     arr1.concat(arr2)
     console.log( arr1.concat(arr2));
```
29. # Create an array of colors and add three new colors using push(). 
 ```js
 let arrColors = ["red","orange","blue"]
arrColors.push("yellow","black","pink")
console.log(arrColors);
```
30. # Create an array of fruits and remove the last element using pop(). 
 ```js
 let arrFurits=["apple","orange","guva","grapes","pomgranate"]
arrFurits.pop()
console.log(arrFurits);
```
31.  # Create an array of cities and remove the first city using shift(). 
```js
  let arrCities = ["kochi","trivandram","kozhikode",]
arrCities.shift()
console.log(arrCities);
```
32. # Create an array of numbers and insert 100 at the beginning using unshift(). 
 ```js
 let arrNumbers = [1,2,3,4,5,6,7,8]
arrNumbers.unshift(100)
console.log(arrNumbers);
```
33. # Check whether "Mango" exists in an array using includes(). 
```js
let arrFruits =["mango","apple","orange","grapes"]
console.log(arrFruits.includes("mango"));
```
34. # Create an array of 10 numbers and extract elements from index 2 to 6 using slice(). 
```js
let arrNumbers =[1,2,3,4,5,6,7,8,9,0]
console.log(arrNumbers.slice(2,6));
```

35. # Create an array ["A","B","C","D","E"] and remove "C" using splice(). 
```js
let arrString = ["A","B","C","D","E"]
arrString.splice(2,1)
console.log(arrString);
```
36. # Insert "Orange" and "Banana" at index 2 using splice(). 
```js
let arrFruits = ["apple","Grapes","mango"]
arrFruits.splice(2,0,"Orange","Banana")
console.log(arrFruits);
```
37. # Convert ["HTML","CSS","JavaScript"] into a string using toString(). 
```js
let arrProgramming=  ["HTML","CSS","JavaScript"]
console.log(arrProgramming.toString());
```
38.Convert the string "red,blue,green,yellow" into an array using split(). 
~~~js
let str = "red,blue,green,yellow" 
console.log(str.split("  "));
~~~
39.Replace all elements in [1,2,3,4,5] with 0 using fill(). 
```js
let arr =[1,2,3,4,5]
console.log(arr.fill(0));
```

40.Create an array of 5 subjects and replace the last 2 subjects with "JavaScript" using fill().
```js
let arr =["java","c++","python","react","php"]
console.log(arr.fill("javascript",3,5));
```









