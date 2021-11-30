[Home Page](https://devaoc.github.io/reading-notes/)

# Class 28 Notes

## Review, Research, and Discussion

1. We don't need multiple html pages in a React app because a React app has conditional redering. It will only render what is required. In multiple page apps, each page is a seperate file. In React we render components which are loaded at the beginning of using the app.
2. We can conditionally render anywhere within a React app. If we want something to appear on every page, all we need to do is have it as one of the top level children of the app.
3. When a new route is requested the components dismount from the page and a new component mounts.
4. Props.children refers to non-specified children of the component that it is being used in.
5. The diffrence between useState() and this.setState() is the type of component that it is being used with and what exactly happens behind the scenes with React.

## Terms

- State Hook: This is a way to access state from a parent while in a child of that parent.
- Mounting and Un-Mounting: This is when a component is first put on to the page and when it is removed.
