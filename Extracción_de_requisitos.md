# EXTRACCIÓN DE REQUISITOS



**PARTES INTERESADAS:**

* Profesor de la asignatura Ingeniería del Software.



**DATOS QUE DEBE ALMACENAR LA APLICACIÓN:**

* Debe tener la información de los alumnos de forma organizada según el DNI, nombre, apellidos, teléfono, email-uco, dirección postal, curso más alto en el que está matriculado, fecha de nacimiento, grupo, líder de grupo. 



**FUNCIONALES:**

* Introducir alumnos manualmente o cargar una base de datos entera de un fichero.(1)

* Mostrar un listado de los alumnos ordenados alfabéticamente por nombre y apellido, por DNI o por curso más alto en el que esté matriculado, ascendente y descendente y por grupo.(1)

* Mostrar a los alumnos que correspondan con el DNI, primer apellido que introduzca el usuario. (2)

* Modificar datos de un alumno. (3)

* Borrar alumno por DNI o por apellido.(3)

* Copia de seguridad manual.(4)

* Generar un fichero que te muestre los datos.(1)

* Mostrar los usuarios de un grupo determinado.(3)

* Mostrar líder de cada grupo de forma especial.(5)

* Insertar alumnos manualmente o cargar una base de datos entera de una copia de seguridad.(1)



**NO FUNCIONALES:**

* Máximo 150 alumnos.

* El fichero generado debe de ser con la extensión ".bin".

* Sistema operativo funcional es linux. 

* Interfaz obligatoria: linea de comandos.

* Lenguaje de programación en C++.

* El fichero que muestra los datos tiene que estar en lenguaje markdown.

* No existe límite de personas por grupo (1 persona puede ser un grupo).

* Cada grupo puede tener o no líder y si existe este debe de ser único.

* Todos los datos son obligatorios menos el grupo y su líder.
