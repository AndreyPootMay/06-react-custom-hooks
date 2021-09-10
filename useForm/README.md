## useForm

Manage an form and the state of his input values and another attributes.

Example:

```js
    const initialForm = { // initialForm represent an form and his input values initial state.
        name: '',
        age: 0,
        email: ''
    };

    const [ formValues, handleInputChange, reset ] = useForm( initialForm );
```