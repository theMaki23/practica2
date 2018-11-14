# Buscar alumnos

**ID**: 3

**Breve descripcion**: El sistema busca un alumno por su DNI, su primer apellido o grupo.

**Actores principales**: Profesor.

**Actores secundarios**: Alumnos.

**Precondiciones**: 

1. El alumno debe de estar insertado previamente en la base de datos.
2. En el caso de buscar por grupo, dicho grupo debe de existir previamente.

**Flujo principal**:

1. El caso de uso comienza cuando el sistema quiere buscar un alumno o varios en especifico.
2. El sistema localiza el alumno/s mediante su DNI, apellido y grupo.

**Postcondiciones**:

- El sistema muestra los datos de el alumno o los alumnos que se indique.

**Flujos alternativos**:

1.a. Si los datos no son introducidos incorrectamente se mostrar� un "ERROR" por pantalla y se volveran a pedir.

2.a. Si el DNI o apellido no corresponde a ningun alumno se mostrara por pantalla "Alumno no existe".

3.a. Si el grupo introducido no corresponde a ninguno se mostrara "Grupo no existe".

3.b. Si el apellido se repite 1 o mas veces, se pedir� al usuario que introduzca el DNI.
