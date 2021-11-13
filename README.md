# Elecciones PASO - Resultados de Agrupaciones por Circuito y Departamento

# Alumnos

*Arancibia Patricia

*Velazquez Lucas



Para la confeccion del tp se utilizaron los resultados electorales de las PASO 2021 para la Provincia del Chaco obtenidos de la página DNA, así como los circuitos en formato shape de la página Circuitos Electorales Argentina.

Se decidió trabajar con los votos de las elecciones para diputados provinciales descartando en consecuencia los votos para diputados nacionales, en segundo lugar obtuvimos los votos positivos de todas las agrupaciones por circuito (así como los votos positivos totales por circuito) descartanto los votos blancos, nulos, recurridos, etc. 
Se armo una lista en formato txt denominada "circuitos_chaco", Una vez realizado esto se pasó la base procesada junto con el shape de los circuitos a la herramienta QGIS donde mediante un join se les asigno a cada circuito sus correspondientes datos de la elección, luego de haber subido esta nueva base a PostgreSQL.

