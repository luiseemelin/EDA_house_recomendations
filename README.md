

# Matching Buissness offers to Client Preferences through Exploratary Data Analysis
## From real estate data to a House for Larry Sanders. 

This projects applies an EDA to match client preferences with real estate offers and enables actionable insights to offer data-driven decision making. 

## Requirements

- pyenv
- python==3.11.3

## Motivation 
An exploratory data analysis is used to understand a data set and align the offers of a fictional real agency to the wishes of a fictional client, Larry Sanders.  
This project demonstrates how with client-specific criteria, the analysis demonstrates how structured data exploration and visualization can uncover meaningful insights that support better, evidence-based decision-making. 
The goal of the EDA is to find fitting recomendations for the client as well check multiple hypotheses regarding the data.

#### Larry Sanders
The fictonal client Larry Sanders would like a waterfront. He has limited budget and would like something nice and isolated. 
Eventhough Larry has kids of his own, he wants a central neighborhood without kids. He does not want his kids to play with other kids, because he is afraid of germs.

#### Hypotheses to be tested
1. houses at the waterfront have more squarefeet (are larger)
2. houses at the waterfront rarely have a basement
3. houses that are isolated and at the waterfront are the most expensive 

## Set up your Environment
This repo contains a requirements.txt file with a list of all the packages and dependencies you will need.

Before you can start with plotly in Jupyter Lab you have to install node.js (if you haven't done it before).
- Check **Node version**  by run the following commands:
    ```sh
    node -v
    ```
    If you haven't installed it yet, begin at `step_1`. Otherwise, proceed to `step_2`.


### **`macOS`** type the following commands : 


- `Step_1:` Update Homebrew and install Node by following commands:
    ```sh
    brew update
    brew install node
    ```

- `Step_2:` Install the virtual environment and the required packages by following commands:

    ```BASH
    pyenv local 3.11.3
    python -m venv .venv
    source .venv/bin/activate
    pip install --upgrade pip
    pip install -r requirements.txt
    ```
### **`WindowsOS`** type the following commands :


- `Step_1:` Update Chocolatey and install Node by following commands:
    ```sh
    choco upgrade chocolatey
    choco install nodejs
    ```

- `Step_2:` Install the virtual environment and the required packages by following commands.

   For `PowerShell` CLI :

    ```PowerShell
    pyenv local 3.11.3
    python -m venv .venv
    .venv\Scripts\Activate.ps1
    python -m pip install --upgrade pip
    pip install -r requirements.txt
    ```

    For `Git-Bash` CLI :
  
    ```BASH
    pyenv local 3.11.3
    python -m venv .venv
    source .venv/Scripts/activate
    python -m pip install --upgrade pip
    pip install -r requirements.txt
    ```
 
## Project strucure
The project ordner includes a documented jupyter notebook, a powerpoint presentation and a python script processind and cleaning the data as well as unit test data. 


## Lizenz
The dataset used in this project, “House Sales in King County, USA”, is publicly available on:
https://www.kaggle.com/datasets/harlfoxem/housesalesprediction

It contains real estate sales data for King County, Washington (including Seattle) from May 2014 to May 2015.
The dataset is provided for educational and non-commercial use under the terms specified by the original author (user: harlfoxem) on Kaggle.
This project uses the data solely for exploratory data analysis and demonstration of data science methods.

## Author
**luiseemelin** 