# *Buscar Alumno*

**ID**:002

**Breve descripcion**:Sistema busca un alumno

-**Actores principales**:Profesor

-**Actores secundarios**:Alumno

**Precondiciones**

1. Alumno debe existir en la base de datos

2. La función debe de recibir si sequiere buscar una persona o un equipo

**Flujo principal**

1. Si se busca una persona el sistema solicitará que introduzca su DNI o apellidos.

 1.1. El usuario proporcionará al sistema el DNI o apellidos
 
2. Si se busca por equipos , el sistema solicitará que introduzca qué equipo quiere buscar
 
 2.1. El usuario proporcionará el equipo a buscar
 
 **Post-Condiciones**
 
 1. Una vez encontrado,la función devuelve la posición en la que se encuentran esos alumnos en la base de datos
 
 **Flujo alternativo**
 
 1. Si el sistema no encuentra el alumno con los datos proporcionadso por usuario, se mandará mensaje de error y devolverá  -1

