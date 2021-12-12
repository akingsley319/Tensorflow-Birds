This project is designed for the purposes of a Deep Learning class project for Regis University. The project files themselves are stored in the "notebooks/" directory and consist of a data analysis file ("EDA.ipynb"), a tensorflow neural network trained for the dataset ("FinalModel.ipynb"), a file used to select said neural network ("ModelSelection.ipynb"), and a file designed to handle the incoming .zip file that contains the data for the neural network ("UnzipArchive.ipynb"). The input folder is the designated folder into which the data will be stored and must be created in order to duplicate this project. The data is not included due to the size of the file, which exceeds limits set by GitHub on file size.

The data can be found at https://www.kaggle.com/gpiosenka/100-bird-species. This dataset contains images of 315 different bird species, labeled and separated into test, validation, and test directories. These sets are explored briefly in "EDA.ipynb". These files are used in the neural network. The purpose is to achieve the highest possible accuracy within one week's time. The goal is to reach at least 95% accuracy, which is considered "moderately robust" by the Kaggle administrator.

In order to properly run this file, the data must be introduced into the environment into the "notebooks/input/" directory. If the file was introduced zipped, create the input directory insert the zipped file (titled as "archive.zip") into the "notebooks/" directory and run the "UnzipArchive.ipynb" file.

The final model is contained in "FinalModel.ipynb". Brief model testing is done in "ModelSelection.ipynb".

All of these steps were done spearately for the purpose of keeping the workspace as compact as possible. This increases the ease of use for both myself and any observer.

These files were constructed and tested in a Docker container (version 20.10.10) using Ubuntu 20.04 LTS as the development environment. All work was managed using JupyterLabs and GitHub was used for version control. Bugs in the WSL2 system hindered full gpu support for tensorflow, but the project was still possible using the CPU.
