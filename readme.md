
# Data Science Toolkit
This workshop aims to highlight important and capable tools to start your data science journey. There isn’t one way to solve every problem, but this setup will empower you to solve a vast majority of problems..

## Essential Downloads

To get started, you'll need to download and install the following tools:

- **[python with Conda](https://docs.anaconda.com/miniconda/):** A package and environment manager.
- **[Visual Studio Code](https://code.visualstudio.com/download):** A versatile and powerful code editor. _note, you can download beta_


## Dataset

### Finding Datasets

There are many sources for datasets, but my favorite is [Kaggle](https://www.kaggle.com/datasets).

Today we will be exploring "Most Streamed Spotify Songs 2024" 
* the dataset: `Spotify Top Songs 2024.zip`


## Running the code
### download this folder
* Select the green code button
* download the zip file
* extract the zip file
* move to **Recommended location:** `Documents/github/<profile name>`
* open the folder in VS Code
  * File -> Open Folder -> select the folder `<profile name>`


## Getting familiar with the notebooks in VS Code
* Check python installation
  * In the terminal in VS Code:
  * `python --version`
* Create new conda environment
  * In the below terminal:
  * `conda create -n spotify`
  * `conda activate spotify`
  * check environment is created: `conda env list`
    * there should be a `*` next to the `spotify` environment
  * [Magic commands](https://ipython.readthedocs.io/en/stable/interactive/magics.html)

## Optional VS Code Plugins

Enhance your coding experience with these optional but highly recommended plugins:
note: installation instructions in the next section

There is a shortcut on the left side for extensions, or you can use the shortcut `Ctrl+Shift+X` or for mac `Cmd+Shift+X`


- **[Data Wrangler](https://marketplace.visualstudio.com/items?itemName=ms-toolsai.datawrangler):** Simplify data manipulation and visualization.
- **[Excel Viewer](https://marketplace.visualstudio.com/items?itemName=GrapeCity.gc-excelviewer):** Easily view Excel files within VS Code.
- **[Indent Rainbow](https://marketplace.visualstudio.com/items?itemName=oderwat.indent-rainbow):** Colorize indents for better readability.
- **[IntelliCode](https://marketplace.visualstudio.com/items?itemName=VisualStudioExptTeam.vscodeintellicode):** AI-assisted code completions and recommendations.
- **[Python Indent](https://marketplace.visualstudio.com/items?itemName=KevinRose.vsc-python-indent):** Automatically adjusts Python indentation levels.


## Install python libraries
* In the terminal in VS Code:
* `conda install pandas`
* `conda install plotly`
We will be needing more libraries, but we will install them as we go along.

### ⚠️ WARNING:
Downloading python packages can be risky! Always check the source:
* check the PyPi page
* Check their github page


## Python built-in libraries & functions
here is a list of the [built-in libraries](https://docs.python.org/3/library/index.html) in latest python version.
Some of the most common libraries are:
* os
* math
* random
* datetime
* json
* re
* time

### Functions
![alt text](image.png)

[Source](https://docs.python.org/3/library/functions.html)


# Next Steps
Let's start with the first notebook: `intro_material.ipynb`