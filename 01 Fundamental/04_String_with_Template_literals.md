## STRING WITH TEMPLATE LITERALS 

Template literals makes it easy to work with string template.

Earlier, we learnt of wrapping strings with single quotes (`'`) and double quotes (`"`) but these provided a very limited functionality.

With the advent of ES6, strings can be wrapped with backticks (``\`) which allows for a cleaner and safer way of working with strings.

```
    let origin =   `I am from Nigeria.` 
```
This means:
 - We can have a string span multiple lines.
 - We can substitute parts of the string with values of variables or expressions.
 - We can safely include HTML in a string.

 If a string contains backtick, you have to escape it using a backlash `\`

 ```
    let message = `String template literals use \`, not double or single quotes.`
 ```


### Multiple line Strings

```
    let newMessage = 
    `With ES6, string manipulations
    became a lot easier with
    template literals.`

```


### Variables or Expression substitution

Like we earlier stated, template literal allows us substitute values of variables or expression directly into our strings.

To achieve this, we place tve variable name or expressions inside a code block as seen below.

```
    ${variableName}

    ${2 + 4}

```

```
    let firstName = 'Kelvin';
    let lastName = 'Ben';
    let age = 23;

    let intro = `Hello, I'm ${firstName} ${lastName}, I am ${age} years old.`

    alert(intro)

    //Hello, I'm Kelvin Ben, I am 23 years old.

```


```
    let unit_price = 20;

    let quantity = 100;

    let message = `You need the sum of ${unit_price * quantity} to purchase  100 units of the item`

    //You need the sum of $2000 to purchase 100 units of the item

```