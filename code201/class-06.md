[Home Page](https://devaoc.github.io/reading-notes/)

# Class 02 Notes

## Reading: Understanding the Problem Domain

The best way to make coding easier is by both:

- Making the problem domain easier
- Getting better at understanding the problem domain

Understanding the problem domain is a crucial part to coding as it can save you lots of time. Sitting down and taking the time to discuss what the point of the code is and how to implement it, is one such way.

## Javascript & JQuery

### Chapter 3: Object Literals

Objects group together a set of variables and functions in order to create a model. In an object, functions are known as methods and variables are known as properties. Literal notation is a way to create an object in Javascript. When creating an object you make a variable and you fill in information within curly braces. To access an object you use dot notation. Example of an object and dot notation:

``` Javascript

let hotel = {
  name: 'Willows Inn',
  rooms: 20,
  booked: 5,
  checkAvailability: function() {
    return this.rooms - this.booked;
  }
}
let hotelName = hotel.name;
let roomsFree = hotel.checkAvailability();

```

### Chapter 5: Document Object Model

