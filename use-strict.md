# Use Strict
## "use strict"

One key difference (improvement!) with strict mode is disallowing the implicit auto-globalvariable declaration from omitting the var:

```javascript

function foo() {
    "use strict"
    var q = 1;
    var w = 2;
    console.log(q);
    console.log(w);
}
foo();

// output : 1 2

```

```javascript

function foo() {
    "use strict"
    var q = 1;
    w = 2;
    console.log(q);
    console.log(w);
}
foo();

// output : ReferenceError: w is not defined
// missing var

```
