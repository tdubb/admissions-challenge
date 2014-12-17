# Admissions Challenge 1 of 2

This is the first of two Admissions Challenges for MakerSquare. This will show your knowledge of basic JavaScript. The next one will be more advanced, and will be presented to you after your "Admissions Q&A Interview".

Create a 'mks-admissions-challenge-1.js' file that has the answers to each of these exercises. All exercise answers should be in the same file, separated by comments. 

#### When you're finished...
[Submit it here.](https://makersquare.typeform.com/to/wdEmGQ)

----

## Passing notes in class

This challenge will require you to decode messages that we've written out for you. You will be required to write your code in JavaScript. You should have 1 function called `translate` that takes an input of an array and gives an output of a single string:

```javascript
var translate = function(arr) {
  // Your code goes here.
  // You'll process the array arr and return a string with the message
};
```

If you're having trouble solving this, you should review [Codecademy](http://www.codecademy.com/en/tracks/javascript) and our [JS Intro course](http://mks.io/js-intro).

## Step 1

We're having you decode a message that we've written out for you. Here's what the messages look like:

```text
laugh
ride
lol
hall
bozo
```

On first glance, this may seem like an odd sentence. However, if you look at the last letter of each word, you will see a very sensible message: "hello".

Your task: given an array of words, translate the encoded message and retrieve the message needed.

Here are a couple of examples:

```javascript
var translate = function(arr) {
  // Your code here
};

var result = translate(["laugh", "ride", "lol", "hall", "bozo"]);
console.log(result); // This should print hello

result = translate(["dog", "polo", "boo", "sudd", "noob", "smiley", "ride"]);
console.log(result); // This should print goodbye
```

## Step 2

We've been infiltrated! Our code was way too easy to hack, and we need to change up our encryption. Each word in the array is translated to a letter depending on the first and last letter of the word. The word is translated into the greater of the two letters. (Note: you can compare letters in JS: "c" > "b")

Here are a couple of examples of how words translate to letters:

"hello" translates to "o" because "o" is greater than "h".
"goodbye" translates to "g" because "g" is greater than "e".

Full Example:

```text
wazdee
apple
love
bic
nooo
more
end
```

This will translate to "welcome".

Here's how the function should work:

```javascript
var translate = function(arr) {
  // Your code here
};
var result = translate(["wazdee", "apple", "love", "bic", "nooo", "more", "end"]);
console.log(result); // This should print welcome

result = translate(["bria", "loud", "fuzu", "antidote]);
console.log(result); // This should print blue
```

## Step 3 - Extra Credit

This is not required. You should schedule an interview before you attempt this.

We keep getting hacked! Let's get better at this. Looking at the first and last letter is not effective. We need a new structure. We will look at the 1st letter of the first word, 2nd letter of the 2nd word, 3rd letter of the 3rd word and so forth. If you are looking for the 10th position of the 10th word, but the 10th word only has 4 letters, you should use the modulo function which will result in you picking the 2nd letter.

Example:

```text
welcome
keep
tabular
binding
el
rev
```

This message would decode to "webdev".

---

# Coding Challenge Part 2

[Submit](https://makersquare.typeform.com/to/wdEmGQ) a completed version of this first challenge to access the next one. You'll be given the link to the second one automatically upon submission of this one. 
