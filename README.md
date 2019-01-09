# Curso Data Analytics
Este repositorio contiene el material para el curso de Data Analytics


Para lanzar el repositorio en Binder :
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/mlcordoba/curso_DA/master)


## 1 - MEDIO AMBIENTE DE TRABAJO
El objetivo es crear el medio ambiente de trabajo, desde el soporte (Jupyter notebook), pasando por el lenguaje (Python) y presentando las principales	herramientas para el análisis y visualización de los datos (Numpy, Pandas y Matplotlib)


#### 1.1 Jupyter Notebook : Los notebooks suponen la fusión de editor de texto, herramienta de programación y soporte de visualización, todo ello accesible a través del browser. Son en la actualidad, de facto, el medio por el que se intercambia código y se muestran los resultados.
 
 
1.2 Elementos básicos de Python : Python es un lenguaje de programación con más recorrido que R, sobre todo si se busca aplicación al Big Data.  En la presentación se enseñará a utilizar elementos básicos como son los tipos de datos (list, arrays, dictionaries), flujos de control (for loop, if/else), Input/Output de ficheros de datos y como generar visualizaciones.
 
 
1.3 Numpy, Pandas y Matplotlib : Estas librerías suponen las principales herramientas para el análisis y la visualización de datos. En este apartado indagaremos en ellas un poco más que en el apartado 1.2.

 
 
2 - TÉCNICAS DE EXPLORACIÓN DE DATOS - SERIES TEMPORALES
Este segundo bloque servirá para poner en práctica cuanto antes lo aprendido en el bloque 1 y pasar a manejar las técnicas de exploración de datos en un tipo de dato muy recurrente en el sector eólico/energético.


2.1 Análisis de la demanda de electricidad en España : Este tipo de series temporales suponen un buen ejemplo para practicar el manejo de datos.


2.2 Climatología de temperatura en España : Un buen caso para practicar el acceso a bases de datos en la web mediante APIs. Ademas servirá para ejercitar como condensar amplia información, fusionarla con la serie de demanda energética y analizar su impacto. 


2.3 Ejercicio  - Análisis de la contaminación del aire en Madrid : Primer paso en el problema que nos irá acompañando a lo largo del curso.

3 - TÉCNICAS DE DEPURACIÓN DE DATOS
En numerosas ocasiones el conjunto de datos original no es capaz de conducir al mejor modelo de predicción posible. Para dar con el mejor modelo es necesario aplicar técnicas de depuración de datos, para saber por ejemplo como seleccionar aquellas variables que ofrecen un mayor poder predictivo, crear nuevas variables utilizando otras como punto de partida que mejoren las originales o simplemente eliminar aquellas variables que degradan el sistema. 

3.1 Factor analysis / ANOVA : Se presentan dos de las técnicas más utilizadas para extraer información sobre un conjunto de variables y poder eventualmente ordenarlas en función del impacto que tengan sobre la variable dependiente. 


3.2 Clustering : Se presentan las técnicas más utilizadas (entre las que destaca el K-means) para separar datos y poder categorizarlas.


3.3 Reducción de dimensiones : Se presentan las técnicas más utilizadas (entre las que destaca el PCA) para poder construir un conjunto de datos de dimensiones reducidas, y por lo tanto manejable, de mejores características.


3.4 Feature Engineering : Análisis de diferentes casos prácticos en los que la construcción de nuevas variables produjo una mejora en la predicción.



4 - TÉCNICAS REGRESIÓN Y CLASIFICACIÓN LINEAL
Se trata del primer bloque dedicado a la predicción. Se empezará a practicar con las dos ramas, regresión y clasificación. La regresión constituye una predicción de una variable continua, mientras que la clasificación trata de predecir una variables discreta.


4.1 Regresión : Puesta en práctica de este tipo de predicción en problemas multidimensionales en Python.


4.2 Clasificación : Puesta en práctica de este tipo de predicción mediante el uso de diferentes técnicas, entre las que destacan : Regresión logística, SVM o Perceptron.


4.3 Árboles de decisión / Random Forest : Se trata de una técnica de predicción muy popular, fácil de implementar y a menudo suficiente. La pondremos en práctica para entre otros ejemplos, para predecir la generación eólica de un cartera de parques eólicos.


