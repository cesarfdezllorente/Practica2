# *Guardar*

**ID**:006

**Breve descripcion**: Sistema permite guardar los datos de los alumnos en un fichero binario

-**Actores principales**:Profesor

-**Actores secundarios**:Alumno 

**Precondiciones**

1. Debe de existir datos para poder guardar


**Flujo principal** 

1. El Caso Uso comienza cuando el sistema necesita guardar los datos de un alumno en el fihero binario

2. Se borra el antiguo fichero binario

3. Se vuelca el vector de alumnos en el fichero Binario creado con el mismo nombre


**Post condiciones**

1. Se manda un mensaje de que se ha guardado con exito 

**Flujos alternativos**

  1. Si hay algun error al abrir el fichero nuevo se mostrará mensaje de error por pantalla
  
  2. Si no existe fichero binario se manda mensaje pidiendo que nombre quiere para su fichero binario
