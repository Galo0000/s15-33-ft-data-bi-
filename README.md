<p align="center">
  <img src="assets/Logo_consultora.png" width="50%" alt="consultora">
</p>

# <h1 align= 'center'>Estudio y desarrollo de aplicación sobre Rendimiento Deportivo </h1>

![Markdown](https://img.shields.io/badge/-Markdown-black?style=flat-square&logo=markdown)
![Python](https://img.shields.io/badge/-Python-black?style=flat-square&logo=python)
![Numpy](https://img.shields.io/badge/-Numpy-black?style=flat-square&logo=numpy)
![Pandas](https://img.shields.io/badge/-Pandas-black?style=flat-square&logo=pandas)
![Matplotlib](https://img.shields.io/badge/-Matplotlib-black?style=flat-square&logo=matplotlib)
![Seaborn](https://img.shields.io/badge/-Seaborn-black?style=flat-square&logo=seaborn)
![Scikitlearn](https://img.shields.io/badge/-Scikitlearn-black?style=flat&logo=scikitlearn)
![AWS](https://img.shields.io/badge/-AWS-black?style=flat-square&logo=aws)
![Power BI](https://img.shields.io/badge/-Power%20BI-black?style=flat-square&logo=powerbi)
![Git](https://img.shields.io/badge/-Git-black?style=flat-square&logo=git)
![GitHub](https://img.shields.io/badge/-GitHub-black?style=flat-square&logo=github)
![Google Drive](https://img.shields.io/badge/-Google%20Drive-black?style=flat-square&logo=googledrive)
![Google Colaboratory](https://img.shields.io/badge/-Google%20Colaboratory-black?style=flat-square&logo=googlecolaboratory)
![Jupyter](https://img.shields.io/badge/-Jupyter-black?style=flat&logo=jupyter)
![Visual Studio Code](https://img.shields.io/badge/-Visual%20Studio%20Code-black?style=flat&logo=visual-studio-code&logoColor=007ACC)

# Índice

- [Descripción](#Descripción)
- [Introducción](#Introducción)
- [Objetivos](#Objetivos)
- [Datos](#Datos)
- [Desarrollo](#Desarrollo)
  - [ETL](#ETL)
  - [Análisis Exploratorio de Datos (EDA)](#Análisis%20Exploratorio%20de%20Datos%20(EDA))
  - [Dashboard](#Dashboard)
  - [Modelo](#Modelo)
  - [Deploy](#Deploy)
- [Tecnologias y Herramientas](#Tecnologias%20y%20Herramientas)
- [Equipo](#Equipo)

# Descripción

Este proyecto forma parte de una simulación laboral realizada por NoCountry en donde se toma una temática o tema para generar el desarrollo de un proyecto como solución a una problematica de negocio basada en datos.

La temática del proyecto elegida en este caso, esta referida al rendimiento deportivo de equipos de futbol; enfocada en un contexto general de rendimiento en una competencia, y en particular en un evento o partido.


# Introducción

<p align="center">
  <img src="assets/Banner_DeRabona.png" width="70%" alt="consultora">
</p>

La plataforma DeRabona es un sitio web que contiene informacion futbolística, como puntuaciones, resultados, estadísticas, noticias sobre transferencias y partidos. 

A pesar de que los valores de los jugadores, junto con otros hechos, son estimaciones, investigadores del Center for Economic Performance han descubierto que los "rumores" sobre transferencias de jugadores son en gran medida exactos.

Estos valores estimados de los jugadores generalmente se actualizan cada pocos meses; considerando cómo funciona el mercado del fútbol de asociación , estas estimaciones pueden ser ligeramente inferiores o superiores a lo que podría sugerir la forma actual de los jugadores y, por lo tanto, el valor actual.

Una apuesta deportiva es un pronóstico de un evento o de un resultado deportivo puntual que consiste en apostar una determinada cantidad de dinero por el resultado elegido.

El proposito de una apuesta deportiva es beneficiarse de este pronóstico o predicción entonces, si se acierta el pronostico que se hizo, cobrarás tus ganancias.

La industria de las apuestas deportivas continúa en franco ascenso y Argentina no es la excepción ante esta tendencia global. De hecho, un reciente informe en la región indica que el rubro ya genera aproximadamente 10 mil millones de dólares en Latinoamérica, de los cuales casi un 25% (2,4 mil millones) corresponden al país campeón mundial de fútbol.

Según indica la compañía Playtech, encargada de llevar a cabo el relevamiento en territorio albiceleste pero que también incluyó a Brasil, Perú, Chile y Colombia, el crecimiento despegó en particular a partir de la pandemia de Covid-19 y los argentinos lideran este incremento en cuanto a cantidad de usuarios registrados y descargas de aplicaciones. 

# Objetivos

Nuestro cliente, dueño del sitio DeRabona nos pide que se realice un estudio sobre el rendimiento deportivo en general para identificar informacion valiosa para 
encarar nuevas funcionalidades e identificar patrones fundamentales en la dinamica de los equipos, jugadores, torneos, etc.

Tambien, se nos encarga la creacion de una aplicacion o sistema que permita predecir o pronosticar el resultado de un partido determinado, con miras al desarrollo de una aplicacion y seccion de apuestas en el sitio basandose en el contexto de desarrollo y crecimiento pronunciado en la industria de las apuestas deportivas en todo el mundo y en especial, en Latinoamerica.

# Datos

Los datos utilizados, provienen de dos fuentes:

* Transfermarkt
* Kaggle

Los datos extraidos de Kaggle estan integrados por 9 ficheros con formato csv, los cuales contienen data referente a clubes, competencias y jugadores de futbol.
Estos son:

* appearances
* club_games
* clubs
* competitions
* game_events
* game_lineups
* games
* player_valuations
* players

Aunque estos ficheros son extraidos de kaggle, originalmente contienen datos de la plataforma Transfermarket. Por lo que decidimos complementar estos ficheros extrayendo desde la plataforma datos sobre una liga en particular, en este caso la liga de Brasil o el Brasileirao, para complementar nuestros datos y tener un contraste con lo cual comparar nuestra data original y tambien con la cual probar distintos análisis, postulados, y modelos que constuyamos a lo largo del desarrollo del proyecto.
Esta data se descargo en una carpeta comprimida, archivos json liga brasil.zip, la cual cuenta con los siguientes ficheros:

* clubs
* game_lineups
* games
* players

Disponibilizamos el diccionario de datos de nuestra data [aquí]()

# Desarrollo
## ETL
## Análisis Exploratorio de Datos (EDA)
## Dashboard
## Modelo
### Descripción

Este repositorio contiene el desarrollo de un modelo de machine learning diseñado para predecir los resultados de partidos de fútbol utilizando datos históricos de rendimiento deportivo. El modelo se ha desarrollado utilizando un proceso de Extracción, Transformación y Carga (ETL) de datos para limpiar y preparar los datos, seguido de un Análisis Exploratorio de Datos (EDA) para comprender mejor la naturaleza de los datos y finalmente, el entrenamiento de varios algoritmos de clasificación para realizar predicciones precisas.

### Contenido del Repositorio

- **ETL y EDA**: Se realiza un proceso de ETL para limpiar y preparar los datos provenientes de nueve bases de datos relacionales obtenidas desde Kaggle. Luego, se lleva a cabo un análisis exploratorio de datos para comprender las características de los datos y tratar con valores atípicos.
  
- **Entrenamiento de Modelos**: Se utilizan varios algoritmos de clasificación, incluyendo RandomForestClassifier, LogisticRegression, DecisionTreeClassifier, KNeighborsClassifier y GradientBoostingClassifier para entrenar y evaluar el modelo. Se divide el conjunto de datos en entrenamiento y prueba, y se evalúa el rendimiento de cada modelo utilizando métricas como precisión, recall y f1-score.

### Resultados del Modelo

- **RandomForestClassifier**: El modelo alcanzó una precisión del 99.18% en el conjunto de prueba.
  
- **LogisticRegression**: El modelo de regresión logística logró una precisión del 100% en el conjunto de prueba.

- **DecisionTreeClassifier**: El modelo de árbol de decisiones alcanzó una precisión del 100% en el conjunto de prueba.

- **KNeighborsClassifier**: El modelo de vecinos más cercanos obtuvo una precisión del 35.96% en el conjunto de prueba.

- **GradientBoostingClassifier**: El modelo de aumento de gradiente logró una precisión del 100% en el conjunto de prueba.

### Uso del Repositorio

Este repositorio puede ser utilizado para entender el proceso de desarrollo de un modelo de machine learning para predecir resultados de partidos de fútbol. Se proporciona el código fuente en Python utilizando bibliotecas como Pandas, Polars, Scikit-learn, Seaborn y Matplotlib. Los datos utilizados en este proyecto pueden ser reemplazados por conjuntos de datos personalizados para adaptarse a diferentes contextos o aplicaciones.
## Deploy
# Tecnologias y Herramientas
# Equipo

<div align="center">

<!-- Primera fila -->
<table>
  <tr>
    <td align="center">
      <img src="https://avatars.githubusercontent.com/u/106486985?s=400&u=f2b5a4953b674b71e5df9e4c71c89ee2ae75fa65&v=4" width="200" height="200"><br><strong>Marco</strong><br>
      <a href="https://www.linkedin.com/in/marco-antonio-caro-22459711b"><img src="assets/linkedin.png" style="width:20px;"></a>
      <a href="https://github.com/marco11235813"><img src="assets/github.png" style="width:20px;"></a>
    </td>
    <td align="center">
      <img src="https://avatars.githubusercontent.com/u/125699535?v=4" width="200" height="200"><br><strong>Adrian</strong><br>
      <a href="http://www.linkedin.com/in/juan-manuel-yunes-mor"><img src="assets/linkedin.png" style="width:20px;"></a>
      <a href="https://github.com/jyunesmor"><img src="assets/github.png" style="width:20px;"></a>
    </td>
    <td align="center">
      <img src="https://avatars.githubusercontent.com/u/101422922?v=4" width="200" height="200"><br><strong>Guillermo</strong><br>
      <a href="http://www.linkedin.com/in/leandro-mambelli-79834a6b"><img src="assets/linkedin.png" style="width:20px;"></a>
      <a href="https://github.com/guillermo"><img src="assets/github.png" style="width:20px;"></a>
    </td>
  </tr>
</table>

<!-- Segunda fila -->
<table>
  <tr>
    <td align="center">
      <img src="https://avatars.githubusercontent.com/u/112107967?v=4" width="200" height="200"><br><strong>Jorge</strong><br>
      <a href="https://www.linkedin.com/in/jorge-antonio"><img src="assets/linkedin.png" style="width:20px;"></a>
      <a href="https://github.com/jorge11235813"><img src="assets/github.png" style="width:20px;"></a>
    </td>
    <td align="center">
      <img src="https://avatars.githubusercontent.com/u/108310078?v=4" width="200" height="200"><br><strong>Matias</strong><br>
      <a href="http://www.linkedin.com/in/matias"><img src="assets/linkedin.png" style="width:20px;"></a>
      <a href="https://github.com/matias"><img src="assets/github.png" style="width:20px;"></a>
    </td>
  </tr>
</table>

</div>

