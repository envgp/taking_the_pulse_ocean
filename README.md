
**[summary](#summary) | [prerequisites](#prerequisites) | [setup](#setup) | [resources](#resources) | [license](#license)**
# Taking the Pulse of the Planet - Atmosphere
[![License](https://img.shields.io/github/license/envgp/taking_the_pulse_atmosphere.svg)](https://github.com/envgp/taking_the_pulse_atmosphere/blob/main/LICENSE)
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/envgp/taking_the_pulse_atmosphere/HEAD?labpath=.%2Fnotebooks)

This repository contains a set of Jupyter notebooks used for an undergraduate course in Stanford Sustainability School: Taking the Pulse of the Planet; a specific module of the course - `Atmosphere` is provided.



## Prerequisites

**Software**

* Some knowledge of Python is assumed.
* All coding will be done in Jupyter notebooks. I'll explain how they work
  briefly but it will help if you've used them before.
* We'll use [numpy](https://numpy.org/), [matplotlib](https://matplotlib.org/), and
  [ipywidgets](https://ipywidgets.readthedocs.io/)
  You don't need to be an expert in these tools but some familiarity will help.

**XXX METHODS USED?**
* Some comments?

### Step 1: Python

**Follow the general instructions for installing Anaconda:** https://www.youtube.com/playlist?list=PLgLft9vxdduAW-jmhYqXvtfGYJS6v2FjM

This will get you a working Python 3 installation with the `conda` package
manager. If you already have one, you can skip this step.

### Step 2: Download the Jupyter notebooks

To access the notebooks, you need to use git to clone this repository

To clone this repository, open up a terminal and navigate to where you want this repository stored on your computer.

Then run
```
git clone https://github.com/envgp/taking_the_pulse_atmosphere.git
```
to clone the repository, and `cd` into the `taking_the_pulse_atmosphere` directory
```
cd taking_the_pulse_atmosphere
```

### Step 3: Create `tpop_atmosphere` conda environment

From inside of the `taking_the_pulse_atmosphere` repository, create the `tpop_atmosphere` conda environment
```
conda env create -f environment.yml
```
and activate the environment
```
conda activate tpop_atmosphere
```

### Step 4: Launching the notebooks

Once you have activated the conda environment, you can launch the notebooks
```
jupyter notebook
```
Jupyter will then launch in your web-browser.

If you are able to open any one of the notebooks and run the first cell, then you should be good to go!

## License

All code and text in this repository is free software: you can redistribute it and/or
modify it under the terms of the MIT License.
A copy of this license is provided in [LICENSE](LICENSE).
