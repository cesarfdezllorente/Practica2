# *Modificar Alumno*

**ID**:004

**Breve descipcion**: El sistema modifica los datos de un alumno

-**Actores principales**: Profesor

-**Actores secundarios**: Alumno

**Precondicciones**

1. El alumno debe existir en el sistema

**Flujo principal**

1. El caso de uso comienza cuando el usuario desea modificar los datos de un alumno

2. El sistema hace uso de la función buscar

3. La función buscar retornará la posición del alumno

4. El sistema solicita que campo desea modificar el alumno y cual es su centro

5. El usuario proporciona dichos datos

6. El sistema introduce los nuevos cambios de dicho alumno 

**Post condiciones**

1. Se muestra por pantalla el alumno

**Flujo alternativo**

3.a. Si el alumno a modificar no está en la base de datos

3.b. Si se introduce un apellido y se encuentra repetido se mostrará un mensaje de error indicando que debe introducir el DNI del alumno a buscar

5. Si se quiere modificar a un grupo y ponerle un lider pero ya tiene se mostrará un mensaje de error indicando que ese grupo ya tiene lider 
