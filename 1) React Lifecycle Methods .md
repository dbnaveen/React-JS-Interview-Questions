### 🔸React Lifecycle Methods Using Class & Functional Components🔸

- Class components has methods.
- Functional components has hooks.

```
3 phases in React:
1. Mounting 
2. Updating 
3. Unmounting
```

**1. componentDidMount()**
```
- When component renders first time
- It is used to call any API's and get the data
```

**2. shouldComponentUpdate()**
```diff
- This returns a boolean value which specifies whether the React should continue with the rendering or not.
- By default the value is true.
- If it is set to false, the component will not continue to update any state value.
- If it is false, the render(), componentWillUpdate(), componentDidUpdate() will not be called.
```
https://codesandbox.io/s/broken-rain-734lip?file=/src/App.js

https://codesandbox.io/s/vigilant-yalow-3ejdsk?file=/src/App.js



**3. componentDidUpdate()**
```diff
- When the value of any variables get updated. Mainly in the child component.
```
**4. componentWillUnmount()**
```
- When the component is removed.
```


## FUNCTIONAL COMPONENTS (uses Hooks)
**(componentDidMount)**
```
useEffect(() => {

}, []);
```
**(componentDidUpdate)**
```
useEffect(() => {

}, [count]);
```
**(componentWillUnmount)**
```
useEffect(() => {
  return()=> {
  }
}, [count]);
```
