# Cystic-Fibrosis-research-analysis
These programs visualize world-class repeated measures microbiome data from a cohort of well-characterized children with Cystic Fibrosis. Although these programs were applied to the real-life settings of Cystic Fibrosis, the theoretical framework it is based upon is applicable to a wide range of other studies featuring longitudinal microbiome data. 

# About This Repository
This repository is intended to be a plain-English explanation of how to implement longitudinal microbiome analyses, using readily available software packages. Microbiome data is notoriously challenging to work with, and traditional statistical methods often fall short. For example, the frequent use of relative abundance data can cause different bacteria to appear to be correlated simply because the relative abundances must sum to 1. Therefore, I used several custom software programs specifically designed to be used with this data type. 

# The Programs
The programs in this repository are written in Python 2.7 and Python 3.7 with Jupyter Notebook, and they visualize the output from two of the software programs I used: the [TIME Web application](https://web.rniapps.net/time/index.php) and [GP Microbiome](https://github.com/tare/GPMicrobiome), a Python-based program available here on GitHub. Programs are in Python 3.7 unless otherwise specified, and anyone can run them with the example data provided here unless otherwise specified. 

The programs are Jupyter (IPython) notebooks (.ipynb files). You can view them here on GitHub, but often Jupyter notebooks don't display as well on this site. Fortunately, Jupyter has a website called [nbviewer](https://nbviewer.jupyter.org/) where you can view any notebook by entering its web address. Click the button below to go directly to this repository on nbviewer.
<br>

[<img height="38" src="https://imgur.com/JUKXSK3.png">](https://nbviewer.jupyter.org/github/V-Talbot/Cystic-Fibrosis-research-analysis/tree/master/)
<br>
If you want to *run* the notebooks, not just view them, you have several options: You can clone or download the project, you can run the notebooks online using websites called Binder and Deepnote. See 'Installation Instructions' for more on how to download the necessary software and run the programs on your own computer. 
<br>

Binder will display them in your browser as if you were running Jupyter Notebook on your own computer. Binder can run both the Python 2 and Python 3 notebooks. 
<br>

[<img height="27" src="https://mybinder.org/badge_logo.svg">](https://mybinder.org/v2/gh/V-Talbot/Cystic-Fibrosis-research-analysis/master)

Deepnote is a newer platform, and since it does not have support for Python 2 yet you can only run the Python 3 programs there. Its creators are frequently updating it and are interested in feedback and suggestions. The display is slightly different there, but Deepnote has interesting features and is well worth exploring. To access the entire repository on Deepnote now, click the button below.
<br>

[<img height="30" src="https://beta.deepnote.org/buttons/launch-in-deepnote.png">](https://beta.deepnote.com/project/69bbfe4c-3745-46a0-a989-e936ebb7fb85)
<br>

Alternatively, you can go directly to an individual notebook on nbviewer, Binder or Deepnote by clicking the corresponding button to the right of its name.   

# Index of Jupyter (IPython) Notebooks
## Programs Which Create Files for Use as Input in Other Programs

### Python 2.7
### readsample27[<img align="right" height="27" src="https://img.shields.io/badge/run%20with%20-binder-579ACA.svg?logo=data:image/png;base64,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">](https://mybinder.org/v2/gh/V-Talbot/Cystic-Fibrosis-research-analysis/master?filepath=readsample27.ipynb)[<img height="38" align="right" src="https://imgur.com/JUKXSK3.png">](https://nbviewer.jupyter.org/github/V-Talbot/Cystic-Fibrosis-research-analysis/blob/master/readsample27.ipynb)
Written for Python 2.7, this program reads the output from GP Microbiome and creates, then saves, csv files for further analysis and plotting with Python 3.7. It also shows how I converted the output files, which initially needed to be read in Python 2.7 on a Windows 10 computer like my own, to a format that could be read by Unix-based operating systems and Python 3. Deepnote does not have support for Python 2 yet, but you can run it on Binder. 

### readsample27_with_151_edit[<img align="right" height="30" src="https://beta.deepnote.org/buttons/launch-in-deepnote.svg">](https://beta.deepnote.com/project/69bbfe4c-3745-46a0-a989-e936ebb7fb85)[<img height="38" align="right" src="https://imgur.com/JUKXSK3.png">](https://nbviewer.jupyter.org/github/V-Talbot/Cystic-Fibrosis-research-analysis/blob/master/readsample27_with_151_edit.ipynb)
Unlike most of my programs, this edit to readsample27 cannot be run with example data. I include it because it demonstrates how to avoid letting a minor discrepancy in a single file cause a significant error later. 

### Python 3.7
### readsample37[<img align="right" height="30" src="https://beta.deepnote.org/buttons/launch-in-deepnote.svg">](https://beta.deepnote.com/project/69bbfe4c-3745-46a0-a989-e936ebb7fb85)[<img height="38" align="right" src="https://imgur.com/JUKXSK3.png">](https://nbviewer.jupyter.org/github/V-Talbot/Cystic-Fibrosis-research-analysis/blob/master/readsample37.ipynb)
This is a version of readsample27 which has been edited to run in Python 3.7, using the reformatted output files.

### readsample37_with_151_edit[<img align="right" height="30" src="https://beta.deepnote.org/buttons/launch-in-deepnote.svg">](https://beta.deepnote.com/project/69bbfe4c-3745-46a0-a989-e936ebb7fb85)[<img height="38" align="right" src="https://imgur.com/JUKXSK3.png">](https://nbviewer.jupyter.org/github/V-Talbot/Cystic-Fibrosis-research-analysis/blob/master/readsample37_with_151_edit.ipynb)
This is a version of readsample27_with_151_edit which has been edited to run in Python 3.7, using the reformatted output files.

### Create_relative_abundance_files[<img align="right" height="30" src="https://beta.deepnote.org/buttons/launch-in-deepnote.svg">](https://beta.deepnote.com/project/69bbfe4c-3745-46a0-a989-e936ebb7fb85)[<img height="38" align="right" src="https://imgur.com/JUKXSK3.png">](https://nbviewer.jupyter.org/github/V-Talbot/Cystic-Fibrosis-research-analysis/blob/master/Create_relative_abundance_files.ipynb)
This program is written to take a file with observed relative abundances of bacteria for several of our CF study participants and split it into separate files, one for each participant. They will be used as input in plots of GP Microbiome output.

### Create_TDTW_all_example[<img align="right" height="30" src="https://beta.deepnote.org/buttons/launch-in-deepnote.svg">](https://beta.deepnote.com/project/69bbfe4c-3745-46a0-a989-e936ebb7fb85)[<img height="38" align="right" src="https://imgur.com/JUKXSK3.png">](https://nbviewer.jupyter.org/github/V-Talbot/Cystic-Fibrosis-research-analysis/blob/master/Create_TDTW_all_example.ipynb)
This program merges and processes output from one of the TIME web application's example analyses and creates a file which will be used later to make two different kinds of box plots. Users can run the analysis themselves, download the files and then run this program, or they can use copies of the files provided for their convenience in this repository. 

### Create_TDTW_all_filtered[<img align="right" height="30" src="https://beta.deepnote.org/buttons/launch-in-deepnote.svg">](https://beta.deepnote.com/project/69bbfe4c-3745-46a0-a989-e936ebb7fb85)[<img height="38" align="right" src="https://imgur.com/JUKXSK3.png">](https://nbviewer.jupyter.org/github/V-Talbot/Cystic-Fibrosis-research-analysis/blob/master/Create_TDTW_all_filtered.ipynb)
Similar to Create_TDTW_all_example, this program merges and processes output from the TIME web application for the CF Data. You cannot run it unedited without the CF data, but screenshots are provided, as is a randomly generated altered version of the output file so that you can run the program which uses it as input.

## Plotting Programs for GP Microbiome Output
### Plotsamples[<img align="right" height="30" src="https://beta.deepnote.org/buttons/launch-in-deepnote.svg">](https://beta.deepnote.com/project/69bbfe4c-3745-46a0-a989-e936ebb7fb85)[<img height="38" align="right" src="https://imgur.com/JUKXSK3.png">](https://nbviewer.jupyter.org/github/V-Talbot/Cystic-Fibrosis-research-analysis/blob/master/Plotsamples.ipynb)
This program processes and plots output from GP Microbiome using functions and loops. Plots show GP Microbiome output with observed relative abundances, both with and without prediction time points. Coloured-coded markers show a particpant's clinical status.

### Leave_One_Out_Examples[<img align="right" height="30" src="https://beta.deepnote.org/buttons/launch-in-deepnote.svg">](https://beta.deepnote.com/project/69bbfe4c-3745-46a0-a989-e936ebb7fb85)[<img height="38" align="right" src="https://imgur.com/JUKXSK3.png">](https://nbviewer.jupyter.org/github/V-Talbot/Cystic-Fibrosis-research-analysis/blob/master/Leave_One_Out_Examples.ipynb)
Similar to Plotsamples, this shows the results of running GP Microbiome while omitting data for one or more time points, then making predictions for those time points to test the accuracy of predictions. Plots take the same form of showing output with and without predictions. Markers again show the participant's clinical status at each time point and indicate the time points which were withheld and predicted for. 

### Plots_Shaded_Backgrounds[<img align="right" height="30" src="https://beta.deepnote.org/buttons/launch-in-deepnote.svg">](https://beta.deepnote.com/project/69bbfe4c-3745-46a0-a989-e936ebb7fb85)[<img height="38" align="right" src="https://imgur.com/JUKXSK3.png">](https://nbviewer.jupyter.org/github/V-Talbot/Cystic-Fibrosis-research-analysis/blob/master/Plots_Shaded_Backgrounds.ipynb)
This program demonstrates how to shade the background of a plot of GP Microbiome output similar to those in Plotsamples according to a binary variable, converting dates to time deltas to indicate with shading whether a participant was on or off antibotics. 

## Box Plots of TIME Output
### DTW_All_boxplots[<img align="right" height="30" src="https://beta.deepnote.org/buttons/launch-in-deepnote.svg">](https://beta.deepnote.com/project/69bbfe4c-3745-46a0-a989-e936ebb7fb85)[<img height="38" align="right" src="https://imgur.com/JUKXSK3.png">](https://nbviewer.jupyter.org/github/V-Talbot/Cystic-Fibrosis-research-analysis/blob/master/DTW_All_boxplots.ipynb)
Boxplots compare the Dynamic Time Warping (DTW) distance from each of 3 selected bacteria to a group of others. This uses as input a randomly altered version of the output from Create_TDTW_all_filtered, which is included in the repository so that anyone can run it.

### DTW_All_boxplots_example[<img align="right" height="30" src="https://beta.deepnote.org/buttons/launch-in-deepnote.svg">](https://beta.deepnote.com/project/69bbfe4c-3745-46a0-a989-e936ebb7fb85)[<img height="38" align="right" src="https://imgur.com/JUKXSK3.png">](https://nbviewer.jupyter.org/github/V-Talbot/Cystic-Fibrosis-research-analysis/blob/master/DTW_All_boxplots_example.ipynb)
Similar to DTW_all_boxplots, this uses as input the results of running one of TIME's example analyses, which looks at antibiotic use and bacteria. Users can run the TIME algorithm and download the results themselves, then process them in Create_TDTW_all_example to create the input file for this program, or they can use copies of them provided here for their convenience. 

### DTW_boxplots_by_status[<img align="right" height="30" src="https://beta.deepnote.org/buttons/launch-in-deepnote.svg">](https://beta.deepnote.com/project/69bbfe4c-3745-46a0-a989-e936ebb7fb85)[<img height="38" align="right" src="https://imgur.com/JUKXSK3.png">](https://nbviewer.jupyter.org/github/V-Talbot/Cystic-Fibrosis-research-analysis/blob/master/DTW_boxplots_by_status.ipynb)
These boxplots show the DTW distance for bacteria from TIME's antibiotic example analysis, grouped by factor variables related to antibiotic use. 

# The Example Data

I have provided example data so that anyone can run my programs. 

The example data for the TIME output box plots came from running Workflow 5b on example data available from the [TIME Web application](https://web.rniapps.net/time/index.php) and saving the results. See the box plot programs for more information on this files and how I downloaded them from TIME. I encourage users to visit the TIME site and play with thieir various example analyses. Then you can either download the files in the same way that I did (as specified in the box plot programs) or go to the 'Box Plot Data' folder, located in the 'Data' folder of this repository under 'Extras', where I have provided them. Along with those, the 'Extras' folder contains all other files which are created by running one of my programs and later used as input in another, as an alternative to creating them yourself.  

# Contact information
If you have questions or comments, or have any difficulty running the programs, please send an email to Virginia Talbot at vtalbot@lesley.edu or vrtalbot@yahoo.com and I will get back to you as soon as possible. 

