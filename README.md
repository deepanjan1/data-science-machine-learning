# data-science-machine-learning
My solution set for Udemy's Python for Data Science and Machine Learning Bootcamp.  The Anaconda package manager was used for all exercises.  Files are in Jupyter Notebooks.

## Setup

#### Installation
Anaconda was installed from [here (version:  Python 3.7)](https://www.anaconda.com/distribution/).  This was all done on Mac OS via a terminal setup.

#### Switching to Conda environment
Switching to the `base` environment to run conda commands can be done as follows with <user_name> being your user directory:
`source /Users/<user_name>/anaconda3/bin/activate`

#### Creating a Conda virtual environment
To keep all the work in a separate virtual environment, create a virtual environment using the conda packager.  Steps are below:
```
# Creating a virtual environment
conda create --name <virtualenv> <packages>

# install packages
conda install <package>

# Info on virtual environments
conda info --envs

# Activate environment
conda activate <virtualenv>

# Deactivate environment
conda deactivate
```