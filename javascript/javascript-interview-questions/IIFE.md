# Immediately Invoked Functions

- prevents polluting globalc scope variables and functions .
- Immediately getting executed
- Types -  named IIFE and simple IIFE (without name)
- please dont forget to **end** IIFE with **semicolon(;)** at the end
- Sandbox - https://codesandbox.io/s/iife-sl7532?file=/src/App.js

- Code 
```//IIFE
//1.Named IIFE
(function abc() {
  console.log("1");
})();

//2.Normal IIFE with arrow function
(() => {
  console.log("2");
})();

//3. IIFE with taking inputs from function
((name) => {
  console.log(`Hi ${name}`);
})("Shaurya");
