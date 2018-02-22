# VSPy

A Python Extension to the C-Munipack Project to assist in identification of variable stars. 

**THIS PROJECT IS STILL UNDER DEVELOPMENT**.

## Table of Contents

* `NGC2180`: Contains Data Sets currently being analyzed for variability
* `Notebooks`: Holds source code for VSPy.
* `Muniwin_Projects`: Holds Munipack Projects for NGC 2180 Projects.
* `docs`: Contains documentation on functions and usage of project.

## Why?
This Project is part of the Astronomy Research Class at Phillips Academy Andover. The purpose of this project is to develop a system that would allow users to easily discover and identify existing and new variable stars in a given set of images. This library is based off of the [C-Munipack Project](http://c-munipack.sourceforge.net/). The goal of this project to provide a machine learning solution to the discovery of variable stars.
 

### What does this project do
* **Compile SQLite DB of Light Curves of Stars in Fields**. Using Munipack, the magnitude of all stars are compiled into light curves, which both the data and the light curves are stored in a SQLite DB.

* **Determine the Period of Variable Stars**: For each star in the database, the program will calculate the periodogram and find the most significant period.
 
* **Correlate Data found in images with Online DBs**: This project connects your data to data from Catalina Sky Survey, SIMBAD, and more to add more data to light curves.

* **Identify and Classify Variable Stars**: This project aims to use statistical analysis and machine learning to classify the light curves as variable and type of variability.

* **View FITS Images**


