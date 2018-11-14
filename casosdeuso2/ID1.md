# Insertar alumno
**ID**: 1

**Breve descripcion**: El sistema permite insertar un alumno en la base de datos.

**Actores principales**: Profesor.

**Actores secundarios**: Alumnos.

**Precondiciones**: 

1. Al insertar un unico alumno se seguira el orden DNI, nombre, primer apellido, segundo apellido, telefono, email-uco, direccion postal, curso mÃ¡s alto, fecha de nacimiento, equipo, lider, en ese orden, separado por espacios en blanco. Todos los campos seran obligatorios menos el de lider y equipo.
2. El alumno no puede existir en el sistema previamente.
3. En la base de datos no puede existir mas de 150 alumnos registrados.


**Flujo principal**:

1. El caso de uso empieza cuando el sistema quiere insertar un alumno o una base de datos.
2. El sistema recopila la informacion de la copia de seguridad o bien pide por teclado la informacion de un alumno.

**Postcondiciones**:

- El sistema añade el alumno a la base de datos.

**Flujos alternativos**:

1.a. Si al insertar alguno de los atributos no son correctos, el sistema mostrara por pantalla: "ERROR, vuelve a introducir los datos correctamente" y se volvera a pedir al usuario que inserte el alumno.

2.a. Si hay 150 alumnos o mas registrados, el sistema imprimira por pantalla un error tal que: "ERROR, base de datos llena".

3.b. Si el DNI introducido coincide con alguno registrado en la base de datos, el sistema mostrara en pantalla: "ERROR, alumno ya registrado". 
