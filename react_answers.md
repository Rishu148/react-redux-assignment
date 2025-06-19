
## Question 1: What is the purpose of the return statement in a React component?

The `return` statement in a React component defines what will be shown on the screen. It usually returns JSX, which looks like HTML. React uses this to display the UI. Without a return, the component won't render anything.

---

## Question 2: What is an event handler in React, and how do you add one to a button?

An event handler is a function that responds to user actions like clicks. In React, we use props like `onClick` to add them. Example:

```jsx
<button onClick={handleClick}>Click Me</button>
```

---

## Question 3: What does the key prop do when rendering a list of elements in React?

The `key` prop helps React identify items in a list. It improves performance and ensures correct rendering. Each item in a list should have a unique key, like an ID.

---

## Question 4: What is the difference between state and props in React?

`State` is local data managed by the component and can change. `Props` are values passed from parent to child and are read-only. State is used for internal logic, props are used to communicate between components.

---

## Question 5: What is the useEffect Hook, and when might you use it in a component?

The `useEffect` Hook is used for side effects like fetching data, setting timers, or updating the DOM. It runs after the component renders. You can also clean up resources inside it using a return function.
