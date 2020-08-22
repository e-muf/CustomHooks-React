# useForm Hook

Ejemplo:
``` language='javascript'
    const initialForm = {
        name: '',
        age: 22,
        email: ''
    }

    const [ formValues, handleInputChange, reset ] = useForm( initialForm );
```