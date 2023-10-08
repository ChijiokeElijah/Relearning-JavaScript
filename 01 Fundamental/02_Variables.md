## Variables are like containers we use to store data. Declaration is the creation of the variables after which values can be assigned to them.

```
    let myName = 'Cindy'
    let myAge = 19;

    console.log("My name is " + myName + ". I am " + myAge + " years old." )

```
In the example above, myName is a variable used to store the value - Cindy. If I want to access the value, I will have to reference the variable name.

Without the variables, I will have to supply the value each time it is requested for in the program.

- Variables can be declared only once and can be done in 4 ways.
- Variables can be named anything except JavaScript reserved words eg. let, console, var etc.
- Variable names must start with either alphabets, underscores or dollar signs.
- Variables can be reassigned a new value.

## There are four ways to declare a variable in JavaScript

1. Automatically: The code below shows an example of automatic variable declaration.

```
 x = 'Orange'

```

2.  `var`: `var` was the method of variable declaration used from 1995 to 2015, hence it's considered the old way. Variables declared with `var` are function scoped or global scoped. In other words, `var` doesn't support block scope.
Example of `var` declaration is below.

```
 var x = "Mango"

 if(x){
 var fname = 'Stanley'
 }
 
 console.log(fname)  //Stanley

```
3. `let`: `let` is a modern way of variable declaration. It is block scoped. This means variables declared in a block which is usually `{}` cannot be accessed outside the block.

```
 let x = "Apple"

 if(x){
    let fname = 'Stanley'
 }

console.log(fname)  //Uncaught ReferenceError: fname is not defined

```

4. `const`: `const` is similar to `let`, except that `const` is used for constants. Variables whose value will not change in the course of the program.

```
 const myId = 124312

```
