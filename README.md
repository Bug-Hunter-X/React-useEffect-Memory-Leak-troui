# React useEffect Memory Leak Bug

This repository demonstrates a common bug in React applications involving the `useEffect` hook.  The `BuggyComponent.js` file shows an example of how neglecting a cleanup function within `useEffect` can lead to memory leaks. The `FixedComponent.js` file presents a corrected version.

## How to Reproduce

1. Clone this repository.
2. Navigate to the project directory.
3. Run `npm install`.
4. Run `npm start`.
5. Observe the behavior of the buggy component and compare it to the fixed component. You may want to use your browser's developer tools to monitor network requests.