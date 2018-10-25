# *Insertar Alumno*

**ID**:001

**Breve descripcion**: El sistema inserta datods del alumno

-**Actores principales**:Profesor

-**Actores secundarios**:Alumno 

**Precondiciones**

1. El alumno no debe existir en la base de datos

2. No debe de haber mas de 150 alumnos

3. Solo puede haber ,si es que lo hay, un solo lider

**Flujo principal** 

1. El caso de uso empieza cuando el sistema necesita insertar un alumno

2. El sistema pide al usuario que introduzca todos los atributos

3. El sistema preguntará al usuario si desea introducir

4. El sustema recoge los datos del alumno

**Post condiciones**

1. El sistema muestra la informacion del alumno insertado por pantalla

**Flujos alternativos**

  1. Si al insertar el DNI o email del alumno ,dicha informacion, se mostrara un mensaje de error por pantalla  avisando que el alumno  ya existe en la base de datos

  2. Si se desea establecer un lider en un grupo que ya lo tiene , se mostrara error diciendo que el grupo ya tiene lider y que para cambiarlo debe llamar a modificar para cambiar el lider del grupo.

  3. Si el usuario desea introducirlos , el sistema  

  4. Si el usuario no desea,
