[Home Page](https://devaoc.github.io/reading-notes/)

# Class 05 Notes

## React Docs - Thinking in React

To break a mock into component hierarchy you'd first have to draw boxes around all the components. You would do this by using the single responsibility principle. This means deciding what section has one job. Components often do one thing so this principle is good for this kind of code block.

Building a static version of your application means to build an app with no interactivity and no state. After you have a static verison you need to identify the minimal representation of UI state.

The three questions you can ask to determine if something is state are:

- Is it passed in from a parent via props? If so, it probably isn’t state.
- Does it remain unchanged over time? If so, it probably isn’t state.
- Can you compute it based on any other state or props in your component? If so, it isn’t state.

You can identify where state needs to live by:

- Identify every component that renders something based on that state.
- Find a common owner component (a single component above all the components that need the state in the hierarchy).
- Either the common owner or another component higher up in the hierarchy should own the state.
- If you can’t find a component where it makes sense to own the state, create a new component solely for holding the state and add it somewhere in the hierarchy above the common owner component.

## Things I want to know more about
