
1. # Check if a number is positive or negative
Concept: if
Problem:
Write a program to check if a number is positive.
Example:
Input: 5 → Output: "Positive"

~~~js
let num = Number(prompt("enter a number"))
if(num>0)
{alert("positive")}
else
{alert("negative")}
~~~

________________________________________
2. # Check if a number is even or odd
Concept: if-else
~~~js
let num = Number(prompt("enter a number"))
if (num%2===0)
{alert("number is even")}
else
{alert("number is odd")}
~~~
________________________________________
3. # Check if a person is eligible to vote
Concept: if-else
Age ≥ 18 → “Eligible” otherwise “Not eligible”.

~~~js
let age = Number(prompt("enter your age"))
if(age>=18)
{alert(" Eligible for vote")}
else
{alert("Not eligible for vote")}
~~~
________________________________________
4. # Find the largest of two numbers
Concept: if-else
~~~js
let num1 = Number(prompt("enter a number"))
let num2 = Number(prompt("enter a number "))
if(num1>num2)
{alert(`"Largest number is:" ${num1}`)}
else
{alert(`"Largest number is:" ${num2}`)}
~~~
________________________________________
5. # Find the largest of three numbers
Concept: if-else if-else
~~~js
let num1 = Number(prompt("enter first  number"))
let num2 = Number(prompt("enter second number "))
let num3 =Number(prompt("enter third number "))
if(num1>=num2 && num1>=num3)
{alert(`Largest number is: ${num1}`)}
else if(num2>=num1 && num2>=num3)
{alert(`Largest number is ${num2}`)}
else
{alert(`Largest number is ${num3}`)}a
~~~
________________________________________
6. # Check if a character is a vowel or consonant
Concept: if-else if-else
~~~js
let character = prompt("enter a charater")
if(character === 'a' || character==='e' || character ==="i" || character === "o" || character === "u")
{alert("character is vowels")}
else
{alert("charater is consonant ")}

~~~
________________________________________
7. # Grade the student based on marks
Concept: if-else if-else
Example:
90–100 → A
80–89 → B
70–79 → C
else → Fail

~~~js
let mark = prompt("Enter your mark")
if(mark>100)
{alert("Enter a valid mark")}
else if(mark>=90)
{alert("Your garde is A")}
else if (mark>=80)
{alert("Your garde is B")}
else if (mark >=70)
{alert("Your grade is C")}
else
{alert("Your failed")}
~~~
________________________________________
8. # Check if a number is divisible by both 3 and 5
Concept: logical AND (&&)
~~~js
let num = Number(prompt("enter a number"))
if( num%3===0 && num%5===0)
{alert("The number is divisilbe")}
else
    {alert("The number is not divisilbe")}
~~~
________________________________________
9. Check if a number is in a range (10 to 50)
Concept: logical AND (&&)
~~~js
let num =Number(prompt("enter a number"))
if((num>=10) && (num<=50))
{alert("Number is included")}
else
{alert("Number is not included")}
~~~

________________________________________
10. # Check if a year is a leap year
Concept: combined conditions (&&, ||)
~~~js
let year=Number(prompt("enter a year"))
if((year % 4 === 0 && year % 100 !== 0) || (year % 400 === 0))
{alert("leap year")} 
else
{alert("not leap year")}
~~~
________________________________________
11. # Display day name based on day number
Concept: switch
1 → Monday
2 → Tuesday …
7 → Sunday
~~~js
let day =(prompt("enter a day number"))
let days=["1","2","3","4","5","6","7"]
switch(day){
    case "1":
        {alert("monday")}
        break
    case "2":
        {alert("Tuesday")}
        break
    case "3":
        {alert("wednesday")} 
        break
    case "4":
        {alert("Thursday")}
        break
    case "5":
        {alert("Friday")} 
        break
    case "6":
        {alert("Saturday")}
        break
    case "7":
        {alert("sunday")}  
        break
        default :
        {alert("try another")} 
}
~~~
________________________________________
 12. # Basic Calculator (Add, Subtract, Multiply, Divide)
Concept: switch
Inputs: number1, number2, operator (+, -, *, /)
~~~js
    let num1=Number(prompt("enter the first number"))
       let num2=Number(prompt("enter the second number"))
       let operator=prompt("enter the operator")
       let operators = ["+","-","*","/"]
       switch(operator)
       {
        case "+":
            {alert(num1+num2)}
            break
        case "-" :
            {alert(num1-num2)}
            break
        case "*":
            {alert(num1*num2)}
            break
        case "/":
            {alert(num1/num2)}  
            break
        default :
        {alert("Enter a valid operator")}          

       }
