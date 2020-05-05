1. In code below "Mark" is a string. What is name?

```js
var name = "Mark";  
```
<!-- 'name' is the name of the variable -->

2. Find the error if any

```js
  var product cost = 3.45;
```
<!-- There should be no space between the variable name and if the variable name is of more than one word, then the first letter of each word (except the first word) should be capital
So, the correct ans will be /var productCost = 3.45/  -->

3. Write `Right or Wrong` next to the code below.

```js
  "Hello World"             right
  'Hello World"             wrong
  "Hello World'             wrong 
  'Hello World'             right
```

## Write `VALID` and `INVALID` infront of the variable name defined below

```js
var man;  VALID
var 1girl; INVALID
var woman3; VALID
var -girl; INVALID
var blackDog; VALID
var 42; INVALID
var $42; VALID
var userName; VALID
var x, y, z; VALID
var x = 5, y = 6, z = 7; VALID
var x = 5 + 10 + 2; VALID
var user = "Tyrion"; "Arya"; "John"; VALID
```

## Basic Operations

Mathematical Operations:

Solve this using mathematical operations. (+, -, \*, / , etc)

```js
var amount = 2080;
// Define a new variable and store the value that is 80 less then the value of amount.
var val1 = amount-80;
alert(val1);

// Define a new variable and store the value that is 200 more then the value of amount.
var val2=amount+200;

// Define a new variable and store the value that is 4 times the value of amount.
var val3= amount*4;

// Define a new variable and store the reminder when the value of amount is  divided by 21.
var val4= amount/4;
```

## var, let and const

Write down the code or if there is any error write down the error.

```js
var user = "Sameer";
// Reassign the value of user to "Sam"
user="Sam";
// Define a variable with name user with value "Irfan"
var user="Irfan";

let number = 21;
// Reassign the value of number to 60
number= 60;
// Define another variable called number with the value of 100
let number = 100;

const username = "Admin";
// Reassign the value of username to "Arya"
let username = "Admin";
// Define a variable called usernae with value "John"
let username= "john";
```

Logical Operation:

Solve this using logical operations. (<, >, &&, ||)

```js
var johnAge = 45;
var markAge = 35;

// Check who is older eithe John or Mark

if(johnAge > markAge)
{
  alert('john is older')
}
else
alert('mark is older')
// Check who is younger
if(johnAge < markAge)
{
  alert('john is younger')
}
else
alert('mark is younger')
// Check if their age is equal
if(johnAge == markAge)
{
  alert('Their ages are equal');
}
// Create a new variable and assign the age of john to new variable.
let john_age = 40;

// Check if john is equal to or greater then mark.
if(john_age >= markAge)
{
  alert('john age is greater or equal to mark age);
}
// Check if john is less then or equal to mark.
if(john_age <= markAge)
{
  alert('john age is less or equal to mark age);
}

// Calculate the average age of john and mark and assign to a new variable.
let avgAge = (john_age + markAge)/2;
alert(avgAge);
```

Output of the following and why :

```js
let charactor = "Arya";
charactor = "John";
console.log(typeof charactor);

string....because typeof charactor i.e. "John" is string
```

Output of the following and why :

```js
let charactor = "Arya";
console.log(typeof charactor);
charactor = 10;

Output:
string
10
output is valid because at first typeof charactor will give type of variable charactor i.e. string
and after that we have reassigned the variable 'charactor' with different data type (number) which is completely fine
```

valid or not (why)

```js
null = 10;
console.log(null);
```
The above code is invalid because we cannot take name of variable as "null" as it means something specific in javascript
