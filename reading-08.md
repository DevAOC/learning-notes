[Home Page](https://devaoc.github.io/reading-notes/)

# Reading Notes 08

## Read

### Expressions and Operators

Javascript has binary and unary operators with one exception of a ternary operator known as the conditional operator. A binary operator requires two operands. For example:

```Javascript

x = y;

```

A list of unary operators include:

- delete
- typeof
- void

The conditional operator is the only on with three operands. It is structured as follows:

condition ? val1 : val2

If the condition returns true, the first value is use and vise versa. For example:

```Javascript

let status = (age >= 18) ? 'adult' : 'minor';

```

If the age is equal to or greater than 18, the value that is assigned to the variable status is adult. If the age is lesser than 18, the value that is assigned to the variable status is minor. 

### Loops

Loops are used to run a segment of code multiple times without writing it more than once. A loop continues to execute until a stated condition is met. There are many avialable loops in Javascript. A list of loops include: 

- for
- do...while
- while
- labeled
- break
- continue
- for...in
- for...of

For detailed information on each loop, please [click here](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Loops_and_iteration#do...while_statement)