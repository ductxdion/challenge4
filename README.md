### The purpose of this challenge is to assess your : 

### List Error and How to fix it
1. Uncaught ReferenceError: require is not defined.
Line 1: var _ = require('lodash')
File: code.js
=>  Error in declaration to use lodash library. Learn simple lodash project to understand how to declare and use lodash.
    Fix: import _ from 'https://cdn.jsdelivr.net/npm/lodash-es@4.17.21/lodash.js';
        Adding type="module" in index.html when using import (It's called ES6 module)

2. Error: Access to script at. 
=> Deploy to IIS or installing extension Live Server in visual code

3. Uncaught RangeError: Invalid array length
    Line: 25
    File: code.js
=> I'm guessing. The purpose of the randomArray function is to creat a new random array from an existing array.
    Because the first parameter can be larger than the second parameter. This is unreasonable.
    Condition while (arr.length >= 0) : Means we need to use some function that can remove elements in arr => I think we should use splice function instead.
    When the array arr is completely cleared, arr.length = 0. Therefore, to exit the loop, we need to change the condition to arr.length > 0
    Using console.log to check the logic easier.
4. favicon.ico 404 (Not Found)
File: index.html
Line: 6
=> Fix to not see error message in Console log.