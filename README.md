# Machine Learning Example (Yet another Hello World)

This repository contains a machine learning example in python along with environment configuration data.` The Jupyter notebook, dataset (<a href="https://archive.ics.uci.edu/ml/datasets/Iris/" target="_blank">the Iris dataset from UCI</a>), and configuration files are included.

Inspired by code written by <a href="https://github.com/srmward/ml-python-iris-tutorial" target="_blank">Jason Brownlee</a>, this simple tutorial includes configuration settings and techniques to ensure that you can rapidly reproduce the expected results.  Consider this a YAHW -- yet another "hello world" version of a python machine learning tutorial, but with training wheels.

You need to install <a href="https://www.anaconda.com/download/" target="_blank">anaconda</a> on either OSX or Linux.  Running Ubutu on the Windows 10 Linuxsubsystem works just as well. I've done this on Windows 10 running bash (Ubuntu Linux)..

From a bash terminal create the environment you will need:

```
    conda create --name py3 --file spec-file.txt 
```


If all goes well you should now have a properly configured python environment called py3.  Then activate the environment:
    
```
     source activate py3
```


Then fire up the notebook:


```
     jupyter notebook --ip=127.0.0.1
```

Either a browser will open with Jupyter running, or you will see, from the command line, the URL to use to access Jupyter.  
