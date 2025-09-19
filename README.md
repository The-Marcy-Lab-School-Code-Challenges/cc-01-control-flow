# **Code Challenge: Control Flow**

**Instructions**

1. Clone down this assignment to your `tip-challenges` directory in your environment.
2. Code your solutions using JavaScript in `index.js`.
3. **Be sure to run and test your code thoroughly.**
4. By the end of class, **commit and push your changes up to Github**.
5. Using the browser, verify that your solution is in your remote repo on GitHub.

---

### example.js

In this file, there are two functions. To test the functions, you can run `node example.js` within this repo. 

### 🧠 `checkValue`

- Tests different values (like strings, numbers, `null`, etc.)
- Shows how JavaScript decides if a value is **truthy** or **falsy**
- Helps us see what will make a conditional statement run

### 📝 `assignGrade`

- Takes in a test score (0–100)
- Uses `if / else if / else` to choose which letter grade to return
- Shows how to write pass data through control flow with conditionals

```jsx

// This function takes in a value and shows how JS evaluates it
const checkValue = (value) => {

  // JavaScript will convert the value to a boolean inside this if statement, depending on whether this value is truthy or falsy
  if (value) {
    console.log("This value is truthy ✅");
  } else {
    console.log("This value is falsy ❌");
  }

  console.log("--------------------------");
};

// 🧪 Test with different data types
//checkValue("Hello");     // String (truthy)
//checkValue("");           // Empty string (falsy)
//checkValue(42);            // Number (truthy)
//checkValue(0);             // Number zero (falsy)
//checkValue(true);          // Boolean (truthy)
//checkValue(false);         // Boolean (falsy)
//checkValue(undefined);     // Undefined (falsy)
//checkValue(null);          // Null (falsy)
//checkValue(NaN);            // Not-a-Number (falsy)

// This function takes a numeric test score (0–100) 
// and returns the corresponding letter grade (A–F)
const assignGrade = (score) => {
  if (score >= 90) {
    return "A";
  } else if (score >= 80) {
    return "B";
  } else if (score >= 70) {
    return "C";
  } else if (score >= 60) {
    return "D";
  } else {
    return "F";
  }
};

// 🧪 Test the function
//console.log(assignGrade(95)); // "A"
//console.log(assignGrade(74)); // "C"
//console.log(assignGrade(40)); // "F"

```

---

## index.js

Write a function called `outfitPicker` that:

- Takes in a temperature (`temp`), which is a number type
- Uses **if / else if / else** statements
- Returns an **outfit suggestion** (as a string) based on the temperature

```jsx

/*
Complete the function so that it returns the following:
80 or above → "Wear shorts and a t-shirt."
60–79 → "Wear jeans and a light jacket."
40–59 → "Wear a sweater and pants."
Below 40 → "Wear a heavy coat, scarf, and boots."
*/

const outfitPicker = (temp) => {
  // ✍️ Write your code here
};

//Test your function below
```
