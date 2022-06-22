# Pure Components


- One way to create a class component is by extending the component class
- There is a second way to create a class component. This is by extending the pur component class.


#### Difference

- Whenever the parent component get updated, the component class gets re-rendered.
- Whenever the parent component get updated, the Pure component class doesn't get re-rendered.
- A Pure component implements **shouldComponentUpdate** with a shallow props and state comparison.
- A Pure component will be called only if there is a change in the prevProps and curProps or prevState and curState

```
Pure component is used to prevent un-necessary renders of the component.
```

https://codesandbox.io/s/pure-component-rkhcn9?file=/src/components/ParentComp.js
