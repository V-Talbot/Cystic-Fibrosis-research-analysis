## Installation Instructions
To run the programs in this repository from your computer (as opposed to running them on a site such as Deepnote via the links I provided), first you need Python. A couple of my programs process output from the Python 2.7 program GP Microbiome, and to run either those particular programs of mine or GP Microbiome itself you will also need that version of Python. Creating a new environment for a second version of Python is described below.

All of the programs are specifically written for Jupyter Notebook. I recommend Anaconda Navigator, which is free. Here’s a [link](https://docs.anaconda.com/anaconda/navigator) to information about it. To download Anaconda, go [here.](https://www.anaconda.com/distribution)  
The programs are specifically written for Jupyter Notebook, which comes with Anaconda Navigator. I like Anaconda Navigator because it makes it easier to work with multiple packages and environments, and because in addition to the command line program you can use several different code editors, such as Jupyter Notebook and Spyder. Fans of R will most likely feel comfortable with Spyder from the start, because it is the most similar to RStudio. You can add also add RStudio itself to the Navigator menu. Jupyter Notebook breaks the code up into cells you can run one at a time, and easily allows for adding cells with things other than code, such as images, links, or comments using Markdown.

## Using both Python 3.7 and Python 2.7
To use both Python 3.7 and 2.7, you need to create a new environment for 2.7.
This is how I did so with my Windows 10 computer: 
Go to the command line interface – I used the Anaconda Powershell Prompt. 
To get Python 2.7 on my Windows 10 machine, I used this code:

conda create -n py27 python=2.7  #for version 2.7

conda activate py27 #to activate 2.7

conda deactivate #to switch back

The code may be slightly different for you depending on what operating system you have. You can click [here](https://stackoverflow.com/search?q=conda+activate+py27) to see more advice on this, or you can simply run a web search for how to create a new environment for Python 2.7. 

## Using the new environment in Anaconda Navigator
After I created the new environment, in addition to being able to use Python 2.7 from the powershell, it appeared in the dropdown menu of Anaconda Navigator, so I could select that environment and launch Jupyter Notebook (or any Anaconda app) using Python 2.7. I needed to use Python 2.7 to process the output (a Pickle file) from the Python 2.7 program GP Microbiome, due to incompatibilities between the versions of Pickle. 

The red arrow below points to the dropdown menu where the environment can be changed.

<img src='https://imgur.com/shU91ax.png' style:height='300ppx'>

## Downloading the repository
You can download the repository in the usual way, by clicking on the 'Clone or Download' button in the GitHub web platform or directly using a 'git clone' command.

