![](README.jpg)

# WEB 101: JAVASCRIPT FUNDAMENTALS 3

## INSTRUCTIONS

It is time to write some functions!

Write these in the `script` tag of a skeleton HTML file.

In the exercises below, just write each function and test the output with `console.log`.

1. Write a function called `add9` that takes one number and returns that number + 9.

2. Write a function called `multiplyNum` that takes 2 numbers and returns their product.

3. Write a function called `capitalizeStr` that takes a string and returns that string with _only_ the first letter capitalized. Make sure that it can take strings that are lowercase, UPPERCASE or BoTh. **[*]**

4. Write a function called `lastLetter` that takes a string and returns the last letter of that string **[*]**:

   1. `lastLetter("abcd")` should return `"d"`

5. Write a function called `average` that takes 3 numbers and returns their average.

6. Write a function called `greaterNum` that takes 2 numbers and returns the greater one.

**Copy and paste the code below**, inside a `script` tag in your HTML page, and try to complete the exercise by filling the body of the functions. On each of the first 4 functions, you must also write the answer to the question **What type of functions is the next one?**. Try to go through the theory again and answer with one of the following terms: `Function Declaration` / `Function Expression` / `Arrow Function`.

```js
// 1) Type of function?
function add9(n) {
  return n + 9;
}

// 2) Type of function?
const multiplyNum = function (n1,n2) {
return n1 * n2;};

// 3) Type of function?
let capitalizeStr = (string) => {
return (    string.charAt(0).toLocaleUpperCase() + string.slice(1)  );};

// 4) Type of function?
function lastLetter(string) {
return string.slice(-1);}

// 5) Type of function?
function average(n1,n2,n3) {
return (n1 + n2 + n3) / 3;}

// 6) Type of function?
function greaterNum(n1,n2) {
 return n1 > n2 ? n1 : n2;}
```

Add the code in a new branch, in a new file named `fundamentals-3-quiz.html` and submit your Pull Request.

---

_Photo by Miguel Á. Padriñán from Pexels_
