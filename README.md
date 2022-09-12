# Cookiecutter MCON 
_derived from Cookiebutter Data Science (https://github.com/drivendata/cookiecutter-data-science)

_A logical, reasonably standardized, but flexible project structure for doing and sharing data science work._

### Requirements to use the cookiecutter template:
-----------
 - Python 2.7 or 3.5+
 - [Cookiecutter Python package](http://cookiecutter.readthedocs.org/en/latest/installation.html) >= 1.4.0: This can be installed with pip by or conda depending on how you manage your Python packages:

``` bash
$ pip install cookiecutter
```

or

``` bash
$ conda config --add channels conda-forge
$ conda install cookiecutter
```


### To start a new project, run:
------------

    cookiecutter https://github.com/klageand/cookiecutter-mcon

This will create a new project in the current directory and add this cookiecutter template to C:\\Users\\user\\.cookiecutters\\.

If cookiecutter-mcon already exists there, it is enough to run:
    
    cookiecutter cookiecutter-mcon

This will create a new project in the current directory.

### The resulting directory structure:
------------

The directory structure of your new project looks like this: 

```
├── LICENSE
├── Makefile           <- Makefile with commands like `make data` or `make train`
├── README.md          <- The top-level README for developers using this project.
├── data (added to gitignore)
│   └── raw
│   ├── intermediate
│   ├── processed
│   ├── temp
├── results (added to gitignore)
│   ├── outputs
│   ├── models
├── documents
│   ├── docs
│   ├── images
│   └── references
├── notebooks               <- notebooks for explorations / prototyping
└── src                     <- all source code, internal org as needed
│   └── misc
│   └── terraform           <- terraform for model training with EC2
```
