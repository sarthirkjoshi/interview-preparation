# Code -  
```

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

//output - [1,2,3,4,5,6,7,8,9] 
```

# Sandbox link -  https://codesandbox.io/s/flatten-array-drzq4k?file=/src/App.js:0-382

