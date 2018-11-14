# Modificar alumno

**ID**: 4

**Breve descripcion**: El sistema modifica los datos de un alumno por su DNI o por su primer apellido que introducira por pantalla el usuario.

**Actores principales**: Profesor.

**Actores secundarios**: Alumnos.

**Precondiciones**: 

1. El alumno debe de existir previamente.
2. El DNI introducido debe de estar compuesto por 8 numeros naturales.
3. El primer apellido debe de estar compuesto por una cadena de caracteres sin numeros.
4. Si modificamos el atributo lider a  1 (lider), no puede existir otro lider en el mismo grupo previamente.

**Flujo principal**:

1. El caso de uso comienza cuando el sistema quiere modificar los datos de un alumno.
2. El sistema localiza el alumno mediante su DNI o apellido.

**Postcondiciones**:

- El sistema vuelve a pedir al usuario que inserte los atributos del alumno que se indique.

**Flujos alternativos**:

1.a. Si los datos no son introducidos incorrectamente se mostrara un "ERROR" por pantalla y se volveran a pedir.

2.b. Si el DNI o apellido no corresponde a ningun alumno el sistema mostrar por pantalla, "Alumno no existe".

3.b. Si el apellido se repite 1 o mas veces, se pedirá al usuario que introduzca el DNI.

4.a Si al cambiar el atributo lider a 1 (lider) tenemos dos lideres en un mismo grupo el sistema imprimira por pantalla, "ERROR, no puede haber mas de un lider por grupo, debe de modificar antes el alumno lider de este grupo"
