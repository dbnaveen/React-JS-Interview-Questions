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
**2. componentDidUpdate()**
```
- When the value of any variables get updated. Mainly in the child component.
```
**3. componentWillUnmount()**
```
- When the component is removed.
```


#### FUNCTIONAL COMPONENTS (uses Hooks)
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
