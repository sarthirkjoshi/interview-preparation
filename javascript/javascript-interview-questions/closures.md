- Closure is a function that references variables in the outer scope from inner scope.
- preserves the outer scope inside its inner scope even after outer function is returned.
- Code -

```
//closure
const closure = () => {
  let a = 1;
  const calculate = () => {
    return (a += 1);
  };
  return calculate;
};
let result = closure();
console.log(result());
```
Sandbox -https://codesandbox.io/s/closure-sl7532?file=/src/App.js:24-194
