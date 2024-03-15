# EDA_penguins

**Version**: 1.0
**Author**: pahoalapizco


Exploratory Data Analysis of palmer penguins data set, this project is part of the course ["Análisis exploratorio de datos"](https://platzi.com/cursos/analisis-exploratorio-datos/) by [Platzi](https://www.platzi.com).

## Prerequisites
- Anaconda >=4.x 

## Create environment
```bash
conda env create -f environment environment.yml
activate eda_penguins
```
## Run project as a module
```bash
pip install --editable .
```

## Project organisation
```

## Project organization

    eda_penguins
        ├── data
        │   ├── processed      <- The final, canonical data sets for modeling.
        │   └── raw            <- The original, immutable data dump.
        │
        ├── notebooks          <- Jupyter notebooks. Naming convention is a number (for ordering),
        │                         the creator's initials, and a short `-` delimited description, e.g.
        │                         `1.0-jvelezmagic-initial-data-exploration`.
        │
        ├── .gitignore         <- Files to ignore by `git`.
        │
        ├── environment.yml    <- The requirements file for reproducing the analysis environment.
        │
        └── README.md          <- The top-level README for developers using this project.

---