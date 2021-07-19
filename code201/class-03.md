[Home Page](https://devaoc.github.io/reading-notes/)

# Class 03 Notes

## HTML & CSS

### Chapter 3: Lists

We already know about the <ul> and <ol> lits tags but there are also <dl>. In a <dl> tag there are two other tags. <dl> is adefinition list with <dt> as the terms being defined and <dd> as the definition of the term above.

You can make nested lists using both <ul> and <ol> with <li> in them. Example:

``` HTML

<ul>
  <li>Toast</li>
  <li>Banana</li>
  <ul>
    <li>Brown</li>
    <li>Green</li>
  </ul>
  <li>Milk</li>
</ul>

```

### Chapter 13: Boxes

This section has good tools for making borders and modifying text within a box.

## Javascript & JQuery

### Chapter 4: Decisions and Loops

The switch statement is a statement that can be used instead of an if or if/else. The switch statment has an expression and is followed by cases. Whatever case the expression corresponds to will be run. Example:

``` Javascript

switch (resp === answer) {
    case true:
      alert('Awesome! You answered correctly!');
      break;
    default:
      alert('Sorry, you answered incorrectly.');
      break;
  }

```
