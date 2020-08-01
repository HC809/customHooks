# useForm Hook

Ejemplo:

const initialForm = {
    nombre = 'Hector',
    apellido = 'Caballero',
    edad: 25,
    email: 'caballero.22.809@gmail.com'
}
const [ formValues, handleInputChange, reset ]= useForm(initialForm);