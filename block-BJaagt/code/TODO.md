Go through the code below and write down the process of making decision about looking for the variable. Also write the output of the code below.

Example:

```js
function hello() {
  var username = "Arya";
}
console.log(useranme); // output
```

In above code we are looking for the variable named `usename`. There is no variable named `username` in the global scope. The variable is inside the function named `hello` and we can't access the variable defined inside a function from outside.

The above code will throw an error `Reference Error username is not defined`.

2. Go through the code below and write down the process of making decision about looking for the variable. Also write the output of the code below.

```js
{
  const username = "Arya";
}
console.log(useranme); // output
```

in the above code variable username is defined inside the block thats why it is in private scope and we will get error as variable username is not defined

3. Go through the code below and write down the process of making decision about looking for the variable. Also write the output of the code below.

```js
if (true) {
  let username = "Arya";
}
console.log(useranme); // output
```

here variable username is declared into global scope of if block thats why we will get error as variable username is not defined.

4. Go through the code below and write down the process of making decision about looking for the variable. Also write the output of the code below.

```js
if (true) {
  var username = "Arya";
}
console.log(useranme); // output
```

here variable username is declared into global scope of if block thats why we will get error as variable username is not defined.

5. Go through the code below and write down the process of making decision about looking for the variable. Also write the output of the code below.

```js
let username = "John";
if (true) {
  var username = "Arya";
}
console.log(useranme); // output
```

here at first we declare variable username with let keyword.now in if block if we try to declare variable username with keyword var then we will get error as variable username is already declared as we cannot redeclare variable declared with var keyword.

6. Go through the code below and write down the process of making decision about looking for the variable. Also write the output of the code below.

```js
let username = "John";
if (true) {
  let username = "Arya";
}
console.log(useranme); // output
```

here as both variables are declared with keyword var thats why we will not get error and as output we will get Arya in console log.

7. Go through the code below and write down the process of making decision about looking for the variable. Also write the output of the code below.

```js
let username = "John";
function sayHello() {
  let username = "Arya";
}
sayHello();
console.log(useranme); // output
```

here as value of username is updated in function execution context memory thats why we get "JOhn" as output.

8. Go through the code below and write down the process of making decision about looking for the variable. Also write the output of the code below.

```js
for (var i = 0; i < 10; i++) {
  console.log(i, "First"); // output
}
console.log(i, "Second"); // output
```

for every value of 0-9 we will get log of vvalue .and as after last increment i becomes 10 and for loop stops we will get log of value "10, second"

9. Go through the code below and write down the process of making decision about looking for the variable. Also write the output of the code below.

```js
for (let i = 0; i < 10; i++) {
  console.log(i, "First"); // output
}
console.log(i, "Second"); // output
```

here as let keyword have block level scope so in if block we can acess i variable but outside if block we cannot access i so we get error as variable i is not defined.
