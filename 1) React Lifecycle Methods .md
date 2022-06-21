### 🔸React Lifecycle Methods Using Class & Functional Components🔸

- Class components has methods.
- Functional components has hooks.

```
3 phases in React:
1. Mounting 
2. Updating 
3. Unmounting
```

**1. ComponentDidMount()**
```
- When component renders first
- It is used to call any API's and get the data
```
**2. ComponentDidUpdate()**
```
- When the value of any variables get updated. Mainly in the child component.
```
**3. ComponentWillUnmount()**
```
- When the component is removed.
```


#### FUNCTIONAL COMPONENTS (uses Hooks)
**(ComponentDidMount)**
```
useEffect(() => {

}, []);
```
**(ComponentDidUpdate)**
```
useEffect(() => {

}, [count]);
```
**(ComponentWillUnmount)**
```
useEffect(() => {
  return()=> {
  }
}, [count]);
```
