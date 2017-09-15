# An Introduction to Python 3

Class taught to middle and high school students for the Miami Valley Computer Science Circle

## Install Python
Install Python 3.4+ from Python.org[https://www.python.org/downloads/]. After installing, verify that you have the correct version
by opening a terminal or command prompt and running

```
$ python --version
Python 3.6.2
```

## Install Dependencies
Install dependencies with ``pip```.


```
pip install -r requirements.txt
```

## Virtual Environment Kernel
If you are using a virtualenv (highly recommended), you'll need to create a kernel specification to launch notebooks with it inside the Jupyter Notebook.


  mkdir -p ~/kernelspecs/pytalk
  jupyter kernelspec install ~/kernelspecs/pytalk --user


Afterwards, you'll need to relaunch any running jupyter notebook servers. Your kernel containing all the packings installed within your virtualenv are now available.

## Run the notebook
Run the notebook with all access on a given port using

```
jupyter notebook

```

This will run the notebook.
