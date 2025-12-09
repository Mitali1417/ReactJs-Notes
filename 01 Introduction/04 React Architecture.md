# React Architecture - Overview and Interview Questions

## React Architecture

React follows a component-based architecture and uses a unidirectional data flow. It is designed to efficiently update and render UI components by leveraging the Virtual DOM.

### 1. Key Components of React Architecture

#### a) Components

* **Functional Components:** Stateless components defined as JavaScript functions.
* **Class Components:** Components that can hold and manage state using `this.state` and lifecycle methods.

#### b) JSX

JSX (JavaScript XML) allows combining HTML-like syntax with JavaScript logic to define UI elements within components.

#### c) Virtual DOM

A lightweight copy of the real DOM that React uses to determine which parts of the UI need updating. It improves performance by minimizing direct DOM manipulation.

#### d) One-Way Data Binding (Unidirectional Data Flow)

Data flows in one direction, from parent to child components. This makes the application predictable and easier to debug.

#### e) State and Props

* **State:** Internal data of a component that can change over time.
* **Props:** Read-only data passed from parent to child components.

#### f) Lifecycle Methods

Methods available in class components to hook into different phases of a component’s life:

* `componentDidMount`
* `componentDidUpdate`
* `componentWillUnmount`

#### g) React Fiber (Reconciliation Algorithm)

React Fiber is the engine behind React's rendering process. It allows incremental rendering and improves responsiveness by splitting work into units.

#### h) React Hooks

Hooks allow functional components to manage state and lifecycle methods:

* `useState` - manages state
* `useEffect` - side effects
* `useContext` - context API access
* `useReducer` - complex state management

---

## Important Interview Questions with Answers

### 1. What is the architecture of React?

**Answer:** React uses a component-based architecture with unidirectional data flow, Virtual DOM, JSX, and lifecycle methods to efficiently manage UI updates.

### 2. What is the Virtual DOM and why is it used?

**Answer:** The Virtual DOM is a lightweight copy of the real DOM. It is used to optimize rendering by updating only the components that have changed.

### 3. What is React Fiber?

**Answer:** React Fiber is the internal reconciliation engine that improves rendering performance and allows incremental updates to the UI.

### 4. What is the difference between state and props?

**Answer:**

* **State:** Mutable, managed internally within a component.
* **Props:** Immutable, passed from parent to child.

### 5. What are React lifecycle methods?

**Answer:** Lifecycle methods are hooks in class components that allow developers to execute code at specific points in a component’s life, such as mounting, updating, or unmounting.

### 6. What is unidirectional data flow?

**Answer:** Data flows from parent components to child components, ensuring predictable state changes and easier debugging.

### 7. How do hooks fit into React architecture?

**Answer:** Hooks provide functional components with the ability to manage state, side effects, and access context, replacing most class component use cases.

### 8. How does React handle rendering?

**Answer:** React uses the Virtual DOM and React Fiber to efficiently update only the components that need changes, improving performance.

### 9. What is JSX and why is it used?

**Answer:** JSX is a syntax extension that allows writing HTML-like code inside JavaScript. It makes code more readable and easier to write.

### 10. Why is React considered modular?

**Answer:** React encourages building reusable components that can be composed to create complex UIs, promoting modularity and maintainability.

---

*This document provides an overview of React architecture and commonly asked interview questions.*
