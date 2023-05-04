# Elements of Machine Learning 2023

Este es un curso introductorio a la ciencia de datos, con énfasis principalmente en los fundamentos matemáticos y estadísticos de los principales algoritmos de aprendizaje automático y reconocimiento de patrones. El tema central del curso es el estudio de métodos para obtener información útil a partir de datos. Al final del curso, los estudiantes comprederán, tanto en la teoría como en la práctica, las etapas necesarias para producir un estudio o análisis de datos, desde la concepción de un problema, hasta la generación de un informe técnico de análisis. Para aprovechar de mejor manera el curso, es recomendable que los estudiantes estén familiarizados con temas de álgebra lineal, cálculo, estadística matemática, y tener conocimientos de al menos un lenguaje de programación (*e.g.* Python, R, Matlab, C++, u otros).


# Programa del curso
<div id='id-programa'/>

[Programa del curso](programa/Programa-ml2023.pdf){:target="_blank"}

### Horario
<div id='id-horario'/>

* Martes y jueves, 16:00 a 17:20 horas.

### Office Hours
<div id='id-office'/>

* Viernes de 18:00 a 20:00 horas, por solicitud del estudiante. También pueden enviar sus dudas por correo electrónico.


# Material del curso
<div id='id-material'/>

  **No.**  | **Fecha**    | **Tópicos**                                                         | **Recursos**
  -------- | ------------ | ------------------------------------------------------------------- |  -------------------------------------
  01       | 12.01.2023   | Introducción al curso. ML y Data Science. <br/> [Aula 01](aulas/Aula01.pdf){:target="_blank"} | 
  02       | 17.01.2023   | Repaso de estadística y probabilidad. <br/> [Aula 02](aulas/Aula02.pdf){:target="_blank"} | 
  03       | 19.01.2023   | Distribución teórica y distribución empírica. <br/> [Aula 03](aulas/Aula03.pdf){:target="_blank"} | Ejercicios en grupos.
  04       | 24.01.2023   | Variables aleatorias. Densidad y Función de Distribución. <br/> [Aula 04](aulas/Aula04.pdf){:target="_blank"} | Ver *aula04.ipynb*. 
  05       | 26.01.2023   | Estadísticos. Media, mediana y moda. <br/> [Aula 05](aulas/Aula05.pdf){:target="_blank"} | Ver *aula05.ipynb*. 
  L1       | 26.01.2023   | Lista 01.                                  | [Lista 01](listas/lista01.pdf){:target="_blank"} [penguins.csv](listas/penguins.csv){:target="_blank"} [tips.csv](listas/tips.csv){:target="_blank"} <br/> **Fecha de Entrega: jueves 2 de febrero.** 
  06       | 31.01.2023   | Covarianza y correlación. Distribución normal multivariada. <br/> [Aula 05a](aulas/Aula05a.pdf){:target="_blank"} [Aula 05b](aulas/Aula05b.pdf){:target="_blank"}  [Aula 05c](aulas/Aula05c.pdf){:target="_blank"}  | Ver *aula06.ipynb*.
  07       | 02.02.2023   | Presentaciones y discusión de análisis de datos. Técnicas de visualización. | 
  08       | 07.02.2023   | Análisis de Componentes Principales (PCA). <br/> [Aula 06](aulas/Aula06.pdf){:target="_blank"} | Ver *aula07.ipynb*.
  09       | 09.02.2023   | PCA. Proyección de datos. Biplot e interpretación. <br/> [Aula 07](aulas/Aula07.pdf){:target="_blank"} | Ver *aula08.ipynb*.
  10       | 14.02.2023   | Interpretación de componentes principales. <br/> [Aula 08](aulas/Aula08.pdf){:target="_blank"} | 
  L2       | 14.02.2023   | Lista 02.                                  | [Lista 02](listas/lista02.pdf){:target="_blank"} [weather.csv](listas/weather.csv){:target="_blank"} [crimes.dat](listas/crimes.dat){:target="_blank"} <br/> **Fecha de Entrega: martes 28 de febrero.** 
  11       | 16.02.2023   | Escalamiento multidimensional. PCA en imágenes. <br/> [Aula 09](aulas/Aula09.pdf){:target="_blank"} | Ver *aula09a.ipynb*, *aula09b.ipynb* y *aula10.ipynb*.
  12       | 21.02.2023   | Kernel PCA. Métodos locales de proyección. <br/> [Aula 10](aulas/Aula10.pdf){:target="_blank"} | Ver *aula11.ipynb* (pendiente). <br/> Experimentar con [Tensorflow Embedding Projector](https://projector.tensorflow.org/){:target="_blank"}
  13       | 23.02.2023   | *Manifold Learning*: IsoMap, UMap, t-SNE. <br/> [Aula 11](aulas/Aula11.pdf){:target="_blank"}  | Ver *aula12a.ipynb* y *aula12b.ipynb*.
  14       | 28.02.2023   | *Manifold Learning*: SOM. <br/> | [democracy_index.ipynb](scripts/democracy_index.ipynb){:target="_blank"} [democracy_index.csv](scripts/democracy_index.csv){:target="_blank"}
  L3       | 02.03.2023   | Lista 03.                                  | [Lista 03](listas/lista03.pdf){:target="_blank"} [wine.csv](listas/wine.csv){:target="_blank"} [hpi-data-2016.xlsx](listas/hpi-data-2016.xlsx){:target="_blank"} <br/> **Fecha de Entrega: martes 14 de marzo.** 
  15        | 07.03.2023   | *Clustering*. Agrupamiento jerárquico. <br/> [Aula 12](aulas/Aula12.pdf){:target="_blank"}  |  
  16        | 09.03.2023   | Ejemplos de agrupamiento jerárquico. <br/>   | Ver *aula13.ipynb*. 
  17        | 14.03.2023   | K-means, K-medians, y K-medoids. <br/> [Aula 14](aulas/Aula14.pdf){:target="_blank"}  |  
  18        | 16.03.2023   | Ejemplos de K-means. <br/>   | Ver *aula15.ipynb*. 
  19        | 21.03.2023   | Métodos basados en densidad. <br/> [Aula 16](aulas/Aula16.pdf){:target="_blank"} | Ver *density-based.ipynb*, *comparison.ipynb*. 
  20        | 23.03.2023   | Métricas para algoritmos de agrupamiento. <br/> [Aula 17](aulas/Aula17.pdf){:target="_blank"} | Ver *clustering-metrics.ipynb*, *silhouette.ipynb*. 
  21        | 28.03.2023   | Regresión Logística. <br/> [Aula 18](aulas/Aula18.pdf){:target="_blank"} | Ver *logistic.ipynb*. 
  22        | 11.04.2023   | Presentaciones primer proyecto.        | 
  23        | 13.04.2023   | Presentaciones primer proyecto.        | 
  24        | 18.04.2023   | K-vecinos más cercanos *KNN*. <br/> [Aula 19](aulas/Aula19.pdf){:target="_blank"} | Ver *knn.ipynb*. 
  25        | 20.04.2023   | Probabilidad condicional. Regla de Bayes.  |
  26        | 25.04.2023   | Clasificador *Naïve* Bayes. <br/> [Aula 20](aulas/Aula20.pdf){:target="_blank"} | Ver *bayes.ipynb*. 
  27        | 27.04.2023   | Redes Neuronales: Historia. Redes multicapa. <br/> [Aula 21](aulas/Aula21.pdf){:target="_blank"} | 
  28        | 02.05.2023   | Implementación en Keras. Ejemplo de red multicapa. <br/> |  [Day1.rar](scripts/Day1.rar){:target="_blank"} <br/> [Tensorflow Playground](https://playground.tensorflow.org/){:target="_blank"}
  29        | 04.05.2023   | Redes multicapa. *Stochastic gradient descent* vs. *Batch gradient descent*. Optimizadores. | [_Example1.ipynb](scripts/_Example1.ipynb){:target="_blank"} <br/> [https://www.ruder.io/optimizing-gradient-descent/](https://www.ruder.io/optimizing-gradient-descent/){:target="_blank"}
 

# Material adicional (scripts)
<div id='id-labs'/>

  **No.**  | **Fecha**    | **Tópicos**                                                         | **Material**
  -------- | ------------ | ------------------------------------------------------------------- |  -------------------------------------
  00       | 12.01.2023   | Instalación de librerías y ambiente de trabajo Python Anaconda, Jupyter-lab.  | [Anaconda+Tensorflow+Jupyter installation guide](otros/Anaconda+Tensorflow+Jupyter_installation_guide.pdf){:target="_blank"} <br/> *Archivos auxiliares:* [plotmatrix.py](otros/plotmatrix.py){:target="_blank"} [test.ipynb](otros/test.ipynb){:target="_blank"}
  04       | 24.01.2023   | Generación de muestras aleatorias en Python. Histogramas, densidad y distribución. | [aula04.ipynb](scripts/aula04.ipynb){:target="_blank"}
  05       | 26.01.2023   | Exploración de datos (EDA). Gráficos y otros plots. | [aula05.ipynb](scripts/aula05.ipynb){:target="_blank"}
  06       | 31.01.2023   | Distribuciones multivariadas. Covarianza, correlación. Entropía. | [aula06a.ipynb](scripts/aula06a.ipynb){:target="_blank"} [aula06b.ipynb](scripts/aula06b.ipynb){:target="_blank"}
  07       | 07.02.2023   | Descomposición SVD de matrices. | [aula07.ipynb](scripts/aula07.ipynb){:target="_blank"}
  08       | 09.02.2023   | Análisis de componentes. Ejemplo con datos de deportes. | [aula08.ipynb](scripts/aula08.ipynb){:target="_blank"} [deport.csv](scripts/deport.csv){:target="_blank"}
  09       | 14.02.2023   | PCA en imágenes. Ejemplo de compresión de imágenes. | [aula09a.ipynb](scripts/aula09a.ipynb){:target="_blank"} [aula09b.ipynb](scripts/aula09b.ipynb){:target="_blank"} [quetzal.png](scripts/quetzal.png){:target="_blank"}
  10       | 16.02.2023   | Escalamiento multidimensional.                      | [aula10.ipynb](scripts/aula10.ipynb){:target="_blank"} 
  11       | 21.02.2023   | Kernel PCA, y extensiones.                          | [aula11.ipynb](scripts/aula11.ipynb){:target="_blank"} 
  12       | 23.02.2023   | *Manifold Learning*: UMap, t-SNE, IsoMap.           | [aula12a.ipynb](scripts/aula12a.ipynb){:target="_blank"} [aula12b.ipynb](scripts/aula12b.ipynb){:target="_blank"} 
  13       | 28.02.2023   | Ejemplo de SOM con pingüinos.                       | [aula13.ipynb](scripts/aula13.ipynb){:target="_blank"}  
  14       | 09.03.2023   | Ejemplos de agrupamiento jerárquico.                | [aula14.ipynb](scripts/aula14.ipynb){:target="_blank"} [horse.jpg](scripts/horse.jpg){:target="_blank"} [tree.jpg](scripts/tree.jpg){:target="_blank"}
  15       | 16.03.2023   | Ejemplo de k-means.                                 | [aula15.ipynb](scripts/aula15.ipynb){:target="_blank"} [horse.jpg](scripts/horse.jpg){:target="_blank"} [tree.jpg](scripts/tree.jpg){:target="_blank"}
  16       | 21.03.2023   | Métodos basados en densidad: Mean-Shift, DBSCAN, OPTICS, BIRCH. | [density-based.ipynb](scripts/density-based.ipynb){:target="_blank"} [comparison.ipynb](scripts/comparison.ipynb){:target="_blank"} 
  17       | 23.03.2023   | Métricas para algoritmos de agrupamiento. | [clustering-metrics.ipynb](scripts/clustering-metrics.ipynb){:target="_blank"} [silhouette.ipynb](scripts/silhouette.ipynb){:target="_blank"} 
  18       | 28.03.2023   | Ejemplo de regresión logística. | [logistic.ipynb](scripts/logistic.ipynb){:target="_blank"} 
  19       | 18.04.2023   | Ejemplo de clasificador KNN. | [knn.ipynb](scripts/knn.ipynb){:target="_blank"} 
  

# Primer Proyecto
<div id='id-prj1'/>

Análisis de datos de EcoBici / Análisis de datos SP500. <br/>
Recursos: <br/>
Sitio web oficial de EcoBici [https://www.ecobici.cdmx.gob.mx/](https://www.ecobici.cdmx.gob.mx/){:target="_blank"} <br/>
Datos abiertos [https://www.ecobici.cdmx.gob.mx/es/informacion-del-servicio/open-data](https://www.ecobici.cdmx.gob.mx/es/informacion-del-servicio/open-data){:target="_blank"}

Sitio de Kaggle con los datos FAANG [https://www.kaggle.com/datasets/suddharshan/historical-stock-price-of-10-popular-companies](https://www.kaggle.com/datasets/suddharshan/historical-stock-price-of-10-popular-companies){:target="_blank"} <br/>
Sitio de Kaggle con los datos SP500 [https://www.kaggle.com/code/thomasrahman/s-p-500-5-stock-data-kmeans-clustering](https://www.kaggle.com/code/thomasrahman/s-p-500-5-stock-data-kmeans-clustering){:target="_blank"}


  **No.**  | **Fecha**    | **Tópicos**                                                         | **Material**
  -------- | ------------ | ------------------------------------------------------------------- |  -------------------------------------
  P1       | 07.03.2023   | Aviso del primer proyecto <br/> [Proyecto 1](proyecto/Proyecto1_2023.pdf){:target="_blank"} | Coordenadas de estaciones <br/> [stations.json](proyecto/stations.json){:target="_blank"} [stations.csv](proyecto/stations.csv){:target="_blank"}  
  .        | 11.04.2023   | Presentaciones                                                      | 
  .        | 13.04.2023   | Presentaciones                                                      | 
  .        | 14.04.2023   | Entrega del reporte, código y presentación.                         | 


# Presentaciones del primer proyecto
<div id='id-sem1'/>

  **No.**  | **Fecha**    | **Expositores**                                                            | **Tópicos**
  -------- | ------------ | -------------------------------------------------------------------------- | -------------------------------------
  01       | 11.04.2021   | Pedro Pablo Beltranena, Andrés Martínez, Nickolas Nolte, Esteban Samayoa   | S&P 500 <br/> [Presentación](proyecto1/S&P500.pdf){:target="_blank"}
  02       | 11.04.2021   | Cruz Del Cid, Daniel Behar, Javier Mazariegos, Marcela Melgar              | Ecobici <br/> [Presentación](proyecto1/Ecobici.pdf){:target="_blank"}
  03       | 13.04.2021   | Carlos Alvarado, Mario Pisquiy, Luz Arévalo, Lorena Pérez                  | FAANG+5 Companies <br/> [Presentación](proyecto1/Faang.pdf){:target="_blank"}


# Segundo Proyecto
<div id='id-prj2'/>

Tema Libre. <br/>
Recursos: Buscar repositorios de Machine Learning, de Bases de datos o Competencias (e.g. Kaggle), para tomar ideas de proyectos. <br/>

  **No.**  | **Fecha**       | **Tópicos**                                                         | **Material**
  -------- | --------------- | ------------------------------------------------------------------- |  -------------------------------------
  P2       | 13.04.2023      | Aviso del segundo proyecto <br/> [Proyecto 2](proyecto/Proyecto2_2023.pdf){:target="_blank"} |  
  .        | 28.04.2023      | Último día para tener elegido tema y datos.                         | 
  .        | 11.05.2023      | Entrega de borrador del proyecto.                                   | 
  .        | 18.05.2023      | Presentaciones                                                      | 
  .        | 19.05.2023      | Entrega del reporte, código y presentación.                         | 


# Referencias
<div id='id-ref'/>

### Textos:

* [R. Duda, P. Hart, D. Stork (2000). *Pattern classification*.](http://library.lol/main/5858DCFE63D714C5C42F433D5F821631){:target="_blank"}

* [C. Bishop (2000). *Pattern Recognition and Machine Learning*.](http://library.lol/main/B616EF565E2D48AE23EE2E19D7B0ADD2){:target="_blank"}

* [T. Hastie, R. Tibshirani, J. Friedman (2013). *The Elements of Statistical Learning*.](http://library.lol/main/5F88A9F135B7AB31FBCF1729412560DC){:target="_blank"}

* [K. Murphy (2012). *Machine Learning: a Probabilistic Perspective*.](http://library.lol/main/8ECFEEB2E1F9A19C770FBA1FF85FA566){:target="_blank"}

### Referencias adicionales:

* [K.-L. Chung (2000). *A Course in Probability Theory*](http://library.lol/main/6B122D4F68618DB5F1893F0296CB2491){:target="_blank"}

* [M. Lefebvre (2011). *Basic Probability with Applications*](http://library.lol/main/F3B9314CA31E0289D5FCD6EEDA01308A){:target="_blank"}

* [G. James, D. Witten, T. Hastie, R. Tibshirani (2008). *An Introduction to Statistical Learning with Applications in R*.](http://library.lol/main/1E48B8220FEE4CD9D192F4ED5020F2DA){:target="_blank"}

* [A. Izenman (2008). *Modern Multivariate Statistical Techniques: Regression, Classification and Manifold Learning*.](http://library.lol/main/B5E1DA4CD9133B468CA730402BBC7117){:target="_blank"}

* [B. Everitt, T. Hothorn (2011). *An Introduction to Applied Multivariate Analysis with R*](http://library.lol/main/83BD38DABC018FE79C6AEEF726BF20D7){:target="_blank"}

* [K. Fukunaga (1990). *Introduction to Statistical Pattern Recognition*.](http://library.lol/main/F1FC9B38F5E9F245C7CDE3AFEDED4D06){:target="_blank"}

* [C. Giraud (2015). *Introduction to High-Dimensional Statistics*.](http://library.lol/main/38E216C9EFA26C09F5A2324BC3122F92){:target="_blank"}

* [L. Devroye, L. Györfi, G. Lugosi (1996). *A Probabilistic Theory of Pattern Recognition*.](http://library.lol/main/60F75D016A9C96D67D752536B9D1753A){:target="_blank"}


### Artículos:

* [A. S. Bandeira (2016). *Ten Lectures and Forty-Two Open Problems in the Mathematics of Data Science*.](https://people.math.ethz.ch/~abandeira/TenLecturesFortyTwoProblems.pdf){:target="_blank"}

---
