# DATA TYPES AND ITS USES

The content of a variable, which we refer to as value or data is always of a certain type. e.g Number or string.

The variable that stores data is not affected by the data type. 
This is to say, one variable used to store a string can be used to store a Number another moment.

```
    let content = "Welcome";

    content = 1234567890;
```
The above code will not throw any error because JavaScript is a `dynamically typed` programming language.


## There are 8 data types in JavaScript.

## 1. Number

```
    let age = 30

    let x = 37.5

```
The Number type refers to both integers and floating point numbers.

## 2. BigInt  
The bigInt type is used to store numbers too big to be represented in the Number type.

JavaScript numbers are stored in 64-bit floating point format, this means that larger numbers cannot be stored exactly hence rounded off.
Numbers higher than  `9007199254740991` or lower than `-9007199254740991` can only be stored with bigInt.

A bigInt value is created by appending `n` at the end of an integer.


```
    const bigNum = 1234567890123456789012345678901234567890n

```

## 3. String

A string in JavaScript is zero or more characters enclosed in a single or double quote.

```
    let fName  = 'Cindy';
    let lName = "Kelvin";

```

If you start with a single quote, ensure to close with a single quote as well, same with double quote

Strings can have a quote inside them as long as it doesn't match the enclosing quotes.

```
    let message = 'I am coming with the "bag"';
```
If you want to use a single quote in a string, you have to escape it with a backslash.

```
    let fName = ' it\'s Queen';
```

## 4. Boolean

Boolean type has two values: true or false;
They are used to store a *Yes* or *No* values.

```
    let isMarried = true;
    let isSingle = false;
```

## 5. Null 
The Null type has only one value `null`. It is a special value that means *nothing* or *unknown*.

```
    let lName = null;

```

The above simply means the value of `fName` is unknown.

## 6. Undefined
 The `undefined` is a special value on it's own. 
 If a variable is declared, but no value was assigned, then it's type is `undefined`.

```
    let date;

    alert(date); // returns 'undefined' 
```

## 7. Object 

An object is a collection of properties, where each property is defined by a key-value pair.

An object is defined by `{}`

```
    let person = {
        firstName: 'Cindy',
        lastName: 'Kelvin',
    }

```

The person object has  properties *firstName* and *lastName*.

The property of an object can be another object.

To access an object's property, you can use 

- The dot `.` notation or
- The bracket `[]` notation

Example:

```
    alert(person.firstName);

    alert(person['lastName'])

```

## 8. Symbol

The `Symbol` type creates a unique value every time it is called.

To create a `Symbol`, you call the symbol function as shown below.

```
    let q = Symbol();
```
