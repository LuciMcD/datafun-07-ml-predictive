# datafun-07-ml-predictive
#### Name: Luci McDaniel
#### Date: 10/05/2023
#### Github Link: https://github.com/LuciMcD 
#### Repo link: https://github.com/LuciMcD/datafun-07-ml-predictive.git 


This repo is for Module Project 7, dealing with time series, simple linear regression, and predictions. 

## First we will create a virtual environment then activate that environment. 

## Step 1: Open a new terminal. Click on Terminal then New Terminal. 

## Step 2. In the terminal type the following: 
    py -m venv .venv

    Note: There should be a pop-up in the bottom left, noticing that you are trying to create a new environment. Select Yes in the pop-up. 
    Also if py isn't working try python or python3. 

## Step 3: Activate your new environment by typing in the terminal: 
    .venv\Scripts\activate

## Now install some updates to packages we'll be using in this repo. 

### With the virtual environment still active type the below in the terminal:

    py -m pip install --upgrade pip ipykernel jupyterlab
    py -m pip install --upgrade black ruff

    py -m pip install --upgrade pandas matplotlib seaborn
    py -m pip install --upgrade voila


## Create a new notebook

In the active virtual environment, create a Python kernel to run the notebook. 
    py -m ipykernel install --user --name .venv --display-name "Python (.venv)"

In VS Code, select File, New File, and the Jupyter Notebook. Save the new notebook to the project file with a name that fits the project. Be sure to select the correct kernel in your notebook. In the top right corner of the VS Code screen. 