Ejercicio Expresiones Regulares
==================================

La finalidad de este ejericio era el aprendizaje y uso de XML.


---------


Definición del ejercicio
---------------------

Dada la pagina web www.edreams.es mediante XML recopilar en un archivo `edreams.xml` una instancia valida para el formulario de dicha pagina.

Una vez obtenido, realizar un fichero SCHEMA `edreams.xsd` que valide el fichero xml.

Para aprender la utilidad de include debemos separar los *simpleType* en un fichero aparte y hacer un include en el main schema.

Finalmente, cuando se hayan realizado las dos cosas importar el fichero `WAC.xsd` de donde obtenemos el tipo **WAC** y hemos de incluirlo como un atributo de **origen** y **destino**.

----------------------
