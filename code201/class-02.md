[Home Page](https://devaoc.github.io/reading-notes/)

# Class 02 Notes

## HTML & CSS

### Chapter 2: Text

In HTML there are a list of tags that are used to aid in writing text. These tags can help bold, italicize, add line breaks or white spaces, and even add quotation marks. Just one example:

``` HTML

<q>I like dogs<q>

```

### Chapter 10: Introducting CSS

CSS is used to style a webpage. It is liked to an HTML page and modifies the page's elements with colors, placement, size, etc. A segment of CSS would look like this:

``` CSS

p {
  font-family: Arial;
}

```

You can also modify multiple elements at once.

``` CSS

h1, h2, h3 {
  font-family: Arial;
  color: yellow;
}

```

These segments were taken from the Jon Duckett textbook.

## Javascript & JQuery

### Chapter 2: Basic Javascript Instructions

In Javascript, you make functions, methods, and variables in order to make an HTML page act a certain way. Variables are made by using var, const, or let and assigning a name and a variable to that name. Variables can consist of strings, numbers, arrays, and boolean values. For example:

``` Javascript

let example1 = 1;
let example2 = "This is just an example";
let example3 = [1, 2, 3]
let example4 = true;

```

There are many more examples of operators that you can use to assign a variable in the Javascript & JQuery book.

### Chapter 4: Decisions and Loops

A loop is a series of repeating steps that continue to run as long as a condition is true. It will exit the loop as soon as it becomes false. The code within the loop is what gets executed. For example:

``` Javascript

if (score > 50) {
  document.write('You passed!');
} else {
  document.write('Try again...');
}

```

This code snippet is from the Javascript & JQuery book.