# Cystic-Fibrosis-research-analysis
These programs visualize world-class repeated measures microbiome data from a cohort of well-characterized children with Cystic Fibrosis. Although these programs were applied to the real-life settings of Cystic Fibrosis, the theoretical framework it is based upon is applicable to a wide range of other studies featuring longitudinal microbiome data. 

# About This Repository
This repository is intended to be a plain-English explanation of how to implement longitudinal microbiome analyses, using readily available software packages. Microbiome data is notoriously challenging to work with, and traditional statistical methods often fall short. For example, the frequent use of relative abundance data can cause different bacteria to appear to be correlated simply because the relative abundances must sum to 1. Therefore, I used several custom software programs specifically designed to be used with this data type. 

# The Programs
The programs in this repository are written in Python 2.7 and Python 3.7 with Jupyter Notebook, and they visualize the output from two of the software programs I used: the [TIME Web application](https://web.rniapps.net/time/index.php) and [GP Microbiome](https://github.com/tare/GPMicrobiome), a Python-based program available here on GitHub. Programs are in Python 3.7 unless otherwise specified. They were written on a Windows 10 computer.

The programs are Jupyter (IPython) notebooks (.ipynb files). You can view them here on GitHub, go to Jupyter's [nbviewer](https://nbviewer.jupyter.org/) website and enter the web address, or click on the file name in the index below to go directly to the file on nbviewer. If you want to *run* the notebooks, not just view them, you can clone or download the project, you can run all the notebooks online using Binder, or you can run all the Python 3 notebooks online using Deepnote.
To access the entire repository on nbviewer, Binder, or Deepnote now, click the corresponding button below:
<br>

[<img align="right" height="30" src="https://beta.deepnote.org/buttons/launch-in-deepnote.svg">](https://beta.deepnote.com/project/69bbfe4c-3745-46a0-a989-e936ebb7fb85)[<img align="right" height="27" src="https://mybinder.org/badge_logo.svg">](https://mybinder.org/v2/gh/V-Talbot/Cystic-Fibrosis-research-analysis/master)[<img height="38" align="right" src="https://imgur.com/JUKXSK3.png">](https://nbviewer.jupyter.org/github/V-Talbot/Cystic-Fibrosis-research-analysis/tree/master/)
<br>

Alternatively, you can go to an individual notebook and click the corresponding button to access it directly on that site.

# Index of Jupyter (IPython) Notebooks
## Programs Which Create Files for Use as Input in Other Programs

### Python 2.7
### readsample27[<img align="right" height="30" src="https://beta.deepnote.org/buttons/launch-in-deepnote.svg">](https://beta.deepnote.com/project/69bbfe4c-3745-46a0-a989-e936ebb7fb85)[<img align="right" height="27" src="https://mybinder.org/badge_logo.svg">](https://mybinder.org/v2/gh/V-Talbot/Cystic-Fibrosis-research-analysis/master)[<img height="38" align="right" src="https://imgur.com/JUKXSK3.png">](https://nbviewer.jupyter.org/github/V-Talbot/Cystic-Fibrosis-research-analysis/blob/master/readsample27.ipynb)
Written for Python 2.7, this program reads the output from GP Microbiome and creates, then saves, csv files for further analysis with Python 3.7 later. 

### readsample27_with_151_edit[<img align="right" height="30" src="https://beta.deepnote.org/buttons/launch-in-deepnote.svg">](https://beta.deepnote.com/project/69bbfe4c-3745-46a0-a989-e936ebb7fb85)[<img align="right" height="27" src="https://mybinder.org/badge_logo.svg">](https://mybinder.org/v2/gh/V-Talbot/Cystic-Fibrosis-research-analysis/master)[<img height="38" align="right" src="https://imgur.com/JUKXSK3.png">](https://nbviewer.jupyter.org/github/V-Talbot/Cystic-Fibrosis-research-analysis/blob/master/readsample27_with_151_edit.ipynb)

### Python 3.7
### readsample37[<img align="right" height="30" src="https://beta.deepnote.org/buttons/launch-in-deepnote.svg">](https://beta.deepnote.com/project/69bbfe4c-3745-46a0-a989-e936ebb7fb85)[<img align="right" height="27" src="https://mybinder.org/badge_logo.svg">](https://mybinder.org/v2/gh/V-Talbot/Cystic-Fibrosis-research-analysis/master)[<img height="38" align="right" src="https://imgur.com/JUKXSK3.png">](https://nbviewer.jupyter.org/github/V-Talbot/Cystic-Fibrosis-research-analysis/blob/master/readsample37.ipynb)

### readsample37_with_151_edit[<img align="right" height="30" src="https://beta.deepnote.org/buttons/launch-in-deepnote.svg">](https://beta.deepnote.com/project/69bbfe4c-3745-46a0-a989-e936ebb7fb85)[<img align="right" height="27" src="https://mybinder.org/badge_logo.svg">](https://mybinder.org/v2/gh/V-Talbot/Cystic-Fibrosis-research-analysis/master)[<img height="38" align="right" src="https://imgur.com/JUKXSK3.png">](https://nbviewer.jupyter.org/github/V-Talbot/Cystic-Fibrosis-research-analysis/blob/master/readsample37_with_151_edit.ipynb)

### Create_relative_abundance_files[<img align="right" height="30" src="https://beta.deepnote.org/buttons/launch-in-deepnote.svg">](https://beta.deepnote.com/project/69bbfe4c-3745-46a0-a989-e936ebb7fb85)[<img align="right" height="27" src="https://mybinder.org/badge_logo.svg">](https://mybinder.org/v2/gh/V-Talbot/Cystic-Fibrosis-research-analysis/master)[<img height="38" align="right" src="https://imgur.com/JUKXSK3.png">](https://nbviewer.jupyter.org/github/V-Talbot/Cystic-Fibrosis-research-analysis/blob/master/Create_relative_abundance_files.ipynb)

### Create_TDTW_all_example[<img align="right" height="30" src="https://beta.deepnote.org/buttons/launch-in-deepnote.svg">](https://beta.deepnote.com/project/69bbfe4c-3745-46a0-a989-e936ebb7fb85)[<img align="right" height="27" src="https://mybinder.org/badge_logo.svg">](https://mybinder.org/v2/gh/V-Talbot/Cystic-Fibrosis-research-analysis/master)[<img height="38" align="right" src="https://imgur.com/JUKXSK3.png">](https://nbviewer.jupyter.org/github/V-Talbot/Cystic-Fibrosis-research-analysis/blob/master/Create_TDTW_all_example.ipynb)
This program merges and processes output from one of the TIME web application's example analyses and creates a file which will be used later to make two different kinds of box plots. 

### Create_TDTW_all_filtered[<img align="right" height="30" src="https://beta.deepnote.org/buttons/launch-in-deepnote.svg">](https://beta.deepnote.com/project/69bbfe4c-3745-46a0-a989-e936ebb7fb85)[<img align="right" height="27" src="https://mybinder.org/badge_logo.svg">](https://mybinder.org/v2/gh/V-Talbot/Cystic-Fibrosis-research-analysis/master)[<img height="38" align="right" src="https://imgur.com/JUKXSK3.png">](https://nbviewer.jupyter.org/github/V-Talbot/Cystic-Fibrosis-research-analysis/blob/master/Create_TDTW_all_filtered.ipynb)
Similar to Create_TDTW_all_example, this program merges and processes output from the TIME web application for the CF Data. You cannot run it unedited without the CF data, but screenshots are provided, as is a randomly generated altered version of the output file so that you can run the program which uses it as input.

## Plotting Programs for GP Microbiome Output
### Plotsamples[<img align="right" height="30" src="https://beta.deepnote.org/buttons/launch-in-deepnote.svg">](https://beta.deepnote.com/project/69bbfe4c-3745-46a0-a989-e936ebb7fb85)[<img align="right" height="27" src="https://mybinder.org/badge_logo.svg">](https://mybinder.org/v2/gh/V-Talbot/Cystic-Fibrosis-research-analysis/master)[<img height="38" align="right" src="https://imgur.com/JUKXSK3.png">](https://nbviewer.jupyter.org/github/V-Talbot/Cystic-Fibrosis-research-analysis/blob/master/Plotsamples.ipynb)

### Leave_One_Out_Examples[<img align="right" height="30" src="https://beta.deepnote.org/buttons/launch-in-deepnote.svg">](https://beta.deepnote.com/project/69bbfe4c-3745-46a0-a989-e936ebb7fb85)[<img align="right" height="27" src="https://mybinder.org/badge_logo.svg">](https://mybinder.org/v2/gh/V-Talbot/Cystic-Fibrosis-research-analysis/master)[<img height="38" align="right" src="https://imgur.com/JUKXSK3.png">](https://nbviewer.jupyter.org/github/V-Talbot/Cystic-Fibrosis-research-analysis/blob/master/Leave_One_Out_Examples.ipynb)

### Plots_Shaded_Backgrounds[<img align="right" height="30" src="https://beta.deepnote.org/buttons/launch-in-deepnote.svg">](https://beta.deepnote.com/project/69bbfe4c-3745-46a0-a989-e936ebb7fb85)[<img align="right" height="27" src="https://mybinder.org/badge_logo.svg">](https://mybinder.org/v2/gh/V-Talbot/Cystic-Fibrosis-research-analysis/master)[<img height="38" align="right" src="https://imgur.com/JUKXSK3.png">](https://nbviewer.jupyter.org/github/V-Talbot/Cystic-Fibrosis-research-analysis/blob/master/Plots_Shaded_Backgrounds.ipynb)

## Box Plots of TIME Output
### DTW_All_boxplots[<img align="right" height="30" src="https://beta.deepnote.org/buttons/launch-in-deepnote.svg">](https://beta.deepnote.com/project/69bbfe4c-3745-46a0-a989-e936ebb7fb85)[<img align="right" height="27" src="https://mybinder.org/badge_logo.svg">](https://mybinder.org/v2/gh/V-Talbot/Cystic-Fibrosis-research-analysis/master)[<img height="38" align="right" src="https://imgur.com/JUKXSK3.png">](https://nbviewer.jupyter.org/github/V-Talbot/Cystic-Fibrosis-research-analysis/blob/master/DTW_All_boxplots.ipynb)

### DTW_All_boxplots_example[<img align="right" height="30" src="https://beta.deepnote.org/buttons/launch-in-deepnote.svg">](https://beta.deepnote.com/project/69bbfe4c-3745-46a0-a989-e936ebb7fb85)[<img align="right" height="27" src="https://mybinder.org/badge_logo.svg">](https://mybinder.org/v2/gh/V-Talbot/Cystic-Fibrosis-research-analysis/master)[<img height="38" align="right" src="https://imgur.com/JUKXSK3.png">](https://nbviewer.jupyter.org/github/V-Talbot/Cystic-Fibrosis-research-analysis/blob/master/DTW_All_boxplots_example.ipynb)

### DTW_boxplots_by_status[<img align="right" height="30" src="https://beta.deepnote.org/buttons/launch-in-deepnote.svg">](https://beta.deepnote.com/project/69bbfe4c-3745-46a0-a989-e936ebb7fb85)[<img align="right" height="27" src="https://mybinder.org/badge_logo.svg">](https://mybinder.org/v2/gh/V-Talbot/Cystic-Fibrosis-research-analysis/master)[<img height="38" align="right" src="https://imgur.com/JUKXSK3.png">](https://nbviewer.jupyter.org/github/V-Talbot/Cystic-Fibrosis-research-analysis/blob/master/DTW_boxplots_by_status.ipynb)

# The Example Data

I have provided example data so that anyone can run my programs. 

The example data for the TIME output box plots came from running Workflow 5b on example data available from the [TIME Web application](https://web.rniapps.net/time/index.php) and saving the results. See the box plot programs for more information on this files and how I downloaded them from TIME. I encourage users to visit the TIME site and play with thieir various example analyses. Then you can either download the files in the same way that I did (as specified in the box plot programs) or go to the 'Box Plot Data' folder, located in the 'Data' folder of this repository under 'Extras', where I have provided them. In the 'Extras' folder you can also find other files which are created by running my programs and later used as input, as an alternative to creating them yourself.  

# Contact information
If you have questions or comments, you can send an email to Virginia Talbot at vtalbot@lesley.edu or vrtalbot@yahoo.com and I will try to get back to you as soon as possible. 

