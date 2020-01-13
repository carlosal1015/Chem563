
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/DPotoyan/Chem563/master)

# Materials for the course Chem563: Statistical Mechanics, ISU Spring 2020 

**Instructor:** Davit Potoyan

---

### 0. What is in this repository?

This repository contains computational notebooks for the course Chem563 Intro to Stat Mech taught at Iowa State University. The content is broken up into (hopefully) self-contained units organized by a distinct topic. Inside each unit you will find the following materials:

1. Lecture slides giving brief summary of key ideas and equation. This is for quick reviewing of discussed material.
2. PDF files of relevant research papers, book chapters and other extra reading material. This is for bedtime reading.  
3. Jupyter-notebooks `notebook.ipynb` and some `file.py`  files containing short snippets for doing various numerical experiments.

### 1. How to run notebooks?

We will use JupyterHub at ISU with environment and all relevant python package conveniently pre-installed for us. <br>**Login [here](https://www.hpc.iastate.edu/guides/classroom-hpc-cluster/jupyterhub) and start running notebooks.** Alternatively you have the following options:

- Launch the binder and run the notebooks in the cloud (change won't be saved unless you download notebooks).

- Download files, create a separate conda environment using `enviroanment.yml` and run notebooks locally in your computer.


### 2. How to use git to update local copy of the repository

We will be adding new material and folders will be populated with new notebooks as we go through the course. 

For the first time clone course repository repository
```bash
$ git clone https://github.com/DPotoyan/Chem563.git
```
A new folder called Chem563 will be created. Enter it and run `jupyter-notebook` or `jupyter-lab`
```bash
$ cd Chem563/
$ jupyter-notebok 
```

To update your local copy do the following: 

```bash
$ cd  Chem563/
$ git pull
```
If you want to save change to your notebooks/files make sure to **rename them**  to avoid overwritting.

### 
