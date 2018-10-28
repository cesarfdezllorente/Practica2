# *Insertar Alumno*

**ID**:001

**Breve descripcion**: El sistema inserta datos del alumno

-**Actores principales**:Profesor

-**Actores secundarios**:Alumnos 

**Precondiciones**

1. El alumno no debe existir en la base de datos

2. No debe de haber mas de 150 alumnos

3. Solo puede haber ,si es que lo hay, un solo lider

**Flujo principal** 

1. El caso de uso empieza cuando el sistema necesita insertar un alumno

2. El sistema pide al usuario que introduzca todos los atributos obligatorios del usuario

3. El sistema recoge los datos del alumno

4. El sistema preguntará al usuario si desea introducir el grupo al que pertenece alumno y si es líder o no 
    3.1. Si el usuario desea introducir estos datos, el sistema los recibirá 
    3.2. Si el usuario no lo desea en ese momento, el sistema dejará esos campos a 0


**Post condiciones**

1. El sistema muestra la información del alumno insertado por pantalla

**Flujos alternativos**

  2. Si al insertar el DNI o email del alumno ,dicha información ya está en la Base de Datos, se mostrará un mensaje de error por pantalla  avisando que el alumno  ya existe en la base de datos

 4. Si se desea establecer un lider en un grupo que ya lo tiene , se mostrará error diciendo que el grupo ya tiene lider y que para cambiarlo debe  modificar y  cambiar el lider del grupo.
