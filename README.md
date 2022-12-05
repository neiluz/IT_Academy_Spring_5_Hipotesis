## IT_Academy_Spring_5_Hipotesis
_______________________________
### Descripción: Ejercicios de Hipotesis Testing con un Dataset de la Liga de football Europea.

### Objetivos:
* Planteamiento de una hipótesis.
* Uso del test de hipótesis en python.
* Uso e interpretación del p-valor por uno o más de un atributo.
* Aplicación del test de hipótesis e interpretación de resultados.

### Definición de las variables:
* Rk: Ranking del club.
* Squad: Nombre del club.
* Country: País al que pertenece el equipo.
* LgRk: Posición en la que terminó el equipo en la liga de su país.
* MP: Partidos jugados durante la temporada.
* W: Partidos ganados.
* D: Partidos empatados.
* L: Partidos perdidos.
* GF: Goles a favor.
* GA: Goles en contra.
* GD: Diferencia de goles.
* Pts: Puntos obtenidos.
* Pts/G: Promedio de puntos obtenidos sobre el total de partidos jugados.
* xG: Número de goles esperados de uno o varios jugadores, depende de la calidad de los tiros.
* xGA: Cantidad de goles esperados de los oponentes depende de la calidad de los tiros.
* xGD: Diferencia entre los goles anotados esperados y los fallados esperados. xGD=xG-xGA.
* xGD/90: Número de goles esperados de uno o varios jugadores en 90 minutos.
* Last 5: Resultado de los últimos 5 partidos (ganados, empatados y perdidos).
* Attendance: Número total de asistencias.
* Top Team Scorer: Nombre del goleador y cantidad de goles.
* Goalkeeper: Nombre del portero.

### Estructura del repositorio:
* Carga del Dataset
* Análisis exploratorio y estadisticos
* Gráficos de las variables más relevantes
* Seleccion de un atributo del conjunto de datos y calcular el p-valor y verificar si se rechaza la hipótesis nula escoginedoo un alfa de 5%.
* Seleccion de dos atributos del conjunto de datos. Calcular los p-valores y verificar si se rechazala hipótesis nula escogiendo un alfa de 5%.
* Seleccion de tres atributos del conjunto de datos. Calcular el p-valor y verificar si la hipótesis nula escogiendo un alfa de 5%.
* Conclusiones

### Librerias utilizadas:
Pandas 
Matplotlib
Seaborn
Plotly.express
Joypy
Missingno a
Scipy import 

### Fuentes utilizadas:
https://towardsdatascience.com/hypothesis-testing-with-python-step-by-step-hands-on-tutorial-with-practical-examples-e805975ea96e
https://machinelearningmastery.com/statistical-hypothesis-tests-in-python-cheat-sheet/
https://www.reneshbedre.com/blog/anova.html
