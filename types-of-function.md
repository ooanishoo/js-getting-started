# Types of Function:
## Anonymous Function

```javascript

var foo = function() {
  // ..
};

```

## Named Function

```javascript

var foo = function bar() {
  // ..
};

```

The first function expression assigned to the foo variable is called anonymous because ithas no name.The second function expression is named (bar), even as a reference to it is also assignedto the x variable. Named function expressions are generally more preferable, thoughanonymous function expressions are still extremely common.

## Immediately Invoked Function Expressions (IIFEs)Into JavaScript53

```javascript

(function (){console.log("hello world");})();

```

