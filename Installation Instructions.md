## Installation Instructions
To run the programs in this repository from your computer (as opposed to running them on Binder or Deepnote via the links I provided), first you need Python. A couple of my programs process output from the Python 2.7-based program GP Microbiome, and to run either those particular programs of mine (as opposed to their Python 3.7 counterparts) or GP Microbiome itself you will also need that version of Python. I needed to use Python 2.7 to process the output (a pickle file) from the Python 2.7 program GP Microbiome because, after being pickled on a Windows 10 machine, it had to be re-pickled for the file to be used on other operating systems with Python 2.7 or on any operating system with Python 3.7. See readsample27 for more details on the incompatibilities between pickle files in different operating systems and Python 2 and 3. Creating a new environment for a second version of Python is described below.

For Python itself, I recommend Anaconda Navigator, which is free. Here’s a [link](https://docs.anaconda.com/anaconda/navigator) to information about it. To download Anaconda, go [here.](https://www.anaconda.com/distribution) My programs are specifically written for Jupyter Notebook, which comes with Anaconda Navigator. I like Anaconda Navigator because it makes it easier to work with multiple packages and environments, and because in addition to the command terminal it comes with several different code editors, including Jupyter Notebook and Spyder. Jupyter Notebook breaks the code up into cells you can run one at a time, and easily allows for adding cells with things other than Python code, such as images, links, or comments using Markdown. Fans of R will most likely feel comfortable with Spyder from the start, because it is the most similar to RStudio. You can add also add RStudio itself to the Navigator menu. 

## Using both Python 3.7 and Python 2.7
To use both Python 3.7 and 2.7, you need to create a new environment for 2.7.
This is how I did so with my Windows 10 computer: 
Go to the command line interface – I used the Anaconda Powershell Prompt. 
To get Python 2.7 on my machine, I used this code:

conda create -n py27 python=2.7  #for version 2.7

conda activate py27 #to activate 2.7

conda deactivate #to switch back

The code may be slightly different for you depending on what operating system you have. You can click [here](https://stackoverflow.com/search?q=conda+activate+py27) to see more advice on this, or you can simply run a web search for how to create a new environment for Python 2.7. 

## Using the new environment in Anaconda Navigator
After I created the new environment, in addition to being able to use Python 2.7 from the powershell terminal, it appeared in the dropdown menu of Anaconda Navigator, so I could select that environment and launch Jupyter Notebook (or any Anaconda app) using Python 2.7 from there.   

The red arrow below points to the dropdown menu where the environment can be changed.

<img src='https://imgur.com/shU91ax.png' style:height='300ppx'>

## Downloading the repository
You can download the repository in the usual way, by clicking on the 'Clone or Download' button in the GitHub web platform or directly using a 'git clone' command.

