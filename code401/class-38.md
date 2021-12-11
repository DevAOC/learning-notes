[Home Page](https://devaoc.github.io/reading-notes/)

# Class 38 Notes

## Review, Research, and Discussion

1. Reducers should be as granular as needed. The reducer should pertain to only a small set of state each. I personally would make a file for each action/state.
2. I believe that it could be a problem for multiple reducers to fire at once. It could modify or rerender components that you dont want rerendered. On the other hand, it could be beneficial when needed. (Make sure to name functions and variables appropriately)
3. A strategy for preventing that multiple reducers are called at once is to name functions and variables very carefully.

## Terms

- Store: A combination of multiple states. This is achieved with Redux.
- Combined Reducers: An object that holds all the reducer funcitons.
