# Cystic-Fibrosis-research-analysis
These programs visualize world-class repeated measures microbiome data from a cohort of well-characterized children with Cystic Fibrosis. Although these programs were applied to the real-life settings of Cystic Fibrosis, the theoretical framework it is based upon is applicable to a wide range of other studies featuring longitudinal microbiome data. 

# About This Repository
This repository is intended to be a plain-English explanation of how to implement longitudinal microbiome analyses, using readily available software packages. Microbiome data is notoriously challenging to work with, and traditional statistical methods often fall short. For example, the frequent use of relative abundance data can cause different bacteria to appear to be correlated simply because the relative abundances must sum to 1. Therefore, I used several custom software programs specifically designed to be used with this data type. 

# The Programs
The programs in this repository are written in Python 2.7 and Python 3.7.3 with Jupyter Notebook, and they visualize the output from two of the software programs I used: the [TIME Web application](https://web.rniapps.net/time/index.php) and [GP Microbiome](https://github.com/tare/GPMicrobiome), a Python-based program available here on GitHub. Programs are in Python 3.7.3 unless otherwise specified. They were written on a Windows 10 computer.

The files are Jupyter (IPython) notebooks (.ipynb files). You can view them here on GitHub, go to Jupyter's [nbviewer](https://nbviewer.jupyter.org/) website and enter the web address, or click on the file name in the index below to go directly to the file on nbviewer. If you want to *run* the notebooks, not just view them, you can clone or download the project, or you can run all the notebooks online by clicking this link: [Binder](https://mybinder.org/v2/gh/V-Talbot/Cystic-Fibrosis-research-analysis/master)

# Index of Jupyter (IPython) Notebooks
## Python 2.7 
[readsample27](https://nbviewer.jupyter.org/github/V-Talbot/Cystic-Fibrosis-research-analysis/blob/master/readsample27.ipynb): Written for Python 2.7, this program reads the output from GP Microbiome and creates, then saves, csv files for further analysis with Python 3.7 later.

## Python 3.7

### Programs Which Create Files for Use as Input in Other Programs

### Plotting Programs for GP Microbiome Output

### Box Plots of TIME Output


# The Example Data

I have provided example data so that anyone can run my programs. 

The example data for the TIME output box plots came from running Workflow 5b on example data available from the [TIME Web application](https://web.rniapps.net/time/index.php) and saving the results. See the box plot programs for more information on this files and how I downloaded them from TIME. I encourage users to visit the TIME site and play with thieir various example analyses. Then you can either download the files in the same way that I did (as specified in the box plot programs) or go to the 'Box Plot Data' folder, located in the 'Data' folder of this repository under 'Extras', where I have provided them.  

