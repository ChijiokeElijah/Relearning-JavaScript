# JAVASCRIPT FUNCTIONS

In JavaScript, a function is a block of code that performs a particular task.

## FUNCTION DEFINITION

Function definition or declaration.

To define a function, we use the `(function)` keyword, the name of the function followed by a parenthesis and the function body enclosed in a curly braces `{}`.

```
    function functionName(parameters){
        
        //function body
    }

```

Inside the function body, you can write the code to be executed whenever the function is called.

To call a function, you write the  function name together with a parenthesis that contains the arguments the corresponds with the parameters if any.

A function can accept zero, one or more parameters. In the case of multiple parameters, they are separated by commas.

When declaring a function, you indicate the parameters; when calling a function, you pass the arguments that corresponds with the parameters.

How do I get the result of the task from my function?

Every function in JavaScript by default returns `undefined` unless a return value is specified.

To indicate the return value for your function, a `return` statement is used followed by the value or expression.


The function below adds two numbers without a `return` statement.

```
    function Sum(a, b){

    alert(a + b);

    }

    let Output = Sum(2, 3);
    console.log('Answer:', output);
```

Output:

```
    //5
    //Answer: Undefined

```

The function below adds two numbers with a `return` statement.


```
    function addNum(a, b){
    
    return a + b;

    }

    let output = addNum(2, 3);
    console.log('Answer:', output);

```

Output:

```
    //5
    //Answer: 5

```

A function body can contain conditionals.

This function does nothing if no name argument is not passed during the function call but returns `Hello name` when a name argument is passed 


```
    function Greetings(name){

    if(!name){
        return;
    }else{
        return (`Hello ${name}`);
    }
}

    console.log(Greetings('Ceejay')) // Hello Ceejay
```

## Function Hoisting

A function can be called before declaring it. This is called hoisting.

The JavaScript engine  moves function declarations to the top of the code before executing the code.

```
console.log(Greetings('Ceejay')) // Hello Ceejay


 
 function Greetings(name){

    if(!name){
        return;
    }else{
        return (`Hello ${name}`);
    }
}


```
