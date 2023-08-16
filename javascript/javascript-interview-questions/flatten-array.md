# Code -  
```
import "./styles.css";

let arr = [1, [2, 3], 4, [5, 6], 7, 8, [9]];
let result = [];
const flatten = (arr) => {
  for (let i = 0; i < arr.length; i++) {
    if (Array.isArray(arr[i])) {
      flatten(arr[i]);
    } else {
      result.push(arr[i]);
    }
  }

  return result;
};

console.log(flatten(arr));

export default function App() {
  return <div className="App"></div>;
}
```

# Sandbox link -  https://codesandbox.io/s/flatten-array-drzq4k?file=/src/App.js:0-382

