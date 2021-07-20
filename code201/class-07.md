[Home Page](https://devaoc.github.io/reading-notes/)

# Class 07 Notes

## Reading: Domain Modeling

This is the act of creating a conceptual model designed for specific problems in code. One such model that encapsulates data, properties, and methods is called an object-oriented model. To define the same propereties across multiple objects we need to use something called a constructor function. An example of a constructor function:

``` Javascript

conts EpicFailVideo = function(epicRating, hasAnimals) {
  this.epicRating = epicRating;
  this.hasAnimals = hasAnimals;
}

const parkourFail = new EpicFailVideo(7, false);
const corgiFail = new EpicFailVideo(4, true);

console.log(parkourFail);
console.log(corgiFail);

```

To make new objects, use the *new* keyword.

The code blocks above are taken from the reading link. More information can be found [here](https://github.com/codefellows/domain_modeling#domain-modeling).

## HTML & CSS

### Chapter 6: Tables

To create a table you must use the **<table>** element. The tag <tr> stands for table row and <td> for table data. You may create a header by using the tag <th> and using the *scope* attribute you can set the headers for each row or column. Example:

``` HTML

<table>
  <tr>
    <th></th>
    <th scope="col">Saturday</th>
    <th scope="col">Sunday</th>
  </tr>
  <tr>
    <th scope="row">Tickets sold:</th>
    <td>120</td>
    <td>135</td>
  </tr>
  <tr>
    <th scope="row">Total sales:</th>
    <td>$600</td>
    <td>$675</td>
  </tr>

```

This code is taken from the book.

## Javascript & JQuery

### Chapter 3: Functions, Methods, and Objects

