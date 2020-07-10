`` `${var name} ` `` this is javascript template literal
### Shadowed Variables
A local variable,declared in a function, that also exists globally.

### Indirect and direct function execution
It can be confusing to see that there seem to be two ways of executing a function:
``` 
 function add() {
 something = someNum + someOtherNum;
  }   
```
add() vs add

It's important to understand why we have these "two ways"!
In general, you call a function that you defined by using its name (e.g. add) and adding parentheses (with any parameters the function might need - or empty parentheses if no parameters are required like in the above example).

=> add()

This is how you execute a function from your code. Whenever JavaScript encounters this statement, it goes ahead and runs the code in the function. Period!

Sometimes however, you don't want to execute the function immediately. You rather want to "tell JavaScript" that it should execute a certain function at some point in the future (e.g. when some event occurs).

That's when you don't directly call the function but when you instead just provide JavaScript with the name of the function.

=> `` someButton.addEventListener('click', add); ``

This snippet would tell JavaScript: "Hey, when the button is clicked, go ahead and execute add.".

`` someButton.addEventListener('click', add()); `` would be wrong.

Why? Because JavaScript would encounter that line when it parses/ executes your script and register the event listener AND immediately execute add - because you added parentheses => That means (see above): "Please execute that function!".

Just writing add somewhere in your code would do nothing by the way:
```
let someVar = 5;
add
alert('Do something else...');
```
Why?

Because you just throw the name of the function in there but you don't give any other information to JavaScript. It basically doesn't know what to do with that name ("Should I run that when a click occurs? After a certain amount of time? I don't know...") and hence JavaScript kind of ignores this statement.
### parseInt() ------ convert a string into number(inbuilt javascript function).
### parseFloat() ------ convert a string/number into float(inbuilt javascript function).
### varname.tostring() ------ convert varname to string (inbuilt javascript function).
### + operator in javascript supports both strings and numbers(3 + '3' = 33)

## Arrays
`` let a = []; `` wil create an array
a.push() method is used to push elments array with existing elements.
### undefined
Default value of uninitilized variable
### NaN(not a number) type == number
if we multiply("hi" * 3) we get error nan
### null
not a default value, to reset/clear a variable we can assign the variable with null
### typeof keyword
to check type
### html defer attribute
<script src = " " defer >   </script> when we put this code inside the head tag then this script is downloaded but get in role after parsing the html code(due to defer attribute)
or we can add the script tag at the end of html code
### html async attribute
<script src = " " async >   </script> it is same as defer but the difference is that the script executes right away once it is downloaded, it does not wait for the html code to parse
### falsy or truthy values
If we pass any other value than boolean in if condition then javascript forces it make boolean this values are called truthy or falsy values
0 is considered as false/falsy
other no than 0 including negative no are considered as true/truthy
empty string is treated as false/falsy
any other string (including "false" treated as true/truthy
empty object and array and all other object and array treated as true/truthy
nan null undefined treated as false/falsy

### Statement vs Expression
expression is right side part of equal sign
statement is that which cannot be written in right side of an equal sign(if statement or complete part, left and right part of equal sign
### some shorthands and tricks
#### How can we convert or coerce a truthy and falsy value to a real boolean ?
we use double exclamation mark !! before the truthy or falsy value(basically it is double negation !!)
#### we can assign a default value to a variable using or || operator
see the video 95

#### use ``` "use strict" ``` in start of an line or function to enable strict mode.

## there are two types of values
primitive values - strings, number, boolean, null,undefined and symbols (stored in memory- normally in stack)
refrence values  - all other objects( more expensive to create) {generally stored in heap}
## Garbage collector
it is built in browsers engine and it periodically checks the browser memory/heaps for unused objects(objects without references/without addresses which are stored in variables).garbage collector removes these objects from the heap memory
