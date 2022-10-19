# Code Challenge: Strings and Arrays

## Instructions

1. Clone down this assignment to your `code-challenges' directory in AWS Cloud9.  
2. Code your solution using JavaScript in `index.js`. 
3. **Be sure to run and test your code throughly!**
4. By the end of Code Challenge, **commit and push your changes up to Github**.
5. Using the browser, verify that your solution is in your remote repo on Github.

## Code Problems

### **Test your solutions for questions 1 and 2 with the following variable:** 
```javascript
const fellows = "marcy fellows"
```

1. Write a function named `charCount` that takes in a string and returns an object where the keys are letters in the string and the value of each key is a count of how many times the character appears in the string.
    
    ```javascript
    const fellows = "marcy fellows"
    charCount(fellows) // returns {" ": 1, a: 1, c: 1, e: 2, f: 1, l: 2, n: 1,o: 2, p: 1, s: 2, t: 1, w: 1}
    ```
    
2. Write a function named `letterCount` that takes in a string and returns an object where the keys are letters in the string and the value of each key is a count of how many times the character appears in the string, not including empty spaces. 
    
    ```javascript
    charCount(capstone) // returns {a: 1, c: 1, e: 2, f: 1, l: 2, n: 1,o: 2, p: 1, s: 2, t: 1, w: 1}
    ```
