# Clasificador Naive Bayes de relatos paranormales

Se desarrolló un clasificador Naïve Bayes con el propósito de 
categorizar relatos de fenómenos paranormales obtenidos mediante web 
scraping del portal [*Your Ghost Stories*](https://www.yourghoststories.com/).  
A partir de los textos recolectados se construyó una matriz dispersa 
(sparse matrix), sobre la cual se evaluaron diferentes 
variantes del clasificador (gaussiano y Poisson). Se aplicó 
*cross-validation* para determinar el valor óptimo del hiperparámetro 
de **Laplace smoothing**.  
El repositorio incluye el código reproducible, los resultados 
obtenidos y un artículo que documenta los métodos y las conclusiones 
principales.  

## Objetivo
El objetivo de este proyecto es clasificar relatos de fenómenos 
paranormales (por ejemplo: *Apparitions / Voices / Touches*, 
*Haunted Places*, entre otros) utilizando el modelo Naïve Bayes. 
Se comparan diferentes variantes del clasificador y se dicotomizó los datos
para obtener un mejor clasificador.

## Herramientas
- **Lenguaje de programación:** R  
- **Librerías principales:**  
  - `rvest` y `robotstxt` para web scraping.  
  - `tidyverse`, `tidytext` y `stringr` para manipulación y limpieza de texto.  
  - `caret` y `tidymodels` para evaluación de modelos y split de los datos.
  - `naivebayes` y `e1071` para implementación del clasificador
- SelectorGadget para la estructura html de la pagina web


## Colaboradores
- [@olivercasas17](https://github.com/olivercasas17)  
- [@ErikJajan](https://github.com/ErikJajan)  
- [@JoseLuis-tsm](https://github.com/JoseLuis-tsm)  

