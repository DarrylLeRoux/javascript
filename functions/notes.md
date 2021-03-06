# First-class functions

- Javascript treats functions as first class citizens
- Functions are simply **_values_**
- Functions are just another "type" of object
- We can store functions in variables or properties
- We can pass functions as arguments to other functions
- We can return functions from functions
- Can call methods on functions

# Higher-order functions

- A function that **_receives_** another function as an argument, that **_returns_** a new function, or **_both_**
- This is only possible because of first-class functions
- `btnClose.addEventListener('click', greet)`
- `addEventListener` is the higher-order function, and the `greet` function is the callback function

```
function count(){
      let counter = 0;
      return function() {
        counter++
      }
  }
```
