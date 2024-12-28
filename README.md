# React + Vite

In this project, I had learned about useState, useEffect, useCallback and useRef.

1. useState is a React Hook that lets you add a state variable to your component.
   const [state, setState] = useState(initialState).

2. useEffect is a React Hook that lets you synchronize a component with an external system.
   Synchronizing with Effects: Some components need to synchronize with external systems. For example, you might want to control a non-React component based on the React state, set up a server connection, or send                                  an analytics log when a component appears on the screen. Effects let you run some code after rendering so that you can synchronize your component with some system outside of React.
   useEffect(setup, dependencies?).

3. useCallback is a React Hook that lets you cache a function definition between re-renders.
   const cachedFn = useCallback(fn, dependencies).

4. useRef is a React Hook that lets you reference a value that’s not needed for rendering.
   const ref = useRef(initialValue).
