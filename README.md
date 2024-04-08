# Exercise: Passing Props in React

## Objective

To practice passing props from a parent component to a child component in React.

## Instructions

1. Use Vite to create a new ReactJS application.
2. Inside the application directory > src, create a folder named `components`.
3. Inside the `components` folder, create two components:
   - **ParentComponent.jsx**: This component will contain a state variable called `message` with the value `"Hello, world!"`. Render a `ChildComponent` inside `ParentComponent` and pass the `message` as a prop to it.
   - **ChildComponent.jsx**: This component will receive a prop called `message` and render it inside a `<p>` tag.
4. In `App.js`, import and use the `ParentComponent`.

## Challenge

Modify the `ChildComponent` to render the `message` prop conditionally. If the `message` prop is `"Hello, world!"`, render it inside a `<p>` tag with a class of `greeting`. If it's any other message, render it inside a `<p>` tag with a class of `default-message`.
