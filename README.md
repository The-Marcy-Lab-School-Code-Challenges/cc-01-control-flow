# **Code Challenge: Control Flow**

## **Instructions**

1. Clone down this assignment to your `code-challenges' directory in your environment.
2. Code your solutions using JavaScript in `index.js`.
3. **Be sure to run and test your code thoroughly and write all functions using arrow syntax!**
4. By the end of Code Challenge, **commit and push your changes up to Github**.
5. Using the browser, verify that your solution is in your remote repo on Github.

## **Code Problems**

### **Code your solutions to these problems in the `index.js` file**

1. Write a function named `greatestOfTwo` that takes in two integer arguments and returns the **largest** of both arguments. You can assume both integers will be different values.
    
    ```
    greatestOfTwo(1, 14) // returns 14
    greatestOfTwo(-2, 2) // returns 2
    
    ```
    
2. Write a function named `areBothSame`, that takes in two arguments and returns true if both arguments are truthy in value, and returns false if not.
    
    ```
    areBothSame(true, 1) // returns true
    areBothSame("2", 2) // returns true
    areBothSame("5", 2) // returns false
    
    ```
    
3. Write a function named `areBothEqual`, that takes in two arguments and returns true if both arguments are the same in data type and value, and returns false if they are not.
    
    ```
    areBothEqual("2", "2") // returns true
    areBothEqual("2", 2) // returns false
    areBothEqual(true, 1) // returns false
    areBothEqual(7, 7) // returns true
    ```
    
    ### Bonus:
    
    Refactor all of the functions so that it returns an error message if only one or zero arguments are passed to the function. 
    
    ```jsx
    greatestOfTwo(1) // returns "Only one argument was passed"
    greatestOfTwo() // returns "No arguments were passed" 
    
    areBothSame(true) // returns "Only one argument was passed"
    areBothSame()  // returns "No arguments were passed" 
    
    areBothEqual("2") // returns "Only one argument was passed"
    areBothEqual() // returns "No arguments were passed" 
    ```