~~~

________________________________________
13. # Check if a number is zero, positive, or negative
Concept: if-else if-else
~~~js
if (a>0)
{alert("Number is positive")}
else if(a<0)
{alert("Number is negative")}
else
{alert("Number is zero")}
*/
________________________________________
14. # Check if a student passed or failed marks ≥ 40 → Pass
Else → Fail

~~~js

let mark=Number(prompt("Enter the mark"))
if(mark>=100){alert("Enter valid mark")}
else if(mark>=40){alert("student passed")}
else{alert("Your faild")}  
~~~
________________________________________
 15. # Check if the person has a fever (normal temperature: 98.6F)
 ~~~js
 let temp = Number(prompt("enter the temperature"))
if(temp>98.6)
{alert(" person has a fever")}
else
{alert("person has no fever")}
~~~
________________________________________
16. Check if someone has normal temperature: Normal temp= (98 to 98.9)
98.1 => normal
99 => not normal
97.9 => not normal
~~~js
let temp = Number(prompt("enter the temperature"))
if (temp>=98&&temp<=98.9)
{alert("Normal")}
else
{alert("Not Normal")}
~~~
________________________________________
17. # You need to have 75% attendance to write the exam. Take the total number of classes and the number of attendances from the student and tell him if he can write the exam

~~~JS
let total$class = Number(prompt("Enter the total classes"))
let attented$class = Number(prompt("Enter the attented classes"))
let percentage =((attented$class/total$class)*100)
if(percentage>=75)
{alert(`Attentence percentage is ${percentage} your eligible for attent the exam`)}
else
{alert(`Attentence percentage is ${percentage} your not eligible for the exam`)}
~~~
________________________________________
 18. If(5>4){
Console.log(“First if”)
}
If(10 >= 6){
Console.log(“Second if”)
}
What will the output of the above code be?
ans
    FIRST IF
    SECOND IF
________________________________________
 19. If(true){
Console.log(“1”)
}
If(false){
Console.log(“2”)
}
If(true){
Console.log(“3”)
   }
What will the output of the above code be?

ans:
The output of that code will be:1 & 3 First block: Since the condition is true, it runs and logs 1.Second block: Since the condition is false, it is skipped entirely.Third block: Since the condition is true, it runs and logs 3.
________________________________________
20. # What will be the output of the below code?
 
________________________________________
 21. # Write a chained if / else-if statement to fill in the following conditions
val  < 5  =>  Tiny
val  < 10  =>  Small
val  < 15  =>  Medium
val  < 20  => Large
val  >= 20  => Huge 
~~~js
let value =Number(prompt("enter the value"))
if(value< 5)
{alert("Tiny")}
else if(value<10)
{alert("Small")}
else if(value<15)
{alert("Medium")}
else if(value<20)
{alert("Large")}
else
{alert("Huge")}
~~~

________________________________________
22. # Use the switch case and create an application with the following roles.
admin => gets full access
subAdmin => gets access to create and delete courses
testPrep => gets access to create and delete tests
user => gets access to consume contents

~~~js
let role=prompt("enter your roles")
let roles =["admin","subadmin","testprep","user"]
switch(role)
{
    case "admin":
        {alert("gets full access")}
        break
    case "subadmin":
        {alert("gets access to create and delete courses")}   
        break 
    case "testprep":
        {alert(" gets access to create and delete tests")}    
        break
    case "user" :
        {alert("gets access to consume contents")} 
        break  
    default :
    {alert(" Not Valid")}   
}
~~~
l
________________________________________
23. #  Guess the output
let a = 5, b = 10;
if (a > b && b > 0) {
    console.log("X");
} else {
    console.log("Y");
}
out put = y
________________________________________
24. # Guess the output
let day = 3;
switch(day) {
    case 1: console.log("Mon"); break;
    case 2: console.log("Tue"); break;
    case 3: console.log("Wed"); break;
    default: console.log("Invalid");
}

out put = wed
________________________________________
25. Create a simple ATM withdrawal checker
Conditions:
Balance should be greater than withdrawal amount
AND amount should be a multiple of 100
~~~js
let amount =Number(prompt("enter the amount"))
let balance= 5000
let Remaning_bal = balance -amount
if(amount<=balance&&amount%100===0)
{alert(`Withdrawel successfull Remaning balance ${Remaning_bal}`)}
else if(amount>=balance)
{alert("insuffient balance")}
else
{alert("Transation faild amount must be a mutiple of 100")}
~~~

