5 - TÉCNICAS REGRESIÓN Y CLASIFICACIÓN NO LINEAL
En este apartado se presentaran los elementos básicos de regresión y clasificación mediante redes neuronales. Además presentaremos, y usaremos, los frameworks más populares en Python (PyTorch, Keras y TensorFlow), algunos de ellos concebidos para el Deep Learning.


5.1 Redes Neuronales Artificiales : Conceptos esenciales de Redes Neuronales Artificiales.


5.2 Regresión : Puesta en práctica de este tipo de predicción en problemas multidimensionales.


5.3 Clasificación : Puesta en práctica de este tipo de predicción.


6 - TÉCNICAS PREDICCIÓN PROBABILISTICA
Se presentaran los conceptos en este tipo de predicción. La diferencia principal es que el resultado final en lugar de ser un único valor determinista, es una distribución de probabilidad. Este tipo de predicción se adapta mejor a aquellos sistemas en los que existe algún tipo de incertidumbre, ya sea en las condiciones iniciales o en alguna parte de la dinámica procesos. Se presentará el framework PyMC3 diseñado para este tipo de predicción.


6.1 Teorema de Bayes : Se trata de una parte fundamental de la predicción probabilística. Introduce los términos de distribución de probabilidad previa, posterior y probabilidad condicional. 


6.2 Simulación de MonteCarlo : Se trata de una técnica para resolver problemas cuya solución es no analítica mediante el uso de elementos probabilísticos.

6.3 Procesos estocasticos : Se presentan los tipos de procesos estocásticos y sus propiedades.


6.4 Cadenas de Markov : Se trata de un tipo de proceso estocástico muy común cuyo estado futuro depende únicamente del estado presente. 


6.5 MCMC : Parte fundamental de este bloque, donde se presenta los elementos prácticos de la predicción probabilística mediante procesos de cadenas de Markov, MC (Markov Chain) unido a simulación de Monte Carlo, MC.



7 - TÉCNICAS PREDICCIÓN DE SERIES TEMPORALES
La predicción de series temporales se puede abordar desde diferentes enfoques, ya sea mediante métodos lineales, como pueden ser los ARIMA o GARCH, mediante redes neuronales. En este apartado servirá pues como colofón a la parte de análisis de datos y técnicas de predicción.


7.1 ARIMA / GARCH / Exponential Smoothing : Puesta en práctica de las clásicas técnicas de predicción de series temporales en Python.


7.2 Redes Neuronales Artificiales : Emplearemos este tipo de técnica para resolver los aspectos no lineales en las series temporales.

7.3 Filtro de Kalman : Técnica para ir corrigiendo iterativamente la predicción en función de la incertidumbre (errores previos) y las observaciones más recientes.


Ejercicio - Predicción de la probabilidad de activación del protocolo de contaminación en Madrid



8 - BIG DATA EN LA NUBE
En este apartado se mostrarán los pasos a seguir para implantar un ecosistema de Big Data en una plataforma en la nube


8.1 Plataformas en la nube AWS/GCP : Se presentarán la plataforma mas popular (AWS) y la que parece dispuesta a arrebatarle esa posición, GCP.


8.2 Bases de datos : Un elemento fundamental en el diseño de un ecosistema de Big Data es la elección de la o las bases de datos. Estas deben encajar a la perfección con el tamaño presente y futuro de los datos y además del tipo de uso, intensivo/extensivo, que se haga de los datos almacenados.


8.3 Computación : El segundo elemento fundamental en el diseño de un ecosistema de Big Data en la nube es la elección de los recursos de computación. Estos deben de encajar, sin idealmente estar sobre o infradimensionados. En este apartado analizaremos diferentes casos prácticos y su solución óptima.


8.4 Pipelines : El tercer elemento fundamental. Adaptación de Python a ficheros de grandes dimensiones.


8.5 Queries : El este apartado se hará uso del lenguaje SQL para poder hacer consultas a bases de datos masivas.

8.6 Monitoring : El este apartado se presentan los diferentes elementos que se deben vigilar para que el sistema. Se aprovechará para enseñar elementos básicos de Linux, como utilizar la linea de comandos y algo de bash scripting.

