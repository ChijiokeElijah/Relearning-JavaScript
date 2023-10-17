# JAVASCRIPT ARITHMETIC OPERATORS

JavaScript performs arithmetic operations by accepting numerical as operands values and returns a single numerical value.

JavaScript supports the following arithmetic operators

- Addition (+)
- Subtraction (-)
- Multiplication (*)
- Division (/)

## 1. Addition Operator (+)

This operator returns the sum of two values.

```
    let addNum = 20 + 15 

    alert(addNum) //35

```

If either of the values is a `string`, the addition operator applies the following rules:
 - if both values are `strings`, it concatenates the two `strings`.

 ```
    let message = 'I am' + ' coming';

    alert(message);// I am coming

 ```

 Note that we can address the values through their `variables`.

 ```
    let message1 = 'I am coming';

    let message2 = 'tomorrow.';

    alert(message1 + " " + message2) //I am coming tomorrow.
 ```

 - if one value is a `string`, it implicitly converts the numeric value into a `string` and concatenates the two `strings`.

 ```
    let message1 = '20';

    let message2 = 25;

    alert(message1 +  message2); //2025
 ```


 ## 2. Subtraction Operator (-)

 The subtraction operator subtracts one value from the other.

 ```
    let num1 = 20;

    let num2  = 10;

    alert(num1 - num2)//10
 ```

 If a  value is a `string`, `boolean`, `null` or `undefined`, the JavaScript will;
 - Convert the value to a number using the  `Number()` function.
 - carry out a subtraction function.

 ```
    let firstNum = 12;

    let secondNum =  '12';

    alert(firstNum - secondNum) // 0

 ```

 ## 3. Multiplication Operator

 The symbol for multiplication operator in JavaScript is `(*)`. This operator multiplies two numbers
 and returns a single value.

 
 ```
   let firstNum = 6;

   let secondNum = 3;

   alert(firstNum * secondNum) // 18

 ```

 If either value is not a number, JavaScript converts it to a number using `Number()` function and performs the multiplication operation.

```
   let firstNum = '2';

   let secondNum = 6;

   alert(firstNum * secondNum) // 12


```

## 4. Division Operator
The symbol for Division operator in JavaScript of `(/)`. It divides the first value with the second value.

```
   let answer = 10/2;

   alert(answer) //5

```

If either value is not a number, JavaScript converts it to a number using `Number()` function and performs the division operation.

```
   let answer = 8/'2'

   alert(answer) //4

```

# OPERATOR PRECEDENCE

Operator precedence refers to the order in which operations are executed in an arithmetic expression.

Multiplication `(*)` and Division `(*)` have **higher precedence** than Addition `(+)` and Subtraction `(-)`


Which means in an expression, Multiplication and Division operations are executed first before Addition and Subtraction.

When parenthesis are found in an expression, expressions inside the parentheses are computed first.  


Where Multiplication and Division operators are involved (operators with the same precedence), they are computed from left to right.

