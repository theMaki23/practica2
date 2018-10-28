# Buscar alumno

**ID**: 3

**Breve descripcion**: El sistema busca un alumno por su DNI o su primer apellido.

**Actores principales**: Profesor.

**Actores secundarios**: Alumnos.

**Precondiciones**: 

1. El alumno debe de estar insertado previamente en la base de datos.
2. El DNI introducido debera de ser una cadena de 8 caracteres numericos y el primer apellido una cadena de caracteres no numericos.

**Flujo principal**:

1. El caso de uso comienza cuando el sistema quiere buscar un alumno en especifico.
2. El sistema localiza el alumno mediante su DNI o apellido.

**Postcondiciones**:

- El sistema muestra los datos de el alumno que se indique.

**Flujos alternativos**:

1.a. Si los datos no son introducidos incorrectamente se mostrará un "ERROR" por pantalla y se volveran a pedir.

2.a. Si el DNI o apellido no corresponde a ningun alumno se mostrara por pantalla "Alumno no existe".

3.b. Si el apellido se repite 1 o mas veces, se pedirá al usuario que introduzca el DNI.
