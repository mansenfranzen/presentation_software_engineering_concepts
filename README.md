# Software engineering concepts for non-techies

This repository contains a jupyter-notebook based presentation regarding software engineering concepts.

It is a non-technical talk about technical things for non-technical audience. It focuses on the actual problem being solved while hiding technical details to emphasize the added value of each concept.

## Usage

### Modify

To edit the existing presentation, you'll require a python environment with either jupyter-notebook or jupyter-lab:

```console
conda create -n presentation_software_engineering_concept python=3.9 jupyterlab -c conda-forge
conda activate presentation_software_engineering_concept

git clone https://github.com/mansenfranzen/presentation_software_engineering_concepts.git
cd presentation_software_engineering_concepts

jupyter lab
```

### Generate

Activate a python environment with jupyter installed in the current repository and execute the following:

```console
jupyter nbconvert LearningSoftwareEngineeringConcepts.ipynb --to slides --reveal-prefix "https://unpkg.com/reveal.js@4.0.2"
```
