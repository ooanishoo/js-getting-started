#Switch
```

function foo() {
    var a = prompt("enter a string");
    var a = "hello";

    switch (a) {
        case "hello":
            typeof a;
            console.log(a);
            break;

        case 1:
            typeof a;
            console.log(a);
            break;

        case true:
            typeof a;
            console.log(a);
            break;

        default:
            console.log("no match found");
            break;
    }
}
foo();

```
