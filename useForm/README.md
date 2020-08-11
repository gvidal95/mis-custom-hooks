# useForm

Ejemplo:

```
    const initialForm = {
        name: '',
        age: 10,
        email: ''
    };

    const [formValues, handleInputChange, reset] = useForm(initialForm);
```