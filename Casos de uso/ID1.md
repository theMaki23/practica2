# Insertar alumno/alumnos.

**ID**: 1

**Breve descripcion**: El sistema permite insertar un alumno o cargar una base de datos desde un fichero.

**Actores principales**: Profesor.

**Actores secundarios**: Alumnos.

**Precondiciones**: 

1. Al insertar un unico alumno se seguira el orden DNI, nombre, primer apellido, segundo apellido, telefono, email-uco, direccion postal, curso mÃ¡s alto, fecha de nacimiento, equipo, lider, en ese orden, separado por espacios en blanco. Todos los campos serÃ¡n obligatorios menos el de lider y equipo.
2. Para poder cargar una base de datos de alumnos esta debe de estar en un fichero formato txt. Seguir una estructura tal que DNI, nombre, apellidos, telefono, email-uco, direccion postal, curso mas alto, fecha de nacimiento, equipo, lider, en ese orden, separado por espacios en blanco. Todos los campos seran obligatorios menos el de lider y equipo. 
3. El fichero txt de la base de datos debe de tener como nombre "basededatos_cargar".
4. Cada atributo del alumno debe de ser consecuente a la realidad. DNI estara formado por 8 numeros naturales, telefono por 9 numeros naturales, nombre y apellidos por una cadena de caracteres que no podrÃ¡ contener numeros, curso mas alto por un unico numero natural, la fecha de nacimiento por una estructura tal que "00/00/00" y por ultimo se dirÃ¡ si es lider o no mediante un 1 (es lider) o un 0 (no es lider).

**Flujo principal**:

1. El caso de uso empieza cuando el sistema quiere insertar un alumno o una base de datos.
2. El sistema recopila la informacion de la base de datos o bien pide por teclado la informacion de un alumno.

**Postcondiciones**:

- El sistema añade el alumno o los alumnos en la base de datos.

**Flujos alternativos**:

1.a. Si al insertar alguno de los atributos no existe o no cumple los requisitos, el sistema mostrara por pantalla un ERROR y se volvera a pedir al usuario que inserte el o los alumnos.

2.a. Si el fichero txt no existe o no tiene el nombre correcto mostrara "el fichero de carga no existe o no es correcto".