# section A:Basic Questions

## Q1.What are the data type in javasript?
ANS:primitive  data type &imprimitive data type

## Q2.List primitive data type in jvascript?
1.srtring

2.Nan

3.Nul

4.boolean

5.Biginit

6.Undefined

## Q3.what is the diffrence between primitive and imprimitive data type?
 ANS:


 | Primitive                    | Non-Primitive                  |
| ---------------------------- | ------------------------------ |
| Stores single value          | Stores multiple/complex values |
| Immutable                    | Mutable                        |
| Compared by value            | Compared by reference          |
| Stored directly              | Stored as memory reference     |
| Examples: `number`, `string` | Examples: `object`, `array`    |

## Q4.What is the`typeof operator? Give examples.

ANS:it is used to check the data type of varriable or value

Example:console.log(typeof 100);

output:number

console.log(type of "string")

output: string

console.log(type of true);

output:boolean

## Q5.What is the undefined data type?

ANS:that means a variable has been declared but has not been assigned a value.

## Q6.What is the  null in javascript?

Ans:null in JavaScript is a special value that represents an intentional empty value or no value.

## Q7.What is the difference between null and undefined?
ANS:

| `null`                  | `undefined`                          |
| ----------------------- | ------------------------------------ |
| Intentional empty value | Variable has no value assigned       |
| Assigned by programmer  | Assigned automatically by JavaScript |
| Type is `"object"`      | Type is `"undefined"`                |
| Means “nothing”         | Means “not defined yet”              |

## Q8.What is the boolean data type?give examples?
ANS: A bolean data type is represent only two value true&false

Example: let isLoggedIn = true;

let hasPermission = false;

## Q9.What is a string in java script?

ANS:in javascript a string is a data type used to represent text 

How to write a string

Single quotes ' '

Double quotes " "

Backticks ` ` (template literals)

## Q10.What is number  data type?? Does JavaScript support integers and floats separately?
ANS:in javascript the number  data type is used to represent all numeric values,
 javaScript does not support integers and floats as separate data types.
 It uses a single data type called Number for both.

# Section B Conceptual Questions

## Q11.What is symbol data type in javascript?
ANS:in javascript the symbol data  typeis a primitive data type create unique identifiers.

## Q12.What is bigint and why is it used

ANS:it is represent very large integres that are bigger than the safe limit of number.

## Q13.What happens when you use data type of null?

 ANS:In JavaScript, null is a special primitive value that represents the intentional absence of any object value. When you check its type using typeof null, it returns object, which is actually a well-known bug in JavaScript that has existed since its early development and was never fixed due to compatibility reasons. Even though it shows objectullis not truly an object—it is used to explicitly indicate that a variable has been assigned an empty or “no value” state on purpose. This is different from undefined, which means a variable has been declared but has not yet been assigned any value.

 ## Q14.Explain type  coercion with  examples.?

 ANS:in javscript is automatic conversion of one data type into another data type when performing operation between data type

 Example:

console.log(5+"12") -string coercion(num-string)

output 512

Numeric Coercion (String → Number)

console.log("10" - 2);

console.log("10" * 2);

console.log("10" / 2);

output

8
20
5

Boolean coercion

console.log(Boolean(0));

console.log(Boolean(1));

console.log(Boolean("hello"));

console.log(Boolean(""));

ouput

false

true

true

false

## 15.What is implicit and explicit type conversion?

ANS:In JavaScript, type conversion refers to changing a value from one data type to another, and it occurs in two ways: implicit and explicit conversion. Implicit type conversion (also called type coercion) happens automatically when JavaScript itself converts data types during operations, such as converting a number to a string in expressions like 5  5 which results in ". On the other hand, explicit type conversion is done manually by the programmer using built-in functions like Number() String() and Boolean(), for exampleNumber("10") converts the string 10` into the number10. The main difference is that implicit conversion is handled by JavaScript without developer control, while explicit conversion is intentionally performed by the developer to ensure the correct data type is used.

## Q16.What is `NaN`? When does it occur?

ANS:NaN in JavaScript stands for “Not a Number”. It is a special value that represents an invalid or undefined numeric result. Even though its name says “Not a Number,” it is actually of the Number data type.

NaN occurs when JavaScript tries to perform a mathematical operation that cannot produce a valid number. For example, dividing a number by a non-numeric string like "hello", or performing arithmetic with undefined or invalid values will result in NaN.

# Section Practical/coding

## Q17.Write a program to check the data type of a variable

ANS:let value = 42;

console.log(typeof value);

output 

number

## 18.Declare a variables of  all primitive data type and  print their type.

ANS:// String

let name = "Alice";


// Number

let age = 25;


// Boolean

let isStudent = true;


// Undefined

let x;


// Null

let y = null;


// BigInt

let bigNumber = 123456789012345678901234567890n;


// Symbol

let id = Symbol("id");


// Printing data types
console.log(typeof name);       // string

console.log(typeof age);        // number

console.log(typeof isStudent);  // boolean


console.log(typeof x);          // undefined

console.log(typeof y);          // object (JavaScript bug)

console.log(typeof bigNumber);   // bigint

console.log(typeof id);         // symbolL

## Q.19.Writte a program conert string to number.

ANS:let num = 100;

let str = String(num);


console.log(str);

console.log(typeof str);

## Q20.Write a program to convert a number to a string.

let num = 150;

// convert number to string

let str = String(num);


console.log(str);

console.log(typeof str);

## Q21. What will be the output of:
console.log(typeof 42);

console.log(typeof "Hello");

console.log(typeof true);

console.log(typeof undefined);

console.log(typeof null);

ANS:number

string

boolean

undefined

object

## Q22.predict the output?

console.log(5 + "5");

console.log("5" - 2);

console.log(true + 1);

console.log(false + "hello");

output

55

3

2

"falsehello"

## Q23.create a  an object and  array then check their data type using typeof

ANS:object 

let student = {

  name: "John",

  age: 20,

  course: "Computer Science"

};

console.log(student);

output

{name'john',age:20,course:'computer science'}

array

let cars =["benz""bmw""polo"]

console.log(cars);

output

['benz','bmw','polo',]

# section D Advaced thinking

## Q24.Can a variable change its data type ?Explain with exaples?

yes, in javascript a variable can change it data type

Eamples

let x=10;
console.lpg(type of x)

let x="10"
console.lg(typeof x)

here changed number; to "string"

## Q25.How does javascript handle large integres?

ANS:JavaScript handles large integers using two main numeric types: Number and BigInt.





