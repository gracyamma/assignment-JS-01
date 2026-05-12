# Section A:Theory&Basics

## Q1.What is the variables in javascript?
ANS:in javascript, a variable is a contaniner that stores data.

## Q2.What is thr difrrence between declaration initialization,and reassignment?

| Action         | Meaning                         |
| -------------- | ------------------------------- |
| Declaration    | Creating the empty box          |
| Initialization | Putting the first item inside   |
| Reassignment   | Replacing the item with another |

## Q3. What is let,var,const,?what is diffrence between them?

ANS:1.let:let is a keyword used to declare variable

2:var:variables created using var keyword can be readed aswell as reassigned

3:const:const is uded to declare a variables whose value should not be reassigned

## Q4.Create a greeting alert.(hint:use prompt,variable meaasge and alert)
ANS: let name = prompt("Enter your name");

let message = "Hello, " + name + "! Welcome!";

alert(message);
## Q5.What are the namimg converstaion in javascript?
ANS
### Cammel case

First word starts lowercase, next words start with capital letters.

### Pascalcase

First word starts with capital letterts.

### UPPER_SNAKE_CASE

ANS:All capital letters with underscores.

### Snske case 

ANS:words seprated by underscores

# Section B:Practical problems

## Q6 . Create variables for age, city, and isStudent. Print them in one sentence.

ANS:let age = 20;

let city = "Kochi";

let isStudent = true;

console.log(
  "I am " + age + " years old, I live in " + city + ", and student status is " + isStudent + ".")

  output:I am 20 years old, I live in Kochi, and student status is true.

  ## Q.7 Swap th value of two variables using temp variable.(Hint: let x = 11, let y = 5, swap the values so that x is 5 and y is 11) 

  ANS:let x = 11;

let y = 5;

let temp = x; // store x value in temp

x = y;        // assign y value to x

y = temp;     // assign temp value to y

console.log("x =", x);

console.log("y =", y);
 
 output

 x=5
 y=11

 ## Q8.Change a variable from nuber to string and print both values?

ANS:let value = 100;          

let stringValue = String(value);   

console.log(value); 
      
console.log(stringValue);

output

100:
"100"

## Q9.Compaine first Name and last Name template?

ANS:let let firstName = "John";

let lastName = "Doe";


let fullName = `${firstName} ${lastName}`;

console.log(fullName);

output john Doe

## Q.10.Identify vaild invalid variable names.
IN VALID

ANS:let 1name;         starts with number

let user-name;     hyphen not allowed

let user name;     space not allowed

let @price;        special character not allowed

VALID

let name;

let userName;

let _age;

let $price;

let user1;





