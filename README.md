# pi-03
En este proyecto individual se realiza un  análisis de datos e informe a partir de un dataset relacionado a accidentes aeros, en donde a partir del EDA y transformación de un dataset(incluyendo datasets extras complementarios). Seguida de la subida a un DB para luego ser cargada a la herramienta power Bi, con el fin de mostrar un Data Analysis en un Dashboard.

# Reporte de Calidad
Todo el proceso de EDA y transformacion fue realizado atreves de python. 
El dataset primario(accidentesAeros.csv), de donde se obtuvo la mayor parte de la información y la más relevante para realizar el análisis. Venia con muchísimos datos faltantes en la mayoría de las columnas, los cuales fueron completados o discretizados utilizando ciertos criterios y la información de otras columnas, además de otras fuentes. Dicho esto, varias de las columnas fueron descartadas por no obtener calidad de dato o ser redundantes.Sin embargo, luego de realizar el EDA se pudo concluir que varias columnas aportaban muchísima información y contexto para analizar y tratar el problema planteado.

Algo que cabe aclarar es que la información extra añadida en el dataset(pasajeros.csv) también tenía algunos datos faltantes y columnas no necesarias. Por lo que  luego del EDA se realizó un filtro como en el anterior para rescatar únicamente lo que aporta dato y contexto a la temática planteada. 


#Diccionario de Datos

Apartir del EDA se pudo concluir que las columnas del dataset AccidentesAeros.csv contenían los siguientes datos:

*Fecha: Día, mes y año en el que tomo lugar el accidente
*Hora Declarada: Momento En donde sucedio el accidente 
*Ruta: Lugar donde sucedió el accidente aereo
*Operador: Empresa u organización propietaria del avion
*flight_no: Número de vuelo registrado
*Route: Destino a donde se dirigían originalmente los aviones
*Ac_type: Modelo del avión
*Registracion: Número de Registro del Avión
*Cn_ln: Número de línea de fuselage
*all_abroad: Número total de personas aborde en el avión 
*Pasajeros a Bordo: número  de pasajeros en el avion
*crew_abroad: Número de tripulación en el avión
*Cantidad de fallecidos:Cantidad Total de gente que murió en el accidente 
*passenger_fatalities: Número de pasajeros Fallecidos 
*crew_fatalities: Número de Tripulantes fallecidos
*ground:Número de personas que murieron en un impacto del avión a tierra
*Summary:resumen de que accidente sucedió y en algunos casos porque sucedio


#Herramientas utilizadas

Python(incluida librerías Pandas y Sqlalchemy) con Jupyter Notebook: Utilizado para El EDA y la transformación 

MYSQL: Para crear una DB donde almacenar los datasets para luego cargarlos

PowerBi: Para que con los datos importados se pueda crear una visualización para hacer un Data Analysis en donde se puedan cruzar y relacionar datos. 
