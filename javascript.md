# javascript questions
[comment]: <> (This is a comment, it will not be included)

| NAME | E-MAIL | 
|------|-------|
|RAVI KUMAR DHAWAN|ravidhawan8899@gmail.com|
---

## Theory
---
01. Question : What is JavaScript? 
>> **JavaScript** is a *scripting* and *object oriented* programming language used both on the *client-side* and *server-side* that allows you to make web pages interactive. And JavaScript gives web pages interactive elements that engage a user.


02. Question : What is the difference between b/w let and var?
>>**var** is used to declare a variable globly  and **let** is used to declare a variable localy(  block-scoped).


03. Question : Why do we prefer const over var?
>> Here both have distinct advanages,If we do not want to change the value of the variable ,we will use *const*.And if we want to change the value of our variable we will use *var*.
 **const** variables can neither be updated nor re-declared. And **var**  is used to declare a variable globly  and **var** variables can be updated and re-declared within its scope.
04. Question : What is the use of javascript in web browsers?
>> JavaScript is a programming language used primarily by Web browsers to create a dynamic and interactive experience for the user.JavaScript is what is known as a client-side script. Most Web applications, such as a search engine, work because of an interaction between the user's device

### Some of the dynamic website enhancements performed by JavaScript are:


1. Autocomplete
2. Loading new content or data onto the page without reloading the page
3. Rollover effects and dropdown menus
4. Animating page elements such as fading, resizing or relocating
5. Playing **audio and video**
6. Validating input from Web forms
7. Repairing browser compatibility issues

05. Question : What are Objects?
>>We know that JavaScript variables are containers for data values,**Objects** are variables too. But objects can contain many values. 
The values are written as **name:value** pairs (name and value separated by a colon), Example:
```
const car = {type:"Fiat", model:"500", color:"white"};
```
06. Question : What is an array and how is it different from an Object in Javascript?
>>An array is a special variable, which can hold more than one value **or** We use arrays whenever we want to create and store a list of multiple items in a single variable. And you can access the values by referring to an index number.
Example :
```
 const cars = ["Saab", "Volvo", "BMW"];
let car = cars[0];
```
>>**Objects** are used to represent a **thing** in your code. That could be a person, a car, a building, a book, a character in a game — basically anything that is made up or can be defined by a set of characteristics. In objects, these characteristics are called properties that consist of a key and a value.  **Basic object syntax**
```
var object = {
  key: 'value'
};
```
07. Question : What is a function?
>>A JavaScript function is a block of code designed to perform a particular task.
A JavaScript function is executed when "something" calls it.
```
function multiplication(p1, p2) {
  return p1 * p2;   // The function returns the product of p1 and p2
}
```
### Why Functions?

You can reuse code: Define the code once, and use it many times.
You can use the same code many times with different arguments, to produce different results.
```
let x = myFunction(4, 3);   // Function is called, return value will end up in x

function myFunction(a, b) {
  return a * b;             // Function returns the product of a and b
}
```
08. Question : How can we implement call by value and call by reference in Javascript?
>>**call by value** \
1.Function arguments are always passed by value.\
2.It copies the value of a variable passed in a function to a local variable.\
3.Both these variables occupy separate locations in memory. Thus, if changes are made in a particular variable it does not affect the other one.
### Example:

```
<script type="javacript">
	// By value (primitives)
	var a = 5;
	var b;
	b = a;
	a = 3;
	console.log(a);
	console.log(b);
</script>
```
**call by reference** \
>>It behaves quite differently from by value. All objects interact by reference
1.In JavaScript, all objects interact by reference.\
2.If an object is stored in a variable and that variable is made equal to another variable then both of them occupy the same location in memory.\
3.Changes in one object variable affect the other object variable.
```
<script>

	// By reference 
	var c = { cheer : 'keet it up' };
	var d;
	d = c;

	// Mutating the value of c
	c.greeting = 'you can do it';
	console.log(c);
	console.log(d);
</script>

```



09. Question : What are the primitive data types in Javascript?
>>**Primitive data types** : The predefined data types provided by JavaScript language are known as primitive data types. Primitive data types are also known as in-built data types.
10. Question : What is DOM?
>>With the HTML DOM, JavaScript can access and change all the elements of an HTML document.When a web page is loaded, the browser creates a Document Object Model of the page.The HTML DOM is a standard for how to get, change, add, or delete HTML elements.
## Number
Number data type in javascript can be used to hold decimal values as well as values without decimal.
```
<script>
	let x = 250;
	let y = 40.5;
	console.log("Value of x=" + x);
	console.log("Value of y=" + y);
</script>

```
## String
The string data type in javascript represents a sequence of characters that are surrounded by single or double-quotes
  ```
<script>
	let str = 'Hello All';
	let str1 = "Welcome to my new house";
	console.log("Value of str=" + str);
	console.log("Value of str1=" + str1);
</script>
```
## Undefined
The meaning of undefined is ‘value is not assigned’.
```
<script>
	console.log("Value of x=" + x);
</script>

```
## Boolean
The boolean data type can accept only two values i.e. true and false.
```
<script>
	console.log("value of bool=" + bool);
</script>

```
## Null
This data type can hold only one possible value that is null.
```
<script>
	let x = null;
	console.log("Value of x=" + x);
</script>

```
11. Question : Why do we need DOM?
>>With the object model, JavaScript gets all the power it needs to create dynamic HTML:

    JavaScript can change all the HTML elements in the page
    JavaScript can change all the HTML attributes in the page
    JavaScript can change all the CSS styles in the page
    JavaScript can remove existing HTML elements and attributes
    JavaScript can add new HTML elements and attributes
    JavaScript can react to all existing HTML events in the page
    JavaScript can create new HTML events in the page




