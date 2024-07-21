
![Politecnico](https://github.com/Alemac22/INDICE-DE-ENTORNO-DE-CALIDAD-DE-VIDA/blob/main/reports/figures/Politecnico.jpg)

 **Carrera:** Tecnicatura Superior en Ciencia de Datos e Inteligencia Artificial.

 **Institucion:** Politécnico Malvinas Argentinas

 **Materia:** Aprendizaje Automático

 **Proyecto Aprendizaje Automatico:** Indice de Entorno de Calidad de Vida

 **Alumno:** Alejandro Maclean

 **Profesor de la Catedra:** Martin Mirabete

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=edfedo" alt="Vistas de perfil" />
  <a href="https://opensource.org/licenses/MIT">
    <img src="https://img.shields.io/badge/License-MIT-yellow.svg" alt="License: MIT" />
  </a>
</p>


CLASIFICACION DE LA CATEGORIA DE ENTORNO DE CALIDAD DE VIDA
==============================


**Objetivo:**

Utilizando técnicas de machine learning, este proyecto tiene como objetivo desarrollar un modelo capaz de clasificar La Categoria del Entorno de Calidad de Vida basándose en las siguientes variables: espacios verdes, transporte público, industrias, la existencia de cavas, y el nivel de riesgo de inundación. 
La combinación de estas variables da como resultado la clasificación del Índice de Entorno.

**Contexto del Problema:**

La Categoria del Entorno de Calidad de Vida es una medida fundamental para evaluar el bienestar de la población en áreas urbanas. Mejorar la calidad de vida no solo beneficia a sus habitantes directos, sino que también contribuye al desarrollo socioeconómico y ambiental más amplio de la zona

**Interrogantes de estudio:**

Algunas de las preguntas que intenta responder este trabajo son:

1. ¿Con qué precisión puede un modelo de aprendizaje automático 
clasificar el Índice de Entorno de Calidad de Vida utilizando las variables 
seleccionadas?
2. ¿Cuáles variables tienen el impacto más significativo en la clasificación?
3. ¿Puede el modelo identificar áreas urbanas específicas que necesitan 
mejoras para aumentar la calidad de vida?

**Descripción del Índice de Entorno:**

Es un índice en el que se incorporan indicadores, del ambiente que rodea a la 
población, vinculados a servicios públicos, eventos climáticos o intervenciones 
humanas, que aportan, positiva o negativamente, a la calidad de vida. Estos 
indicadores son: espacios verdes públicos, cavas, transporte público, industrias 
y riesgo por inundación.

**Relevancia:**

Este índice apunta a relevar las características de aquella porción del ambiente 
que interactúa significativamente con la población en su lugar de residencia, 
incidiendo en su calidad de vida. Para ello evalúa una serie de elementos (de 
orden social, productivo, cultural y físico natural) presentes en el territorio.

**Alcance (qué mide el índice):**

El Índice mide el nivel de condiciones (vinculadas al entorno) de bienestar 
general que ofrece el Estado a la población, en un radio censal determinado.


**Machine Learning for Classifying Quality of Life Environment Index**
	
This research paper analyzes the development of a machine learning system that is capable of classifying the Quality of Life Environment Index based on variables such as green spaces, public transportation, industries, the presence of quarries, and flood risk levels. This is useful to identify places that need to increase their Quality of Life. The aim of this research is to assess how accurately the model could classify the environment index and which variables would have the most significant impact. Methods include data collection, preprocessing, and the implementation of various machine learning algorithms, for example Linear Regression, Logistic Regression and Decision Tree. The data is processed by this algorithms to train the model, which classifies the environment index. The model is adjusted to improve accuracy. The results demostrate the model´s effectiveness in classifying the Quality of Life Environment Index, identifying significant variables such as green spaces and flood risk. Finally, the study suggests that machine learning models can effectively predict urban areas' quality of life with an accuracy of 98%, providing valuable insights for environmental development. This predictions can be used in real world, to benefit urban planification. 

**Video Presentacion:**  ![VIDEO](https://github.com/Alemac22/INDICE-DE-ENTORNO-DE-CALIDAD-DE-VIDA/blob/main/references/Video%20Presentacion.mp4)



Project Organization
------------

    ├── LICENSE
    ├── Makefile           <- Makefile with commands like `make data` or `make train`
    ├── README.md          <- The top-level README for developers using this project.
    ├── data
    │   ├── external       <- Data from third party sources.
    │   ├── interim        <- Intermediate data that has been transformed.
    │   ├── processed      <- The final, canonical data sets for modeling.
    │   └── raw            <- The original, immutable data dump.
    │
    ├── docs               <- A default Sphinx project; see sphinx-doc.org for details
    │
    ├── models             <- Trained and serialized models, model predictions, or model summaries
    │
    ├── notebooks          <- Jupyter notebooks. Naming convention is a number (for ordering),
    │                         the creator's initials, and a short `-` delimited description, e.g.
    │                         `1.0-jqp-initial-data-exploration`.
    │
    ├── references         <- Data dictionaries, manuals, and all other explanatory materials.
    │
    ├── reports            <- Generated analysis as HTML, PDF, LaTeX, etc.
    │   └── figures        <- Generated graphics and figures to be used in reporting
    │
    ├── requirements.txt   <- The requirements file for reproducing the analysis environment, e.g.
    │                         generated with `pip freeze > requirements.txt`
    │
    ├── setup.py           <- makes project pip installable (pip install -e .) so src can be imported
    ├── src                <- Source code for use in this project.
    │   ├── __init__.py    <- Makes src a Python module
    │   │
    │   ├── data           <- Scripts to download or generate data
    │   │   └── make_dataset.py
    │   │
    │   ├── features       <- Scripts to turn raw data into features for modeling
    │   │   └── build_features.py
    │   │
    │   ├── models         <- Scripts to train models and then use trained models to make
    │   │   │                 predictions
    │   │   ├── predict_model.py
    │   │   └── train_model.py
    │   │
    │   └── visualization  <- Scripts to create exploratory and results oriented visualizations
    │       └── visualize.py
    │
    └── tox.ini            <- tox file with settings for running tox; see tox.readthedocs.io


--------

<p><small>Project based on the <a target="_blank" href="https://drivendata.github.io/cookiecutter-data-science/">cookiecutter data science project template</a>. #cookiecutterdatascience</small></p>
