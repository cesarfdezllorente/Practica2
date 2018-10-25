# Documento de extracción de Requisitos
## *Datos que almacena la aplicación*
La aplicación que debemos realizar se basará en una Base de Datos donde encontraremos una lista de alumnos.
Cada alumno tendrá como atributos:
* Nombre
* Apellidos
* Dni
* Fecha de nacimiento
* Teléfono
* Dirección Postal
* Curso más alto en el que está matriculado el alumno
* Email UCO
* Equipo de Ingeniería del Software al que pertenece
* Si es lider o no del grupo

## *Partes interesadas*
Las partes interesadas presentes en nuestra aplicación serán tanto profesores como alumnos

## *Requisitos Funcionales*
* Nuestra aplicación permitirá ***insertar*** a un máximo de 150 alumnos siendo obligatorio introducir todos sus atributos menos el equipo al que pertenece y si es lider o no.
* Podrá ***buscar*** a cualquier alumno previamente introducido por su Dni, apellidos o por equipo al que pertenece.
* ***Mostrará*** a un alumno o a todos a la vez de diferentes maneras de forma ascendente y descendente.
* Permitirá ***modificar*** los datos de los alumnos y ***borrar*** a uno o varios alumnos  a la vez.
* Se deberá ***guardar*** los datos sobre un fichero binario y además se podrá ***cargar*** dicho fichero binario cada vez que se quiera abrir la aplicación.
* Por último, permitirá  al usuario ***salir*** de dicha aplicación cuando  lo desee.

## *Requisitos no Funcionales*
Esta aplicación tendrá como requsitos no funcionales:
* Establecimiento de una interfaz por línea de comandos
* Se utilizará como Lenguaje de Programación C++ y  como Lenguaje de Documentación Marckdown
* La información de los alumnos de la Base de Datos estará guardada en un fichero Binario
* Deberá ser una aplicación eficiente y sencilla de comprender para el usuario
* Toda la información a mostar se hará por línea de Comandos de forma clara y ordenada y a través de un fichero en lenguaje Markcdown o html

## *Prioridad de los requisitos*
* **Prioridad 1:** Cargar Fichero Binario
* **Prioridad 2:** Insertar Alumno
* **Prioridad 3:** Guardar Fichero Binario
* **Prioridad 4:** Buscar Alumno
* **Prioridad 5:** Moatrar Alumno
* **Prioridad 6:** Modificar y borrar Alumno
* **Prioridad 7:** Salir de la Base de Datos
