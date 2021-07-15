[Home Page](https://devaoc.github.io/reading-notes/)

# Class 02 Notes

## HTML & CSS

### Chapter 4: Links

Links are always found in an <a> tag. Links can be internal or external. Example:

``` HTML

 <a href="https://devaoc.github.io/restaurant-flora/">Flora</a>

```

There are two properties you can use when making a link. These are:

#### target

When trying to open a new page. (Attribute _blank)

#### mailto:

A link for email addresses. This is put within the href.

### Chapter 15: Layout

In CSS, HTML elements act as a box. They can either be block level elements or inline. Block being on its own line and inline being surrounded by other elements. If there are multiple block level elements within each other, the top level block element is known as the container.

#### Positioning Schemes

- Normal flow
- Relative Positioning
- Absolute Positioning
- Fixed Positioning
- Floating Elements

z-index helps you control which box is on top when elements are overlapping.

## Javascript & JQuery

### Chapter 3: Functions, Methods, and Objects

You make a function by using the function keyword and then naming it with parentheses. Within the parentheses you can declare parameters. Example:

``` Javascript

function helloWorld() {
  document.write('Hello, World!');
}

```

Calling a function doesn't require much code:

``` Javascript

helloWorld();

```

You can return values from a function by using the keyword return. You can return multiple values by returning an array.