# `python_fundamentals`
- Materials corresponding to a series of Python seminars given at Fordham University's Graduate School of Business.

### Overview

#### Seminar Content

We have here the materials for a few different types of Python seminars:
- basics
- data science
- time series analysis & forecasting

The _basics_ seminar covers basic computer programming in Python, as well as introductory data analysis techniques using the Python library `pandas`, which has become something of an industry-standard tool for quickly working through and making sense of a new data set.

The _data science_ notebooks cover the working-through of a real extract of the 1994 U.S. Census, which I originally found on the University California Irvine's [Machine Learning Repository](https://archive.ics.uci.edu/ml/index.php) (note that you don't need to download the data - this happens automatically). We cover data wrangling, exploratory data analysis, some light feature engineering, and some basic machine learning.

The _time series_ notebooks cover analysis techniques in the context of time series data - data with an undelrying temporality. This data has to be treated with some special care, and as such there are some special ideas and techniques that it's good to know about. In our seminars on the subject, we use real, daily equities data from _QuantQuote_, which you can learn more about [here](https://quantquote.com/historical-stock-data) (note that you don't have to download this dataset, either).

### Tools

The code you are going to be reading and writing is that of _Python_. This is an open-source (i.e. freely available for use), high-level (i.e. you think more about expressing you ideas and less about computer-system things like memory) computer programming language that has really taken off in the data science world thanks to some key libraries - code that other people have written that you can make use of.

These libraries include:

- `pandas` - data analysis tools; SQL-like / relational data analysis; built-in visualization capabilities
- `numpy` - heavily used by pandas under-the-hood; essentially, Python wrappers for some really well-optimized C and FORTRAN code
- `scikit-learn` - robust library providing a good breadth of machine learning functionality
- `matplotlib` - a powerful, if cumbersome, plottling library
- `jupyter` - a tool for creating interactive notebooks that combine code, visualizations, Markdown [formatting](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet), and [LaTeX] (https://en.wikipedia.org/wiki/LaTeX)

You can read more about Python, [here](https://docs.python.org/3/tutorial/); pandas, [here](https://pandas.pydata.org/docs/user_guide/index.html); numpy, [here](https://numpy.org/devdocs/user/quickstart.html); and Jupyter, [here](https://jupyter.org/index.html).

### GitHub

What is GitHub? This is an online platform for storing, interacting with, and collaborating on, computer programming projects.

Core to its functioning is something called `git`. Git is _version control system_, which is a tool that carefully keeps track of all changes made to any code it's tracking, and which (among other things) allows for teams to work together on editing the same code at the same time. Installing git is not required, as it can be a little bit cumbersome for those who are unfamiliar with working on the command line. However, if you do install git, it will allow for you to quickly retrieve updates to this repository, without having to re-download the whole thing every time. You can find some installation instructions [here](https://www.atlassian.com/git/tutorials/install-git).

Git is a command-line tool, and so many applications have sprung up to provide visual and web interfaces to git. GitHub is one of such tools, and it's really taken off in the open-source community.

### Instructor Bio

Abe Lerman is the founder and CEO of _NewTrails Data Science_, a boutique data science consulting firm. You can learn more about NewTrails [here](https://newtrails.io/about). He has worked as a data scientist and Python developer at firms including The Blackstone Group, Contently, Elliott Management, and Dun & Bradstreet, and has successfully developed machine-learning models in a number of contexts. He earned a Master of Science degree in Quantitative Finance from Fordham University, and a Bachelor of Arts degree in Mathematics from Skidmore College. In his personal life, he enjoys guitar, skiing, and some light cobbling.

### Setup

This will be a **hands-on** session - students will benefit from trying to run the material we discuss it. 

Students should come prepared, having downloaded and installed Python and the necessary libraries a priori (I can offer technical support as needed, but this is not the best use of time). The easiest way to do this is to go [here](https://www.anaconda.com/download/), and click the green "Download" button for Python 3.7. 

Note the above link leads to a download of the Anaconda Python distribution, which provides Python + a whole lot of third-party libraries and other tools. Students do not have to get Python this way - this just provides an all-in-one download. 

For those looking for more of an _a la carte_ option, these notebooks can be run with the following installed:
- Python 3.6+
- `numpy`
- `pandas`
- `sklearn`
- `matplotlib`
- `ipython`
- `jupyter`
- `requests`
- `indoorplants` (a library I wrote)

Next, you need to get these materials. Once you're here, you can do the following:

1. click the green "Clone or download" button at the top right of this repo's home page
2. click "Download ZIP"
3. extract the zip file to somewhere convenient, e.g. `/home/your_user_name/projects/python_fundamentals` (this should be a location _on your machine_, and not an external drive)

Then, if you are on _Windows_:
- open `Anaconda Cmd`
- navigate to the directory you've unpacked (use `cd` to change directories, `dir` to list contents of directory)
- run `jupyter notebook`

If you are on _Mac_:
- open `terminal`
- navigate to the directory you've unpacked (use `cd` to change directories, `ls` to list contents of directory)
- run `jupyter notebook`

### Jupyter Keyboard Shorcuts

- To run a cell:

    shift + enter

- To enter command mode:

    escape

The following commands must be run from command mode and operate at the cell level.

- Copy, cut, paste cell:

    c, x, v

- New cell above, below:

    a, b

- Delete cell:

    dd

- Convert cell to markdown:

    m

- See all shortcuts:

    h
