# bicycles-seoul

<a target="_blank" href="https://cookiecutter-data-science.drivendata.org/">
    <img src="https://img.shields.io/badge/CCDS-Project%20template-328F97?logo=cookiecutter" />
</a>

Have you felt the Siberian winter in Seoul? Have you seen the smog 
that often descends on the city?

I have - and, as a cyclist, I know that weather and atmospheric pollution
are the two things that most influence whether I will get on a bike.

In this project, I try to improve on other analysts' scores for the 
Seoul bike hire dataset by introducing atmospheric pollution data 
from a weather station in central Seoul.

The Seoul bike hire dataset has been solved with an R squared of ~91%.
The standard dataset contains weather-related data, some time and date variables,
and the number of bikes hired in Seoul. The objective is to build a regression model
that predicts the number of bikes hired, given the weather and time variables.

A Seoul pollution dataset for the same time frame as the Seoul bike hire dataset
(2017-2019) is available on Kaggle. In this project, I bring the two together and then
build a regression model to try and beat an R squared of 91%.

My secondary objective is to use the CCDS project structure to create a project that is
clearly and cleanly organised.

## Project Organisation

```
├── LICENSE            <- MIT
├── README.md          <- The top-level README for developers using this project.
├── data
│   ├── external       <- Data from the Seoul pollution dataset
│   ├── interim        <- Data during transformation and preprocessing steps
│   ├── processed      <- The final data set for modeling
│   └── raw            <- The original Seoul bike hire dataset
│
├── docs               <- A default mkdocs project; see www.mkdocs.org for details
│
├── models             <- Trained models
│
├── notebooks          <- Jupyter notebooks. This is a notebook based project, so notebooks can be read in order.
│
├── pyproject.toml     <- Project configuration file with package metadata for 
│                         bicycles_seoul and configuration for tools
│
├── references         <- Data dictionaries, manuals, and all other explanatory materials.
│
├── requirements.txt   <- The requirements file for reproducing the analysis environment, e.g.
│                         generated with `pip freeze > requirements.txt`
│
├── setup.cfg          <- Configuration file for flake8
│
└── bicycles_seoul   <- Source code for use in this project.
    │
    ├── predictor     <- Home of the module files
    ├── models        <- Models for use in the Python module
```

--------

