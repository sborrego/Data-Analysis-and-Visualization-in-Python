# Data Analysis and Visualization in Python
University of South Florida workshop   
Tuesday, February 27th, 2024  
9:00 - 10:30 am EST  

This workshop will introduce the basics of the powerful Python data visualization library Matplotlib. We will create simple visualizations for different types of data and explore how to customize and share these visualizations. This is a follow-up workshop to the *Python Programming: An Introduction* workshop, you can find the material [HERE](https://github.com/sborrego/Introduction-to-Python/blob/main/Introduction%20to%20Python.ipynb).

***

## Data Download

We will be using real data taken from the Gapminder dataset. To download the data, click 
<a href="https://github.com/sborrego/Data-Visualization-in-Python/blob/main/gapminder-data.zip" download> HERE </a> to go to the file webpage. Click on the `download` button, unzip the file, and place the unzipped folder named **data** on your desktop.

***

## Software Installation

We will program in Python using JupyterLab, a programming environment that runs in a web browser. For this to work you will need a reasonably up-to-date web browser -- Chrome, Safari and Firefox are all supported.

You will also need to find the command line (aka terminal, shell) on your system. If you are not familiar with the command line on your system, you can find help [HERE](https://swcarpentry.github.io/shell-novice/index.html#open-a-new-shell).

To start the software, you will need to use your terminal to open a notebook. In your terminal type `jupyter notebook` - your terminal will fill with code and a new browser window will open with the Jupyter software. Click on `New` and `Python3`, and you are all ready to code in a new notebook! For more information about getting started, [HERE](https://datacarpentry.org/python-socialsci/index.html#setup-instructions-for-python) is a helpful document.

### Recommended Installation - Anaconda

Downloading Python and JupyterLab independently may often times run into issues that are tricky and time consuming to resolve. A simpler method of obtaining Python is to use the all-in-one installer Anaconda. It easy to install, provides a user-friendly interface, and allows easy access to Python packages.

Download Anaconda - [https://www.anaconda.com/products/individual](https://www.anaconda.com/products/individual)  
Addition Help with Anaconda - [HERE](https://carpentries.github.io/workshop-template/install_instructions/#python)

***

## Advanced User Software Installation

For **advanced users** that are familiar with the command line and prefer to install Python and JupyterLab individually, you can find the links and installation instructions on the software websites linked below.

### Python

There are two current versions of Python -- we will be using version 3.5 or later. 

Download Python 3.x - [https://www.python.org/downloads/](https://www.python.org/downloads/)

### JupyterLab

Install JupyterLab by following the first set of instructions - [https://jupyter.org/jnstall](https://jupyter.org/install)

***

##  Additional Software Requirements (for those NOT using Anaconda)

We will be using the Python plotting package, Matplotlib. It must be installed on your computer using the command line using the command `pip`. 

### Check that `pip` is installed correctly

* Getting started with `pip` [instructions](https://pip.pypa.io/en/stable/getting-started/)
    - Note: You may need to use `python3` instead of `python` like the instructions indicate
    - Note: You may also need to use `pip3` instead of `pip`
* If `pip` is not installed or working, try following these instructions [HERE](https://pip.pypa.io/en/stable/installation/)

### Install Matplotlib

* On command line, type:
    - `python -m pip install -U pip`
    - `python -m pip install -U matplotlib`
* Installation instuctions for Matplotlib - [HERE](https://matplotlib.org/stable/users/installing/index.html)

### Install Numpy

* On command line, type:
    - `pip install numpy`
* Installation instructions for Numpy - [HERE](https://numpy.org/install/)

### Install Pandas

* On command line, type:
   - `pip install pandas`
* Installation instructions for Pandas [HERE](https://pandas.pydata.org/docs/getting_started/install.html)

*** 

## Additional Learning Resources

* [Beginner's Guide to Python](https://wiki.python.org/moin/BeginnersGuide) - Official Python with extensive resources
* A helpful document with Python basics to reference: [DataCamp Python Basics Cheat Sheet](https://www.datacamp.com/cheat-sheet/getting-started-with-python-cheat-sheet) 
* A tutorial demonstrating how to use Matplotlib with real data: [DataCamp Introduction to Plotting with Matplotlib in Python](https://www.datacamp.com/tutorial/matplotlib-tutorial-python)  
* [Matplotlib documentation](https://matplotlib.org/stable/index.html)
* Colors in Matplotlib - [Named Colors](https://matplotlib.org/stable/gallery/color/named_colors.html#)
* Style guide for python code - [PEP 8](https://www.python.org/dev/peps/pep-0008/)
* The Zen of Python - [PEP 20](https://www.python.org/dev/peps/pep-0020/)
* [The Carpentries](https://carpentries.org/)
    + [Programming in Python](https://swcarpentry.github.io/python-novice-inflammation/)
    + [Plotting and Programming in Python](http://swcarpentry.github.io/python-novice-gapminder/)
