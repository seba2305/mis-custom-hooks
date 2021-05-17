# useForm Hook

Ejemplo de uso:
```
    const initialForm = {
        name: 'John Doe',
        age: 20,
        email: 'jdoe@example.com'
    };
    
    const [formValues, handleInputChange, reset] = useForm(initialForm);
        
```