# AGCC_pyforgeo
Introduction to Python for Geoscientists at the Australian Geoscience Council Convention 2018.

Friday 19th October 2018, 10am - 4pm.

Please arrive early if you need help setting up your Python environment or downloading this repository.

### Please note. This repo is being updated, you will need to download it again closer to the workshop.
 
## Workshop Description
Take your geoscience data management and analysis to the next level with an introduction to Python. Python has deservedly become a popular language for scientific computing. It has all the friendly features and conveniences you would expect of a modern programming language. It boasts a rich set of libraries used and developed by geoscientists for working with data. The Python programming language offers adaptability and versatility to the types of analyses, modelling, and workflows that geoscientists utilise.
 
## In this course you will learn:
* Basic programming concepts and techniques.
* Syntax, control statements, and Python data types.
* How to use well-developed libraries (e.g. Numpy, Scipy).
* Data frames and data wrangling using Pandas.
* Visualisation in Python using matplotlib
* Machine learning strategies from the scikit-learn library
 
We will teach the course using Jupyter notebooks, which allow Python code, results, visualisations and documentation to be blended seamlessly. This platform is perfect for sharing insights with others while producing reproducible research.
 

## Prerequisites 
Have Python 3 installed with these packages:
* jupyter 
* matplotlib
* numpy
* scipy
* scikit-learn
* pandas
* basemap
* pyshp
 
### Mac or Linux users

If you use the anaconda python package manager, this command should set up a correct environment for us to work in:
 
```conda create -n pyforgeo python=3.6 scipy=0.19 scikit-learn=0.18 matplotlib=2.0 pyshp=1.2 numpy=1.12 jupyter=1.0 basemap=1.0 pandas=0.20```

### Windows users

If you are using Anaconda on Windows, the Basemap package does not like Python 3. Use these lines to install from an Anaconda Prompt:

```conda create -n pyforgeo python=3.6 scipy=0.19 scikit-learn=0.18 matplotlib=2.0 pyshp=1.2 numpy=1.12 jupyter=1.0 pandas=0.20 ```

After the environment is installed, activate it:

```conda activate pyforgeo```

Then install basemap from an alternative source:

```conda install -c conda-forge basemap=1.0.8.dev0```

## Instructions
We will be working through a series of Jupyter Notebooks in the following order. 

* [Introduction](examples/Intro_Python_Geo.ipynb): A primer on Python, Jupyter, scripting, coding, plotting, everything!

* [Data Science for Geoscience](examples/ML_Geo.ipynb): An example that uses basic machine learning tools in the context of geoscience.


 
## Presenter Bios

**Nathaniel Butterworth**

nathaniel.butterworth@sydney.edu.au 

Nathaniel has worked as a postdoctoral research associate in the EarthByte group at the University of Sydney. Here he learned the crafts of data mining and machine learning on big data projects. Prior to this he completed a PhD in geosciences entitled, “The dynamics of subduction and its tectonic implications”. Before pursuing geophysics he received his BSc from the University of Wollongong in 2008 and his honours in astrophysics from the University of Sydney in 2009. Nathaniel, now with the Sydney Informatics Hub, trains researchers in data science and high-performance computing.
 
**Madhura Killedar**

madhura.killedar@sydney.edu.au

Dr Madhura Killedar is a data scientist at the Sydney Informatics Hub at the University of Sydney where she applies Bayesian and machine learning techniques to a range of disciplines from geoscience & paleo-climate to medical research, provides statistical consultation for graduate students, and helps teach programming courses in python and R. She received her PhD in physics in 2011, then conducted postdoctoral research in gravitational lensing, cosmology and astro-statistics in Italy and Germany. She has also worked in epidemiology and child nutrition developing computational models for the World Bank with a focus on optimising population health outcomes and uncertainty quantification, before moving to her current role.

 