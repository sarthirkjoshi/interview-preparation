# useState hook

- asynchronous hook
- Code:
  
    `const [count,setCount]=useState()`
- with initialState, always take prevState and apply your requirements to that

  Ex. - setCount(preCount=>prevCount+1)
- usecase3- initialState as object

  setaName({...name, firstName:value})

- usecase4 - initialState as Array
- It is used to toggle boolean values(true, false),Objects and arrays 
