# Cookiecutter 

_Standard project to clone and reuse (based on cookiecutter-datascience)_

Directly taken from [cookiecutter-data-science](https://github.com/drivendata/cookiecutter-data-science).


### Requirements to use the cookiecutter template:

 - Python >=3.5
 - [Cookiecutter Python package](http://cookiecutter.readthedocs.org/en/latest/installation.html) >= 1.4.0: 
This can be installed with pip by or conda depending on how you manage your Python packages:

``` bash
$ pip install cookiecutter
```

ou

``` bash
$ conda config --add channels conda-forge
$ conda install cookiecutter
```


### To start a new project, run:

    cookiecutter https://gitlab.com/raphaele_adjerad/cookiecutter/

### The resulting directory structure
 
```
├── data
│   ├── raw                 <- The original, immutable data dump.
│   ├── interim             <- Intermediate data that has been transformed.
│   ├── processed           <- The final, canonical data sets for modeling.
│   ├── output              <- Output from models
│   ├── schemas             <- Raw and processed data schemas, based on Table Schema standard
|
├── documentation           <- Documentation for the project
|
├── notebooks               <- Notebooks Jupyter (only include jupytext --to .py version of notebooks) 
|
├── reports                 <- Generated analysis as HTML, PDF, LaTeX, etc.
│   └── figures             <- Generated graphics and figures to be used in reporting
|
├── setup.py                <- makes project pip installable (pip install -e .) so src can be imported
├── src                     <- Source code
│   ├── __init__.py         <- Makes src a Python module
|
├── tests                   <- Tests for our projet
|            
├── LICENCE.txt
├── README.md
├── requirements.txt        <- The requirements file for reproducing the analysis environment, e.g.
    │                         generated with `pip freeze > requirements.txt`
```


