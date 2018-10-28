# Generar fichero de datos

**ID**: 7

**Breve descripci�n**: El sistema genera un fichero en el que se muestran los datos almacenados por el profesor.

**Actores principales**: Profesor.

**Actores secundarios**: Alumnos.

**Precondiciones**:

1. Debe de existir almenos 1 alumno registrado en el sistema.
2. El formato del fichero generado debe de ser con la extensi�n ".bin".

**Flujo principal**:

1. El caso de uso comienza cuando el usuario ejecuta el programa e introduzca el primer alumno.
2. Los datos introducidos se guardan en el fichero generado.

**Postcondiciones**:

- El sistema generar� un fichero en el que estar�n guardados los datos introducidos al sistema.

**Flujos alternativos**:

1.a. En el caso de que ya existiera un fichero, el sistema abrir�a el fichero y a�adir�a los datos sin sobreescribir lo existente.

1.b. Si el usuario no introduce ning�n alumno y el sistema no encuentra un fichero existente, no se generar� ninguno.

2.a. Los datos que se introduzcan al sistema se guardaran en el fichero solo si estan expresados de forma v�lida.
