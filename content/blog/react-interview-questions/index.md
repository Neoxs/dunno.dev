---
title: React Interview Questions
date: "2022-08-18T22:40:32.169Z"
description: Commen react interview questions that you should absolutry know.
---

There are many articles written about React inteview questions. In general, Here is some of the most repetetive ones:

### what are props in react ?
[Props](https://reactjs.org/docs/components-and-props.html) are read-only components (immutable variables) that stores values and it gives a way to pass data from one component to another.

### what are react hooks ?
[Hooks](https://reactjs.org/docs/hooks-intro.html) are a new addition in React 16.8. They let you use React [state and lifecycle](https://reactjs.org/docs/state-and-lifecycle.html) methods without writing a class.<br>
which makes React so much better because you have simpler code that implements similar functionalities faster and more effectively.

### what is useMemo ?
[useMemo](https://reactjs.org/docs/hooks-reference.html#usememo) is a react hook that can help to optimise the performance of an application by “remembering” the result of an expensive functions based on the given parameters in order to preventing an unnecessary re-render every time there is a change in the application.

### useMemo vs useCallback ?
<b>[useCallback](https://reactjs.org/docs/hooks-reference.html#usecallback)</b> returns its function uncalled so you can call it later, while <b>useMemo</b> calls its function and returns the result.

### what is useRef ?
The [useRef](https://reactjs.org/docs/hooks-reference.html#useref) Hook return a mutable object that does not cause a re-render when updated.

### what is useEffect ?
The [useEffect](https://reactjs.org/docs/hooks-reference.html#useref) Hook allows you to perform side effects in your components. Basically it replaces the old React class lifecycle methods ([componentDidMount](https://reactjs.org/docs/react-component.html#componentdidmount), [componentDidUpdate](https://reactjs.org/docs/react-component.html#componentdidupdate), and [componentWillUnmount](https://reactjs.org/docs/react-component.html#componentwillunmount) combined.) 

### what are promises in javascript ?
A promise is <b>an object that may produce a single value some time in the future : either a resolved value, or a reason that it's not resolved</b> (e.g., a network error occurred). A promise may be in one of 3 possible states: <b>fulfilled</b>, <b>rejected</b>, or <b>pending</b>.

### what is the diffrence between localStorage and sessionStorage ?
The difference between localStorage and sessionStorage is that <b>localStorage data does not expire, whereas sessionStorage data is cleared when the page session ends.</b>

### what are custom hooks ?
[Custom Hook](https://reactjs.org/docs/hooks-custom.html) is a JavaScript function which we create by ourselves, when we want to extract component logic into reusable functions in order to share it between other components. It allows you to reuse some piece of code in several parts of your app.

### what are Higher Order Components ?
A [higher-order component (HOC)](https://reactjs.org/docs/higher-order-components.html) is an advanced technique in React for reusing component logic. Concretely, <b>a higher-order component is a function that takes a component and returns a new component.</b>

### what is MVP ?
A minimum viable product, or MVP, is a product with enough features to attract early-adopter customers and validate a product idea early in the product development cycle.

### what is conditional rendering in react ?
[Conditional rendering](https://reactjs.org/docs/conditional-rendering.html) in React works the same way conditions work in JavaScript. Use JavaScript operators like <b>if</b> or the <b>conditional operator &&</b> to update UI elements based on the current state of the component.

### what is the difference between inline if and && operator in conditional rendering ?
There's no significant performance difference.

### what are cookies and what are used for ?
Cookies are small text files that a web server generates and sends to a web browser.
It can be very useful to save piece of information about the user or a specific request that was done earlier.

### what are function as child component (as child pattern) ?
A [Function as Child Component (or FaCC)](https://reactpatterns.js.org/docs/function-as-child-component/) is a pattern that lets you you pass a render function to a component as the children prop.

### what is a callback function ?
A callback function is a function passed into another function as an argument, which is then invoked inside the outer function to complete some kind of routine or action.