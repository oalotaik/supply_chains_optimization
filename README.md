## Necessary Packages
Python's random module + Pandas + Matplotlib + PuLP

## Motivation
This repository contains a series of Jupyter Notebooks dedicated to demonstrate how to mathematically model and optimize some typical supply chains problems using Python. Specifically, they give an introduction to using the PuLP framework, which is a Python framework for mathematical modeling and optimization.

## The PuLP Framework
[PuLP](https://pypi.org/project/PuLP/) is an LP modeler written in Python. PuLP can generate MPS or LP files and call GLPK, COIN CLP/CBC, CPLEX, and GUROBI to solve linear problems.

#### Installing PuLP using pip:
`pip install pulp`


## Files
1. images folder: contains some resource images used in some notebooks markdown cells
2. 6 jupyter notebooks: all notebooks are numbered and have self-explanatory names. It's better to follow the numbering in order to gradually learn the basics of PuLP. The last notebook `06_case_study_capacitated_plant_location.ipynb` is a case study that puts together all the concepts in one place.

## Acknowledgement
These notebooks are basically my notes from the online course "Supply Chains Analytics in Python" that I took at DataCamp.com. So, thanks go to the instructor of that course.
