# Descripción de Conjunto de datos
Conjunto de datos perteneciente al proyecto de grado "CONSTRUCCIÓN DE UN CONJUNTO DE DATOS SOBRE GESTOS DEPORTIVOS DE SAQUE Y REMATE COMO FUNDAMENTO PARA EL ÁNALISIS DEDUCTIVO Y TOMA DE DECISIONES EN DEPORTISTAS DE VOLEIBOL DE LA UPTC"


## Abreviaciones [metrica - me]
El conjunto de datos presenta algunas abreviaturas en los nombres de sus variables, es por esto que acontinuación se explica cuales son:
|Abreviatura|Significado|
|-----------|-----------|
|ma|Movimiento Angular|
|va|Velocidad Angular|
|vl|Velocidad Lineal|
|std|Desviación estandar|

## Unidades de metricas
Cada archivo csv cuenta representa un tipo de dato, a continuación se presentan las unidades pertenecientes a cada gesto:
| Métrica | Unidad |
|---------|--------|
|Movimiento Angular| Grado sexagesimal|
|Velocidad Angular| rad/s|
|Velocidad Lineal| m/s|

## Descripción de variables
A continuación se presenta la descripción de las variables presentes en los csv.

|Nombre de variable| Descripción|
|------------------|------------|
|idJugador|Identificador del jugador (Util para hacer merge entre los archivos)|
|me_i_Extremidad|Esta variable indica el valor de la metrica promedio de la extremidad (muñeca, codo, hombro, cadera, rodilla, tobillo) en al momento de iniciar el gesto deportivo.|
|me_f_Extremidad|Esta variable indica el valor de la metrica promedio de la extremidad (muñeca, codo, hombro, cadera, rodilla, tobillo) en al momento de impactar el balón, correspondiente a la fase de Golpeo en los gestos deportivos.|
|me_std_Extremidad|Cada métrica (movimiento angular, velocidad lineal, velocidad angular) ofrece una desviación estándar, perteneciente a la dispersión presentada por el jugador en los n videos analizados.|
| Edad| Edad del jugador al cual se le está realizando el análisis.|
|Sexo|Sexo del jugador al cual se le está realizando el análisis.|
|Peso|Peso del jugador al cual se le está realizando el análisis. **_(Valor en kg)_**|
|Experiencia|Esta variable indica la cantidad de años que el jugador tiene entrenando. Ayuda a identificar el nivel del jugador.|
|Efectividad|Efectividad presentada por el jugador en la sesión de captura de movimientos. Esta variable toma únicamente en cuenta que el gesto del jugador haya tenido como resultado que el balón se encuentre en el campo de juego del rival. **_(Valor en porcentaje)_**|

[Click Aqui](https://www.kaggle.com) para ir a kaggle.
