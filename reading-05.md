[Home Page](https://devaoc.github.io/reading-notes/)

# Reading Notes 05

## Read

### What is CSS

CSS stands for Cascading Style Sheet. It is what allows you to modify the look of the webpages you create in HTML. CSS uses selectors such as class and id to allow you to target specific points in your HTML code.

#### CSS Syntax

CSS syntax opens with a selector (h1, section, article, etc) followed by {...} which encases arguments. The arguments encased within the {} are what modify the look and feel of the page. There are many arguments ranging from color to animations!

A class selector is always written using a period (.) character between the tag and class name. Also, an id selector is written similarly with a hash (#) character between the tag and the id name. For example:

```CSS

h1.class-name-example {
    color: blue;
}
h2#id-name-example {
    color: red;
}

```

These are specific to making a change to the content of h1 or h2 tag with their respective class or id. For example:

```HTML

<h1 class="class-name-example">
    ...
</h1>
<h2 id="id-name-example">
    ...
</h2>

```

There are many more selectors to choose from. To learn more about selectors [click here.](https://developer.mozilla.org/en-US/docs/Learn/CSS/Building_blocks/Selectors)

## Reading & Expirement

### How to Add CSS

There are only three was to add CSS to your HTML code. These are:

- External CSS (A file in the same or near directory of your HTML, referenced by using a `link` tag and specifying a path)

```HTML

<link rel="stylesheet" href="mystyle.css">

```

- Internal CSS (A style section written within your HTML file)

```HTML

<style>
    body {
        background-color: linen;
    }
    h1 {
        color: maroon;
        margin-left: 40px;
    }
</style>

```

- Inline CSS (CSS that is written in the tag declaration)

```HTML

<p style="color: purple; font-size: 12px; text-align: center;">Fubar: Fucked up beyond all recognition</p>

```

The most optimal way to include CSS on your webpages is to use an external file. Although internal CSS may be the same as your external file, it makes the HTML sloppy or hard to read. It is generally viewed as bad practice. Inline CSS should never be used on a finished product. It is generally used to track or quickly view what a certain line of CSS would do to your page.

CSS will apply styles by priority in a cascading manner. This means that the most priority goes by inline CSS as the most priority, to external and internal stylesheets, and finally the web browser defaults. In other words, what is written last is what will be displayed. 

### CSS Color

There are many types of color arguments you can use in CSS. For example:

- HEX or hexidecimal values

```CSS

body {
    color: #92a8d1;
}

```

- RGB or red, green, blue values

```CSS

body {
    color: rgb(201, 76, 76);
}

```

- RGBA or red, green, blue, opacity values

```CSS

body {
    color: rgba(201, 76, 76, 0.6);
}

```

- HSL or hue, saturation, lightness values

```CSS

body {
    color: hsl(89, 43%, 51%);
}

```

- HSLA or hue, saturation, lightness, opacity values

```CSS

body {
    color: hsla(89, 43%, 51%, 0.6);
}

```

All are valid ways of displaying a color in CSS.

## Skim

### CSS Reference

This is a reference for all the CSS rules and arguments: [https://developer.mozilla.org/en-US/docs/Web/CSS/Reference](https://developer.mozilla.org/en-US/docs/Web/CSS/Reference)

### Myers Web Reset Stylesheet

This is a basic browser reset available on [https://meyerweb.com/eric/tools/css/reset/](https://meyerweb.com/eric/tools/css/reset/)