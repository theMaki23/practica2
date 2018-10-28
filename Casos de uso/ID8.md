# Mostrar alumnos de un grupo

**ID**: 8

**Breve descripción**: El sistema muestra los usuarios que hay registrados en un grupo determinado.

**Actores principales**: Profesor.

**Actores secundarios**: Alumnos.

**Precondiciones**: 

1. Debe de existir almenos 1 alumno registrado en el sistema.
2. Debe de estar registrado almenos 1 grupo en el sistema.
3. Cada grupo debe tener como minimo 1 alumno registrado.

**Flujo principal**:

1. El caso de uso comienza cuando el sistema requiere mostrar los alumnos pertenecientes a un grupo determinado.
2. El sistema localiza al grupo requerido por el usuario y muestra sus componentes.
3. El sistema localiza al lider del grupo si lo hubiese y lo indica de manera especial.

**Postcondiciones**:

- El sistema muestra a los alumnos que componen el grupo, remarcando al lider si lo hubiese.

Flujos alternativos:

1.a. Si el sistema no tiene alumnos registrados muestra un mensaje de error.

2.a. Si el sistema no tiene ningun grupo registrado muestra un mensaje de error.

2.b. Si el grupo seleccionado no tiene alumnos registrados se mostrara un mensaje de error.

3.a. Si no existe lider en el grupo no se muestra nada.