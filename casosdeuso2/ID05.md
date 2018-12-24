# Borrar alumno

**ID**: 5

**Breve descripcion**: El sistema borra un alumno por su DNI o por su primer apellido que introducira por pantalla el usuario.

**Actores principales**: Profesor.

**Actores secundarios**: Alumnos.

**Precondiciones**: 

1. El alumno debe de existir previamente.
2. El DNI introducido debe de estar compuesto por 8 numeros naturales.
3. El primer apellido debe de estar compuesto por una cadena de caracteres sin numeros.

**Flujo principal**:

1. El caso de uso comienza cuando el sistema quiere borrar un alumno.
2. El sistema localiza el alumno mediante su DNI o apellido.

**Postcondiciones**:

- El sistema borra al alumno que se indique.

**Flujos alternativos**:


1.a. Si el DNI o apellido no corresponde a ningun alumno se mostrara por pantalla "Alumno no existe".

2.b. Si el apellido se repite 1 o mas veces, se pedirá al usuario que introduzca el DNI.
