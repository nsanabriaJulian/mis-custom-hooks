# useForm

Ejemplo:
```javascript

    const initialForm = {
        name: '',
        age: 0,
        email: ''
    };

    const [ formValues, handleInputChange, reset] = useForm( initialForm );
```
    regresa un arreglo [] (array).