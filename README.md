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

[<img height="30" src="https://beta.deepnote.org/buttons/launch-in-deepnote.svg">](https://beta.deepnote.com/project/69bbfe4c-3745-46a0-a989-e936ebb7fb85)
<br>

Alternatively, you can go directly to an individual notebook on nbviewer or Deepnote by clicking the corresponding button under its description.   

# Index of Jupyter (IPython) Notebooks
## Programs Which Create Files for Use as Input in Other Programs

### Python 2.7
### readsample27[<img height="38" align="right" src="https://imgur.com/JUKXSK3.png">](https://nbviewer.jupyter.org/github/V-Talbot/Cystic-Fibrosis-research-analysis/blob/master/readsample27.ipynb)
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

# The Example Data

I have provided example data so that anyone can run my programs. 

The example data for the TIME output box plots came from running Workflow 5b on example data available from the [TIME Web application](https://web.rniapps.net/time/index.php) and saving the results. See the box plot programs for more information on this files and how I downloaded them from TIME. I encourage users to visit the TIME site and play with thieir various example analyses. Then you can either download the files in the same way that I did (as specified in the box plot programs) or go to the 'Box Plot Data' folder, located in the 'Data' folder of this repository under 'Extras', where I have provided them. Along with those, the 'Extras' folder contains all other files which are created by running one of my programs and later used as input in another, as an alternative to creating them yourself.  

# Contact information
If you have questions or comments, or have any difficulty running the programs, please send an email to Virginia Talbot at vtalbot@lesley.edu or vrtalbot@yahoo.com and I will get back to you as soon as possible. 

