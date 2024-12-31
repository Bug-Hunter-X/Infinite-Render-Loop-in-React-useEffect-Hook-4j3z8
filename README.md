# Infinite Render Loop in React useEffect Hook

This repository demonstrates a common error in React applications: an infinite render loop caused by a missing dependency in the `useEffect` hook.  The `useEffect` hook, while powerful, requires careful management of its dependency array to prevent unintended re-renders.

## The Bug

The `bug.js` file contains a React component that unintentionally creates an infinite render loop.  Can you spot the error?