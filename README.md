# Tensorflow-Birds
# Tensorflow-Birds

This project is designed for the purposes of a Deep Learning class project for Regis University. The project files themselves are stored in the "notebooks/" directory and consist of an data analysis file ("EDA.ipynb"), a tensorflow neural network trained for the dataset (" "), and a file designed to handle the incoming .zip file that contains the data for the neural network ("UnzipArchive.ipynb"). The input folder is the designated folder into which the data will be stored. The data is not included due to the size of the file, which exceeds limits set by GitHub on file size.

The data can be found at https://www.kaggle.com/gpiosenka/100-bird-species. This dataset contains images of 351 different bird species, labelled and separated into test, validation, and test directories. These sets are explored briefly in "EDA.ipynb". These files are used in the neural network. The purpose is to achieve the highest possible accuracy within one week's time.

In order to properly run this file, the data must be introduced into the environment into the "notebooks/input/" directory. If the file was introduced zipped, introduce the zipped file into the "notebooks/" directory titled as "archive.zip" and run the "UnzipArchive.ipynb" file.

These files were constructed and tested in a Docker container (version 20.10.10) using Ubuntu 20.04 LTS as the development environment. All work was managed using JupyterLabs and GitHub was used for version control.
