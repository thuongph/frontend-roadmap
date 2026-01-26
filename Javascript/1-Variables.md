# Variable scope

### Block scope

==> `let` and `const` --> closet containing block statement

### Function scope

==> `var` --> closet containing function or static initialization block inside a class

### Global scope

==> `var` outside a parent function, or `let` or `const` outside a parent block

```
{
    let scopedVariable = true;
    console.log( scopedVariable );
}
> true

scopedVariable
> ReferenceError: scopedVariable is not defined

{
  const scopedConstant = false;
}
const scopedConstant = true;

scopedConstant;
> true

function myFunction() {
    var scopedVariable = true;

    return scopedVariable;
}

scopedVariable;
> ReferenceError: scopedVariable is not defined

myFunction();
> true

scopedVariable;
> ReferenceError: scopedVariable is not defined

var functionGlobal = true; // Global
let blockGlobal = true; // Global

{
    console.log( blockGlobal );
    console.log( functionGlobal );
}
> true
> true

(function() {
    console.log( blockGlobal );
    console.log( functionGlobal );
}());
> true
> true
```

# Variable Hoisting

==> move the declaration of functions, variables, classes, or imports to the **top** of their scope

```
hoistedVariable
> undefined

var hoistedVariable = 2 + 2;

hoistedVariable\
> 4

{
    hoistedVariable;

    let hoistedVariable;
}
> Uncaught ReferenceError: can't access lexical declaration 'hoistedVariable' before initialization
```
