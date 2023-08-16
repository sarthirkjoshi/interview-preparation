# Pure and Impure Functions

- gives **same output** for **same input**
-  **Predictable**, Readable, Reusable, Testable
- Not having any side effects
- It doesnt use console.log as well as console is external api and not javascript
- You should always try to convert impure to pure function so that it will not be changed by global scope or any other function
- Sandbox - https://codesandbox.io/s/pure-functions-fmmjps?file=/src/App.js
- Code
```
//Pure functions
function greeting(name) {
  return `Hey ${name}`;
}
console.log(greeting("Shaurya"));
/********************************* */
//ImPure functions
let name = "Shaurya";
function greeting1() {
  console.log(`Hi ${name}`); //console is external API
}
greeting1();
```


  
