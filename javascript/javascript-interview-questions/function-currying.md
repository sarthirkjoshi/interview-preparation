# Function Currying

- **Haskell Curry** American Mathematician and Logician
- Currying is a function that **takes one argument at a time** and **returns a new function expecting the next argument** till **last function** will return **desired output**
- Sandbox - https://codesandbox.io/s/function-currying-dh44sx?file=/src/App.js
- used in DOM manipulation as well
- loadash curry function
- Code
 
```
//currying function older way
function sum(x) {
  return function (y) {
    return function (z) {
      return x + y + z;
    };
  };
}
console.log(sum(1)(2)(3));

//currying function with ES6 arrow function
const sumOne = (x) => (y) => (z) => x + y + z;
console.log(sumOne(4)(5)(6));
```
