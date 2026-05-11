# Introduction to Pandas and Numpy

---------------------------

![Pandas](./images/pandas_photo.jpg)
<span>Photo by <a href="https://unsplash.com/@pbernardon?utm_source=unsplash&amp;utm_medium=referral&amp;utm_content=creditCopyText">Pascal Bernardon</a> on <a href="https://unsplash.com/s/photos/panda?utm_source=unsplash&amp;utm_medium=referral&amp;utm_content=creditCopyText">Unsplash</a></span>

In this Repository you will find Jupyter Notebooks that you should work through as **Pair-Programmers**.

## At the end of this Repo you should:

- Understand why Pandas and Numpy are valuable tools for Data Scientists

- Be familiar to handle data in Pandas DataFrames and Numpy-Arrays

- Know how to combine datasets

- Be able to do some EDA on a new dataset

- Know how to plot some basic plots for better data understanding


## This Repo covers:

### 1. Pandas

- [Introduction to Pandas](./1_Pandas/01_Introduction_to_Pandas.ipynb)

- [Practice Pandas: Functionalities](./1_Pandas/02_Pandas_Practice_Functionalities.ipynb)

- [Introduction to Visualization](./1_Pandas/03_Introduction_to_Visualization.ipynb)

- [More Pandas Practice: Functionalities and Visualizations](./1_Pandas/04_More_Pandas_Practice.ipynb)

- [Even More Pandas Practice: Exploratory Data Analysis (EDA)](./1_Pandas/05_Even_More_Pandas_Practice.ipynb)

### 2. Numpy

- [Introduction to Numpy](./2_Numpy/01_Introduction_to_Numpy.ipynb)

- [Practice Numpy: Functionalities](./2_Numpy/02_Numpy_Practice.ipynb)

### 3. More Pandas

- [The Last Pandas Practice](./3_More_Pandas/01_The_Last_Pandas_Practice.ipynb)

- [Combining DataFrames](./3_More_Pandas/02_Combining_Dataframes.ipynb)

- [Dealing with date and time data (Datetime)](./3_More_Pandas/03_Datetime.ipynb)

Please make sure you create a template of this repository to your **personal** github account, clone it to your **local machine** and  then set up a the new virtual environment by following the instructions below.

## Seting Up Your Virtual Environment

The added [requirements file](requirements.txt) contains all libraries and dependencies we need to execute Pandas and Numpy. 

### For **`MacOS`** :

```BASH
pyenv local 3.11.3
python -m venv .venv
source .venv/bin/activate
pip install --upgrade pip
pip install -r requirements.txt
```
-------------------------------------------

### For **`WindowsOS`** : 

Open `PowerShell` CLI (as an administrator) :

```Bash
pyenv local 3.11.3
python -m venv .venv
.venv\Scripts\Activate.ps1
python -m pip install --upgrade pip
pip install -r requirements.txt
```

Open `Git-Bash` CLI (as an administrator) :

```Bash
pyenv local 3.11.3
python -m venv .venv
source .venv/Scripts/activate
python -m pip install --upgrade pip
pip install -r requirements.txt
```
### *Note :*

If you encounter an error, try using the following command:

```Bash
python.exe -m pip install --upgrade pip
```

[![Shipping files](https://github.com/neuefische/ds-pandas-numpy/actions/workflows/workflow-02.yml/badge.svg?branch=main&event=workflow_dispatch)](https://github.com/neuefische/ds-pandas-numpy/actions/workflows/workflow-02.yml)
