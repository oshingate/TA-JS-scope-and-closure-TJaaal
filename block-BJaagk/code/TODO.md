1. Convert the function below into different forms of function expression.

```js
function percentage(marks, total) {
  return (marks * 100) / total;
}

// Your code goes here
let percentage = (marks, total) => {
  return (marks * 100) / total;
};
let percentage = function name(marks, total) {
  return (marks * 100) / total;
};
let percentage = function (marks, total) {
  return (marks * 100) / total;
};
```

2. Write Function Declaration or Function Expression next to the function.

```js
function percentage(marks, total) {
  return (marks * 100) / total;
}
// Your answer

let percentage = (marks, total) => {
  return (marks * 100) / total;
};
```

```js
let percentage = function percentage(marks, total) {
  return (marks * 100) / total;
};
function percentage(marks, total) {
  return (marks * 100) / total;
}
```

```js
let percentage = function (marks, total) {
  return (marks * 100) / total;
};
function percentage(marks, total) {
  return (marks * 100) / total;
}
```

```js
let percentage = (marks, total) => {
  return (marks * 100) / total;
};
function percentage(marks, total) {
  return (marks * 100) / total;
}
```

```js
let percentage = (marks, total) => (marks * 100) / total;
function percentage(marks, total) {
  return (marks * 100) / total;
}
```

3. Why is a function definition an expression in JavaScript? Give one example of function expression.
   function Defination:-when we use function keyword to declare function then it is called as function defination.
   ex:-function percentage(marks, total) {
   return (marks \* 100) / total;
   }
   function-Expression:-when we store function into variable then it is called function expression.
   ex:-let percentage = (marks, total) => {
   return (marks \* 100) / total;
   };

4. Why is a function call an expression in JavaScript?
   as we get serires of steps after calling function thats why it is an expression.

5. Write VALID and INVALID next to each example below with the reason.

```js
function add(a, b) {
  return a + b;
}

let five = add(2, 3); // Answer valid here five will store 5 in it.
five = add; // Answer valid here five will store the function reference in it.
five = five(10, 11); // Answer valid as previously it has function reference in it here five will store 21 in it
five = function () {
  return "Hello";
}; // Answer valid here five will store function reference into it
```

6. What is the difference between function definition and function call? Explain with an example.
   in function defination we use function keyword to declare function and write steps to be executed.
   and in function call we call that series of steps to execute one by one
   ex:- function add(num1,num2){return num1+num2} //function defination
   add(1,2)//function call

7. What is the similarities between function definition and function call?
   both are used on functions
8. Is the code below valid or invalid. Explain with reason.

```js
function hello() {
  console.log("Hello World!");
}

hello.user = "Sam"; // valid as function is also a object
```

9. What is higher order function explain with an example.
<!-- higher order function is function which accepts another function as its parameter. -->

10. Explain what is callback function. Why you can pass a function inside a function?
<!-- call back function is used as parameter to HOF.  -->
