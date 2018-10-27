# *Borrar Alumno*

**ID**:005

**Breve descipcion**: El sistema borra los datos de un alumno

-**Actores principales**: Profesor

-**Actores secundarios**: Alumno

**Precondicciones**

1. El alumno debe existir en el sistema

**Flujo principal**

1. El caso de uso comienza cuando el sistema necesita buscar uno o varios alumnos

2. El sistema pregunta al usuario si desea borrar un alumno, un equipo o todas la base de datos

2.1. Si es un alumno o equipo se hará uso de la función buscar, que retornará la posición de los alumnos buscados

2.1.1. Se borrarán dichos alumnos

2.2. Si es toda la base de datos, el sistema no hará uso de la función buscar y borrará toda la base de datos

**Post condiciones**

1. Se muestra mensaje de que se ha borrado a tal o tales alumnos

**Flujo alternativo**
