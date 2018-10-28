# Copia de seguridad manual

**ID**: 6

**Breve descripción**: El sistema realizará una copia de seguridad de los datos solicitada por el usuario.  

**Actores principales**: Profesor.

**Actores secundarios**: Alumnos.

**Precondiciones**: 

1. Debe de existir almenos 1 alumno registrado en el sistema.
2. Debe de existir un fichero en el que estén almacenados los datos.

**Flujo principal**:

1. El caso de uso comienza cuando el usuario solicita realizar una copia de seguridad de los datos.
2. El sistema genera un segundo fichero con los datos guardados hasta ese momento.

**Postcondiciones**:

- El sistema generá un fichero que incluirá los datos registrados en el sistema hasta ese momento.

**Flujos alternativos**:

1.a. Si este fichero ya existe se sobreescribe por el nuevo.

2.a. Si no existen alumnos registrados en el sistema no se creara el fichero y se mostrara un mensaje de error.