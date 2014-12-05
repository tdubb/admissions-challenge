# Admissions Challenge 1 of 2

This is the first of two Admissions Challenges for MakerSquare. This will show your knowledge of basic JavaScript. The next one will be more advanced, and will be presented to you after your "Admissions Q&A Interview".

Create a 'mks-admissions-challenge-1.js' file that has the answers to each of these exercises. All exercise answers should be in the same file, separated by comments. 

#### When you're finished...
[Submit it here.](https://makersquare.typeform.com/to/wdEmGQ)

----
## Exercise #1.1

Write a function `yell` that takes a string and console logs that string **in all caps**.

```javascript
var yell = function (string) {
  // TODO
}
```

----
## Exercise #1.2

Write a function `addFive` such that the following code works:

```javascript
var addFive = function (x) {
  // TODO
}

console.log("addFive(3) should be 8:", addFive(3));
console.log("addFive(6) should be 11:", addFive(6));
```

----
## Exercise #1.3

Write a function `divideBy` such that the following code works:

```javascript
var divideBy = ???? // TODO

var result = divideBy(50, 2);
console.log('Result should be 25:', result);

result = divideBy(40, 10);
console.log('Result should be 4:', result);

result = divideBy(99, 3);
console.log('Result should be 33:', result);
```

----
## Exercise #2.1

Fix the following code (1 syntax error) so that the function returns `'SLAP'`:

```javascript
var slap = function {
  return 'SLAP';
};
slap();
```

----
## Exercise #2.2

Fix the following code (1 syntax error) so that the function runs:

```javascript
var poke = function (name) {
  return name ' reproaches your behavior.';
};
poke('Billy');
```


----
## Exercise #2.3

Fix the following code (2 logic errors) so that the function returns a sensible message:

```javascript
var doubleIt = function (x) {
  return X + ' times two is ' + x;
};
doubleIt(8);
```

----
## Exercise #2.4

Fix the following code (1 logic error) so that the function runs:

```javascript
var greet = function () {
  return "Welcome, " + name;
};
greet('Bob');
```

----
## Exercise #2.5

Fix the following code (1 syntax error, 1 logic error) so that the function runs:

```javascript
var poke = fuction () {
  console.log('ow');
};
poke;
```

----
## Exercise #2.6

Fix the following code (1 syntax error, 1 logic error) so that the code alert the correct message:

```javascript
var askify = function (request) {
  "Can you please " request + "?";
};

var result = askify('fix me');
console.log('Result should be "Can you please fix me?":', result);
```

----
## Exercise #2.7

Fix the following code (2 syntax errors) so that the function runs:

```javascript
var multiplyString = function (string, times) {
  if (times === 0) {
    return '';
  }
  else {
    return string + multiplyString(string times - 1);
  }
};

var result = multiplyString('Mike' 5);
console.log(result);
```

----
## Exercise #3.1

Write a JavaScript program that prompts the user for a number:

* If the number is divisible by 7, alert a lucky message
* If the number is even, alert that they are an even steven.

----
## Exercise #3.2

Write a JavaScript program that prompts the user for a password of your choice:

* If correct, it alerts an access granted message
* If not correct, it alerts an access denied message
* Only allow the user to try up to three times.

----
## Exercise #3.3

Write a JavaScript program that **prompts** three times, and then shows a **single alert** with all three strings in the opposite order they were prompted.

----
## Exercise #4

Write a function `welcome` that:

  * Takes two parameters `name1` and `name2`
  * If **two** parameters are present, returns "Welcome, #{name1} and #{name2}!"
  * If **only one** parameter is present, returns "Welcome, #{name1}!"

Remember JavaScript **does not** have string interprolation, so you can't just use "#{name1}".

```javascript
var welcome = ???? // TODO

var result = welcome('Alice', 'Bob');
console.log('Result should be "Welcome, Alice and Bob!"', result);

var result = welcome('Alice');
console.log('Result should be "Welcome, Alice!"', result);
```
