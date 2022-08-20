# parcial_gestion_Datos


Juan Sebatian Vargas Torres

Las respuestas también se pueden encontar en el notebook para mayor claridad en cada una de las secciones del mismo.

Pregunta 1:

Las variables y sus  tipos del del dataframe se pueden observar a continuación:


Atributo  |Type
-------------------|-------------------
 Gender         | object (Categórico)
 Race         |  object (Categórico)
 parental level of education         |  object (Categórico-ordinal)
 lunch         |  object (Categórico)
 test preparation course          |  object (Categórico)
 math score     |  float 64 (Numérico)
 reading score   |  float 64 (Numérico)
 writing score   |  float 64 (Numérico)
 
 
 
 
 Pregunta 2:
 
 
 Gender:
 Se validó la cantidad de nulls que habían y se logró indentificar que el porcentaje era del ~4%, en este caso se pudo directamente eliminar dichos registros, sin embargo, lo que se hizo fue cambiarlos por la moda. 
No se encontraron valores inconsistentes.
Se asume que el valor "non-binary" es un dato válido.

Race:

Se validó la cantidad de nulls que habían y se logró indentificar que el porcentaje era del ~4%, en este caso se pudo directamente eliminar dichos registros, sin embargo, lo que se hizo fue cambiarlos por la moda. 
No se encontraron valores inconsistentes.

Parental level of Education :
Se validó la cantidad de nulls que habían y se logró indentificar que el porcentaje era del ~6%, en este caso se pudo directamente eliminar dichos registros, sin embargo, lo que se hizo fue cambiarlos por la moda. 
No se encontraron valores inconsistentes.


Lunch:

Se validó la cantidad de nulls que habían y se logró indentificar que el porcentaje era del ~5%, en este caso se pudo directamente eliminar dichos registros, sin embargo, lo que se hizo fue cambiarlos por la moda. 
No se encontraron valores inconsistentes.



Test preparation course:

Se validó la cantidad de nulls que habían y se logró indentificar que el porcentaje era del ~4%, en este caso se pudo directamente eliminar dichos registros, sin embargo, lo que se hizo fue cambiarlos por la moda. 
No se encontraron valores inconsistentes.
Se toma el valor "none" como válido.


math score:

Se validó la cantidad de nulls que habían y se logró indentificar que el porcentaje era del ~5%, en este caso se pudo directamente eliminar dichos registros, sin embargo, lo que se hizo fue cambiarlos por la moda. 

Se econtaron valores atípicos, por lo tanto se buscaron aquellos estuvieran 1.5IQR encima del Q3 o 1.5IQR por debajo del Q1 y luego estos se cambiaron por lo mediana.


Reading score:

Se validó la cantidad de nulls que habían y se logró indentificar que el porcentaje era del ~5%, en este caso se pudo directamente eliminar dichos registros, sin embargo, lo que se hizo fue cambiarlos por la moda. 

Se econtaron valores atípicos, por lo tanto se buscaron aquellos estuvieran 1.5IQR encima del Q3 o 1.5IQR por debajo del Q1 y luego estos se cambiaron por lo mediana.


writing score:

Se validó la cantidad de nulls que habían y se logró indentificar que el porcentaje era del ~5%, en este caso se pudo directamente eliminar dichos registros, sin embargo, lo que se hizo fue cambiarlos por la moda. 

Se econtaron valores atípicos, por lo tanto se buscaron aquellos estuvieran 1.5IQR encima del Q3 o 1.5IQR por debajo del Q1 y luego estos se cambiaron por lo mediana.


 
 
 Pregunta 3:

Se logra observar que la asignatura que en promedio tiene mayor puntaje es Reading.

Para el caso de Math: Se puede obsevar que no tiene ningún sesgo, es simétrica la distribución.

Para el caso de Reading: Se puede obsevar que tiene un ligero sesgo hacia la derecha.

Para el caso de Writing: Se puede obsevar que tiene un ligero sesgo hacia la derecha.

Pregunta 4:


Se puede observar que existen una alta correlación positiva entre todos los features, resaltando una mayor correlación entre los features: "Reading Score" y "Writing Score".




Pregunta 5:


Se puede observar que de media, los hombres tienden a tener un puntaje ligeramente mayor a de las mujeres y las personas consideradas como "non-binary"

En base a lo anterior, se logra obsevar una ligera diferencia en los puntajes obtenidos en matemáticas según el género.




Pregunta 6:


Se puede obsevar que los padres de los hijos que obtuvieron un writing score superior al percentil 85, tienen todos los distintos tipos de escolaridad, aunque los más representativos son "associate's degree" y "some college"



Pregunta 7:


Se puede obsevar que solo el 2,4% de los estudiantes obtuvieron un puntaje igual o superior a 90 en las tres asignaturas.

Se puede observar que de ese 2,4% de los estudiantes, el ~54% de ellos se preparó para los exámenes.





