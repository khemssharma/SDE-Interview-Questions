# Common Frontend Theoritical Questions

## JavaScript

### What is a closure and what is a closure function?

A closure is when a function remembers variables from its outer (lexical) scope.
A closure function is a function that retains access to those outer-scope variables even after the outer function has finished executing.
This is possible because in JavaScript, variables are not garbage-collected as long as they are still referenced by a function."

---

### Callback Function
A callback function is a function that is passed as an argument to another function and is executed later, usually after an event or operation is completed.

---

### Handlers
Handlers are functions that are responsible for handling a specific event, request, or action.

---

### Events
Events are actions or occurrences triggered by user interactions or by the system, such as clicking a button, pressing a key, or loading a page.

---

### Hoisting in JavaScript
Hoisting is JavaScript’s behavior where variable and function declarations are moved to the top of their scope during compilation, allowing them to be accessed before their declaration.


## React.js Questions & Model Answers
- What are the main features of React?

"React is a component-based library for building user interfaces. Key features include virtual DOM for performance, reusable components, hooks for state and side-effect management, and unidirectional data flow for predictability."

- Difference between props and state?

"Props are external inputs to a component—immutable and set by the parent. State is internal, mutable, and used to manage a component’s local data and UI behavior."

- How does the virtual DOM work?

"React maintains a virtual DOM, which is a lightweight copy of the actual DOM. When state or props change, React updates the virtual DOM and efficiently syncs only the necessary differences to the real DOM using a diffing algorithm."

- What are hooks?

"Hooks are functions like useState and useEffect that let you manage component state and lifecycle directly in functional components, removing the need for class components."

- Explain “lifting state up”.

"Lifting state up means moving shared state to a common ancestor component so multiple child components can access and modify it. This keeps data flow predictable and organized."

## Next.js Questions & Model Answers

- Advantages over plain React?

"Next.js adds features like server-side rendering, static site generation, built-in routing, image optimization, and API routes. This improves SEO, performance, and developer efficiency."

- SSR vs SSG?

"SSR (Server-side Rendering) generates pages on each request, ideal for dynamic data. SSG (Static Site Generation) pre-builds pages at build time for fast load times, perfect for static content."

- How do API routes work in Next.js?

"API routes are serverless functions you can create in the /pages/api folder. They handle backend logic like data fetching, authentication, and act as endpoints within the same codebase."

- How do you deploy a Next.js app?

"Next.js apps can be deployed to platforms like Vercel, Netlify, or any server that supports Node.js. Tools like Vercel automate static generation and serverless deployment."

## Redux Questions & Model Answers

- What is Redux and why use it?

"Redux is a state management library for predictable state updates using actions and reducers. It centralizes state, facilitates debugging, and helps manage complex app flows."

- Redux data flow?

"Data flows from a component dispatching an action → reducer processes it → store updates → UI re-renders based on the new store state."

- Redux Toolkit benefits?

"Redux Toolkit simplifies Redux setup by providing utilities for reducers, actions, and async logic. It reduces boilerplate and promotes best practices."

- Redux vs Context API?

"Redux is best for large-scale state management with advanced tooling and middleware. Context API suits simple, limited global state but may cause performance issues for frequent updates."

## Very Basic Web Dev Questions

- What are semantic HTML elements, and why are they important?

- Explain relative, absolute, and fixed positioning in CSS.

- What’s the difference between visibility: hidden and display: none?

- How do media queries work in CSS?
