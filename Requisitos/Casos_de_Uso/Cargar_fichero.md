# *Cargar*

**ID**:007

**Breve descripcion**: El sistema permite cargar al fichero binario en la aplicacion

-**Actores principales**:Profesor

-**Actores secundarios**:Alumno 

**Precondiciones**

1. Debe existir un fichero binario


**Flujo principal** 

1. Sistema abre el fichero binario

2. El sistema vuelca el fichero binario en un vector de estructura de alumnos que permitirá porder manejar a todos los alumnos de la base de datos de manera sencilla

**Post condiciones**

1. Se manda un mensaje de que el fichero ha sido cargado con éxito

**Flujos alternativos**

  1. Si hay algun error al abrir el fichero se mostrará mensaje de error








