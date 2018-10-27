# *Mostrar Alumno*

**ID**:003

**Breve descipcion**: El sistema muestra los datos de uno o varios alumnos

-**Actores principales**: Profesor

-**Actores secundarios**: Alumno

**Precondicciones**

1. El alumno debe existir en el sistema

**Flujo principal**

1. El caso empieza cuando el sistema necesita mostrar uno o varios alumnos

2. El sistema pide si desea mostrar 1 alumno, todos o un equipoç

2.1. Si es un alumno o un equipo se hará uso de la función buscar

2.1.1. La función retornará la posición o posiciones en la que se encuentran los alumnos buscados

2.2. Si es todos los alumnos no se hará uso de la función buscar y el sistema pedirá de que manera quiere que se muestren los alumnos

2.2.1. El usuario proporcionará la información requerida

3. El sistema mostrará por pantalla la información del o de los alumnos solicitada

**Post condiciones**

1. Cuando se muestre por consola se deberá además crear un fichero markdown o html con la misma información mostrada

**Flujo alternativo**

2.a. Si el usuario introduce unos datos de un alumno que no está en la base de datos, un equipo no creado o no hay alumnos en la base de datos aún. Se mostrará mensaje de error
