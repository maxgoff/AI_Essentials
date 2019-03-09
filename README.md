# AI Essentials

GitHub repository can be found here: <a href="https://github.com/maxgoff/AI_Essentials" target="_blank">ML_Example</a>

This repository contains examples of Jupyter notebooks for machine learning, AI basics, and Deep Learning.   The Jupyter notebooks, datasets and configuration files are included.

You need to install Anaconda on either OSX or Linux.  Running Ubutu on the Windows 10 Linux subsystem works just as well. I've done this on Windows 10 running bash (Ubuntu Linux).

## Install / Configure bash on Windows 10

Follow this tutorial and pick Ubuntu as the version of Linux you want to host on Windows, unless you know what you're doing and prefer other distrubutions: <a href="https://www.windowscentral.com/how-install-bash-shell-command-line-windows-10" target="_blank">How to Install Bash on Windows 10</a> 
## Bash on OSX

If you're on a Mac, the standard Terminal utility will do. You might want to download iTerm for a better experience, but it's not required: <a href="http://sourabhbajaj.com/mac-setup/iTerm/README.html" target="_blank">iTerm tutorial</a>

## Install Anaconda

Next, you need to install <a href="https://www.anaconda.com/download/" target="_blank">anaconda</a> on your platform (either OSX or Linux).  

REMEMBER: If you are on Windows 10 hosting Linux, you are effectively running on Linux.  So run the install script from a bash window.

## Configure Environment
Once installed from a bash terminal, change directory to the root of the repository.  You should see a file called README.md and several subdirectories including the config directory.  To create the environment you will need to issue the following command from your terminal:

```
    conda env create  --file config/environment.yml 
```


If all goes well you should now have a properly configured python environment called py3.  Then activate the environment:
    
```
     conda activate py3
```

## Running Jupyter

Then fire up the notebook:


```
     jupyter notebook --ip=127.0.0.1
```
Either a browser will open with Jupyter running, or you will see, from the command line, the URL to use to access Jupyter. Congratulations! Now you can successfully run the notebook!

From the Jupyter notebook page in your browser open the notebooks direcotry and you will see the examples. Click on them to open them.

If you have never used Jupyter before, see this tutorial:  <a href="https://nbviewer.jupyter.org/github/jupyter/notebook/blob/master/docs/source/examples/Notebook/Notebook%20Basics.ipynb">Notebook Tutorial.</a>
