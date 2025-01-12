# React useEffect Hook with Incorrect Dependency Array

This example demonstrates a common mistake when using the `useEffect` hook in React.  The `useEffect` hook is intended to perform side effects based on changes to state or props. However, if the dependency array is empty (`[]`), the effect only runs once after the initial render. 

The provided code demonstrates this by logging the count value. The expectation is that the count will be logged each time the count updates. However, the code only prints it once on the initial render.