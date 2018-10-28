# *Modificar Alumno*

**ID**:004

**Breve descipcion**: El sistema modifica los datos de un alumno

-**Actores principales**: Profesor

-**Actores secundarios**: Alumno

**Precondicciones**

1. El alumno debe existir en el sistema

**Flujo principal**

1. El caso de uso comienza cuando el usuario desea modificar los datos de un alumno

2. El sistema hace uso de la función buscar_alumno indicando a la función que quiere buscarse un alumno, no un equipo

      2.1 La función buscar_alumno retornará la posición del alumno

3. El sistema solicita que campo desea modificar del alumno y cuál es su cambio

4. El usuario proporciona dichos datos

5. El sistema introduce los nuevos cambios de dicho alumno 

**Post condiciones**

1. Se muestra por pantalla el alumno

**Flujo alternativo**

2.a. Si el alumno a modificar no está en la base de datos se mandará mensaje de error

2.b. Si se introduce un apellido y se encuentra repetido se mostrará un mensaje de error indicando que debe introducir el DNI del alumno a buscar

3. Si se quiere modificar a un grupo y ponerle un lider pero ya tiene, se mostrará un mensaje de error indicando que ese grupo ya tiene lider 
