# javascript level 2 
>> 
01. question : Why do we use functions in JavaScript?
>> In JavaScript, a function allows you to define a block of code, give it a name and then execute it as many times as you want. A JavaScript function can be defined using *function* keyword.
**Example:**

```
function multiply(num1,num2) {
  let result = num1 * num2;
  return result;
}
```

02. question : What is Function Invocation?
>>The function invocation is used to execute the code inside the curly braces in the function definition by adding () after function name after it has been defined to invoke that particular function.
**Example:**
```
function car( color ) {
    return color;
}
car( red );
```
03. question : Does a function behave like an object in Javascript? Prove it by an example.
>>In JavaScript, functions are called Function Objects because they are objects. Just like objects, functions have properties and methods, they can be stored in a variable or an array, and be passed as arguments to other functions.


```
function message() {
    console.log("Greetings!");
}

console.log(typeof message);               // => function
console.log(message instanceof Object);    // => true
console.log(message instanceof string);    // => false

```
04. question : What are Events in Javascript?

>>JavaScript's interaction with HTML is handled through events that occur when the user or the browser manipulates a page. When the page loads, it is called an event. When the user clicks a button, that click too is an event. Other examples include events like pressing any key, closing a window, resizing a window, etc.

05. question : What is a string?
>>A JavaScript string stores a series of characters like "you can do it".
A string can be any text inside double or single quotes
Normally, strings like "you can do it", cannot have methods or properties because they are not objects.JavaScript treats strings as objects when executing methods and properties.
The first character is in position 0, the second in 1, and so on.
```
let care1 = "bmw";
let car2 = 'audi';
```
06. question : What is an array? Is it static or dynamic in Javascript?
>>In JavaScript, array is a single variable that is used to store different elements.It is often used when we want to store list of elements and access them by a single variable
Example:
```
// Initializing while declaring
var color = ["red", "black, "green", "blue"];

```

07. question : difference between map and set in javascript?
>>A **Set** is a collection dataset that needs to be composed of unique values,where a **Map** is when you have pairs of associated data when we map the keys to the value.
Example:

```
let set = new Set();

let kalu = { name: "kalu" };
let raju = { name: "raju" };
let pinki = { name: "pinki" };

// visits, some users come multiple times
set.add(kalu);
set.add(raju);
set.add(pinki);
set.add(kalu);
set.add(pinki);

// set keeps only unique values
alert( set.size ); // 3

for (let user of set) {
  alert(user.name); // kalu (then raju and pinki)
}
```

```
let map = new Map();

map.set('1', 'str1');   // a string key
map.set(1, 'num1');     // a numeric key
map.set(true, 'bool1'); // a boolean key


// Map keeps the type, so these two are different:
alert( map.get(1) ); // 'num1'
alert( map.get('1') ); // 'str1'

alert( map.size ); // 3
```

08. question : Difference between Array and Map?
>>




09. question :What are array methods? List a few names?
>>aaray methods are the oprations on array for particular task.
1. sort():	Sorts the elements of an array.
2. reverse():	Reverses the order of the elements in an array
3. indexOf()	Search the array for an element and returns its position
4. find():	Returns the value of the first element in an array that pass a test etc.



10. question :In how many ways can we traverse through an array in Javascript?
>>There are multiple ways one can iterate over an array in Javascript. The most useful ones are mentioned below. ...
Using while loop. 
using forEach method.
Using every method. 
Using map. 
