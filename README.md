{{CLASIFICACION DE LA CATEGORIA DE ENTORNO DE CALIAD DE VIDA}}
==============================

{{Objetivo:

Utilizando técnicas de machine learning, este proyecto tiene como objetivo desarrollar un modelo capaz de clasificar La Categoria del Entorno de Calidad de Vida basándose en las siguientes variables: espacios verdes, transporte público, industrias, la existencia de cavas, y el nivel de riesgo de inundación. 
La combinación de estas variables da como resultado la clasificación del Índice de Entorno.

Contexto del Problema:
La Categoria del Entorno de Calidad de Vida es una medida fundamental para evaluar el bienestar de la población en áreas urbanas. Mejorar la calidad de vida no solo beneficia a sus habitantes directos, sino que también contribuye al desarrollo socioeconómico y ambiental más amplio de la zona

Interrogantes de estudio:
Algunas de las preguntas que intenta responder este trabajo son:
1. ¿Con qué precisión puede un modelo de aprendizaje automático 
clasificar el Índice de Entorno de Calidad de Vida utilizando las variables 
seleccionadas?
2. ¿Cuáles variables tienen el impacto más significativo en la clasificación?
3. ¿Puede el modelo identificar áreas urbanas específicas que necesitan 
mejoras para aumentar la calidad de vida?

Descripción del Índice de Entorno:
Es un índice en el que se incorporan indicadores, del ambiente que rodea a la 
población, vinculados a servicios públicos, eventos climáticos o intervenciones 
humanas, que aportan, positiva o negativamente, a la calidad de vida. Estos 
indicadores son: espacios verdes públicos, cavas, transporte público, industrias 
y riesgo por inundación.

Relevancia:
Este índice apunta a relevar las características de aquella porción del ambiente 
que interactúa significativamente con la población en su lugar de residencia, 
incidiendo en su calidad de vida. Para ello evalúa una serie de elementos (de 
orden social, productivo, cultural y físico natural) presentes en el territorio.

Alcance (qué mide el índice):
El Índice mide el nivel de condiciones (vinculadas al entorno) de bienestar 
general que ofrece el Estado a la población, en un radio censal determinado.

}}

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
