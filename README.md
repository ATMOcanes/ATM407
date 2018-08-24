# ATM407, University of Miami

## How to use this repository of Jupyter (Python) notebooks, with The IDV as the visualization system

1. Install [The IDV](https://www.unidata.ucar.edu/downloads/idv/nightly/index.jsp), and [Jupyter notebooks via the Anaconda package](https://unidata.github.io/unidata-python-workshop/installation.html). 

2. Create a GitHub account. 

3. **Fork this repo** by clicking the Fork button you see at upper right while logged in to your GitHub account.

4. **Clone** your forked repo to your local machine. 
  - To do this most intuitively, install the "223" version of the GitHub desktop client, which you can download from: 
    - **Mac:** https://central.github.com/mac/latest
    - **Windows:** https://github-windows.s3.amazonaws.com/GitHubSetup.exe
    
  - Then, in the GitHub desktop client, select the **+** symbol at upper left, choosing **Clone**.
    - You will have to select or create the directory name you put it in, on your own computer. *Naming is worth a lot of thought!* How will all this fit into your larger intellectual life (as mapped into your computer)? I think Jupyter notebooks are the most important layer of the technology stack we are working with here. As a big part of my computing future, it is nice to have them all in one folder tree, without too many other things in there. So I would create and use use the folder name **(home)/Jupyter/ATM407** and clone this repo into there. 

5. Install all the packages that make up the ATM407 **environment** on your machine, using conda (part of the Anaconda package you installed). To do this from a command line in Anaconda Propmpt or Terminal, change directories into your clone of this repo, where you can find the file ATM407_environment.yml. Create the environment as explained [here](https://github.com/MPOcanes/MPO624-2020/blob/master/CONDA_ENVIRONMENTS.md), but substituting ATM407 for MPO624 as needed. It will take a few minutes to download all the Python packages we will use. You could also do this step from the Anaconda Navigator GUI. 

6. In a directory containing your clone of this repo, activate the ATM407 environment as was explained [here](https://github.com/MPOcanes/MPO624-2020/blob/master/CONDA_ENVIRONMENTS.md). Then, *from that ATM407 environment* launch `jupyter notebook`. A browser will pop up and you can navigate within it to open the .ipynb files in this repo. 

