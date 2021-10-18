[Home Page](https://devaoc.github.io/reading-notes/)

# Class 01 Notes

## Map

Array.map() is an array method that helps to loop through an array. You write an imbeded function with the array element as a parameter. You can then do work and return anything to a new array if desired.

## Reduce

Array.reduce() is an array method that helps you modify an existing array. The return value is the sum of that modification.

## Superagent

### .then

```javascript
const getCharacters = () => {
  superagent
    .get("https://swapi.dev/api/people/1/")
    .then((data) => {
      const key = data.body.name;
      const object = {};
      object[key] = data.body.url;
      console.log(object);
    })
    .catch((err) => console.error(err));
};
```

### Async/Await

```javascript
const cityGetter = async (cityName) => {
  try {
    const info = await superagent.get(`https://geocode.xyz/${cityName}?json=1`);
    console.log(`Longitude: ${info.body.longt}, Lattitude: ${info.body.latt}`);
  } catch {
    console.error(err);
  }
};
```

## Promises

Promises are a promised return; either positive or negative (values and information or an error/rejection). It is used in asynchronous functions to make sure that when the function is done running, that we dont have a code breaking return.

Callbacks are not all viewed as asynchronous. They can do work on the side of other code or can be run after the stack is complete.
