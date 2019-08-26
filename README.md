# ATM407, University of Miami

## How to use this repository of Jupyter (Python) notebooks, with The IDV as the visualization system

1. Install [The IDV](https://www.unidata.ucar.edu/downloads/idv/nightly/index.jsp), and [Jupyter notebooks via the Anaconda package](https://unidata.github.io/python-workshop/installation.html). 

2. Create a GitHub account, and [install the small program git](https://git-scm.com/download) if you are using a Mac that doesn't have it.

3. **Fork this repo** by clicking the Fork button you see at upper right while logged in to your GitHub account.

4. **Clone** your forked repo to your local machine. 
  - To do this most intuitively, install the [desktop client](https://desktop.github.com)
  - I have preferred the older "223" or 224 version of the GitHub desktop client, available (spring 2018) from: 
    - **Mac:** https://central.github.com/mac/latest
    - **Windows:** https://github-windows.s3.amazonaws.com/GitHubSetup.exe
    
  - Then, in the GitHub desktop client, select the **+** symbol at upper left, choosing **Clone**.
    - You will have to _select or create the directory name_ you put it in, on your own computer. ***Naming is worth a lot of thought!*** How will all this fit into your larger intellectual life (as mapped into your computer)? I think Jupyter notebooks are the most important layer of the technology stack we are working with here. So I would create and use use the folder name **(home)/Jupyter/ATM407** and clone this repo into there. Others think of GitHub as the central technology, and use **(home)/Jupyter/ATM407**. Some want it on their Desktop, and choose **(home)/Desktop/Jupyter/ATM407**

5. Install all the packages that make up the ATM407 **environment** on your machine, using conda (part of the Anaconda package you installed). To do this from a command line in Anaconda Propmpt or Terminal, change directories into your clone of this repo, where you can find the file ATM407_environment.yml. Create the environment as explained [here](https://github.com/MPOcanes/MPO624-2020/blob/master/CONDA_ENVIRONMENTS.md), but substituting ATM407 for MPO624 as needed. It will take a few minutes to download all the Python packages we will use. You could also do this step from the Anaconda Navigator GUI. 

6. In a directory containing your clone of this repo, activate the ATM407 environment as explained [here](https://github.com/MPOcanes/MPO624-2020/blob/master/CONDA_ENVIRONMENTS.md). **SIMON SAYS! replace MPO624 with ATM407!** Then, *from that ATM407 environment* (type `bash`, then `source activate ATM407`), launch `jupyter notebook`, or perhaps even better `jupyterlab`. A browser will pop up and you can navigate within it to open the .ipynb files in this repo. 

