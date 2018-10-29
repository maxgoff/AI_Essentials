# Machine Learning Example (Yet another Hello World)

GitHub repository can be found here: <a href="https://github.com/maxgoff/ML_Example" target="_blank">ML_Example</a>

This repository contains a machine learning example in python along with environment configuration data.` The Jupyter notebook, dataset (<a href="https://archive.ics.uci.edu/ml/datasets/Iris/" target="_blank">the Iris dataset from UCI</a>), and configuration files are included.

Inspired by code written by <a href="https://github.com/srmward/ml-python-iris-tutorial" target="_blank">Jason Brownlee</a>, this simple tutorial includes configuration settings and techniques to ensure that you can rapidly reproduce the expected results.  Consider this a YAHW -- yet another "hello world" version of a python machine learning tutorial, but with training wheels.

You need to install Anacondaon either OSX or Linux.  Running Ubutu on the Windows 10 Linux subsystem works just as well. I've done this on Windows 10 running bash (Ubuntu Linux).

## Install / Configure bash on Windows 10

Follow this tutorial and pick Ubuntu as the version of Linux you want to host on Windows, unless you know what you're doing and prefer other distrubutions: <a href="https://www.windowscentral.com/how-install-bash-shell-command-line-windows-10" target="_blank">How to Install Bash on Windows 10</a> 
## Bash on OSX

If you're on a Mac, the standard Terminal utility will do. You might want to download iTerm for a better experience, but it's not required: <a href="http://sourabhbajaj.com/mac-setup/iTerm/README.html" target="_blank">iTerm tutorial</a>

## Install Anaconda

Next, you need to install <a href="https://www.anaconda.com/download/" target="_blank">anaconda</a> on your platform (either OSX or Linux).  

REMEMBER: If you are on Windows 10 hosting Linux, you are effectively running on Linux.  So run the install script from a bash window.

## Configure Environment
Once installed from a bash terminal create the environment you will need:

```
    conda create --name py3 --file spec-file.txt 
```


If all goes well you should now have a properly configured python environment called py3.  Then activate the environment:
    
```
     source activate py3
```

## Running Jupyter

Then fire up the notebook:


```
     jupyter notebook --ip=127.0.0.1
```

Either a browser will open with Jupyter running, or you will see, from the command line, the URL to use to access Jupyter.  Congratulations!  Now you can successfully run the notebook!
