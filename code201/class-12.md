[Home Page](https://devaoc.github.io/reading-notes/)

# Class 12 Notes

Charts are the best way to display data visualy.

To use Chart.js you first need to download and unzip the files into the directory where you are working. You must then import the script into your html page. We need to also create a canvas element where the chart will be created.

Charts are simple to use and easy to master, making Chart.js a good tool for data representation.

The canvas element only has two attributes:

- Width
- Height

The chart itself cannot be modified using CSS but the canvas element does act like any other element. This means you can make a border and change the color, etc.

To put information within the chart you must first access a rendering context. Example:

``` Javascript

const canvas = document.getElementById('tutorial');
const ctx = canvas.getContext('2d');

```

