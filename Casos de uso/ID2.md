# Mostrar Alumno

**ID**: 2

**Breve descripcion**: Muestra los datos ordenados por nombre y apellido, por DNI o por curso más alto en el que esté matriculado.

**Actores principales**: Profesor.

**Actores secundarios**: Alumnos.

**Precondiciones**: 

1. El usuario debera indicar como quiere que se ordene y el orden de este. Mediante un menu numérico que se mostrará por pantalla se indicará el parámetro por el cual se ordenará (ordenados alfabeticamente por nombre y apellido, por DNI o por curso más alto en el que esté matriculado, ascendente o descendentemente).
2. El usuario indicará mediante un 1 y 0 el sentido del orden. 1(ascendente) y 0(descendente).

**Flujo principal**:

1. El caso de uso comienza cuando cuando el sistema quiere mostrar los alumnos ordenados.
2. El sistema recoge a los alumnos de forma ordenada.

**Postcondiciones**:

- El sistema muestra los alumnos ordenadamente.

**Flujos alternativos**:

1.a. Si el usuario no introduce una opcion valida en el menu del parametro por el cual se ordenara, el programa imprimira en pantalla un "ERROR, opcion no valida", y volvera a pedirlo.

2.a Si el usuario introduce un sentido de ordenacion no valido se mostrara por pantalla "ERROR"
