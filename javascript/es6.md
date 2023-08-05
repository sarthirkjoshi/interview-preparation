**ES6**

- **ECMA script 2015 is called ES6**


**1. Let and Const**

- Variables declared with **var** are **functional scope** OR **global scope**.
- Variables declared with **let and const**  are **block scope**.
- We can **not change** value of **const**
  
  Ex.
	
  function abc(){    //**functional scope**
  if (b=2){     //**block scope** }}


**2. Template Literals**

- use backtick (`) in orde to use this
- Ex. `My name is ${name}`
- We can also add expression
- Ex. `const a=2;b=3;
       `My name is {a=b}`
- methods - startwith(), endsWith(), includes(), ${name}.repeat(5)


**3. Array destructuring** 

- Expression that makes it possible to **unpack** values from **array**
  Ex.  const [a,b,c] = ['s','a','r']
- swap 2 numbers without using 3rd variable
  let a=1, b=2;  let [a,b] = [b,a];  console.log(a,b);

**4. Object destructuring** 
-  **unpack properties** from **object**
  Ex. let {a,b,c} = {a: "1",b: "2",c: "3"}


**5. Arrow functions** (fat arrow functions)
const a = () =>{}

**6 Default parameters**
Ex. function(a,b=2){}

**7. Rest parameters** 
- allows us to represent an indefinite number of arguments as an array
- 


   
    
