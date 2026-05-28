1. # Convert an array of names into uppercase using map().
 ```js
 */
let arr = ["anandhu","abhinav","elbin"]
let upper=arr.map(item=>
    item.toUpperCase()
)
console.log(upper);
```
2. # Filter numbers greater than 50.
```js
let arr =[10,40,50,80,60]
let result =arr.filter((item=>{
    return item>=50
}))
console.log(result);
```

3. Find the largest number using reduce().
```js
let arr =[1,2,3,4,5,]
let largest = arr.reduce((acc,cur)=>{
    return acc>cur ? acc:cur
})
console.log(largest);
```
4. Find the first word starting with "A".find()
```js
let arr=["Anandhu","Abinav","elbin"]
let result = arr.find((item)=>{
 return item.startsWith("a".toUpperCase())
})
console.log(result);
```
5. Check whether any number is negative.some()
```js
let arr =[1,2,3,4,5,-1]
let result = arr.some((item)=>{
    return item<1
})
console.log(result);
```

6. Check whether every number is even.every()
```js
let arr =[1,2,3,4,5,]
let result = arr.every((item)=>{
    return item%2===0
})
console.log(result);
```