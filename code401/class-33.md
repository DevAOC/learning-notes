[Home Page](https://devaoc.github.io/reading-notes/)

# Class 33 Notes

## Review, Research, and Discussion

1. Context API gives you a way to pass global data to children components without having to manually pass down props through every component.
2. A component outside of a provider can consume the context using the useContext() hook.
3. You could use it to create a dark mode or light mode. It can also be useful for authentication/authorization.
4. Context hell is when you nest providers and make them children of each other.

## Terms

- Global State: Data that all components share.
- Global Context: A way to share global state to all components without passing down props.
- Provider: Allows consuming components to subscribe to context changes.
- Consumer: A React component that subscribes to context changes.
