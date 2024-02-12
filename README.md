# datafun-07-applied Repository for Project 7: Apply Supervised Machine Learning - Simple Linear Regression

## Project Purpose
To implement the guided projects in 10.16 and 15.4 of textbook: <a href=https://amzn.to/2KfCptN>_Intro to Python for Computer Science and Data Science: Learning to Program with AI, Big Data and the Cloud_.</a> 

## Overview
Employ a type of supervised machine learning, simple linear regression, to train a model using all available data and use the resulting model (a "best-fit" straight line) to make predictions. 

### Project Requirements include:
 - Build a model
 - Make predictions
 - Visualize the model
 - Publish your insights

## Project Structure & Deliverables
- `datafun-07-applied`: Project repository
- `README.md`: Provides an overview of the project, as well as instructions for setting up and executing the environment.
- `requirements.txt`: Lists all packages required for the project.
- `examples` files: Contains all associated textbook materials to perform project
- `tmontague_ml.ipynb`: Jupyter Notebook file

## Environment Setup & How to Install and Run the Project

- Create a new GitHub repository named `datafun-07-applied` with a default `README.md.`

- Clone the repository to your local machine.
```python
git clone https://www.your-repository.com
```
- Create a Project Virtual Environment in the .venv folder.
- Activate the Project Virtual Environment.
```python
py -m venv .venv
```
```python
.\.venv\Scripts\Activate.ps1
```

- Install dependencies into your `.venv` (shiny and pandas) and freeze into your requirements.txt.

```python
pip install pandas
pip install seaborn
pip instal matplotlibl
```
```python
pip freeze > requirements.txt
```
- Add a useful .gitignore to the root project folder with `.vsode/` and `.venv/` to prevent adding to repository

- Git add and commit with a useful message (e.g. "initial commit") and push to GitHub.
    
    `git add .`
   
    `git commit -m "initial commit"`
   
    `git push origin main`
   
## Project Organization & Data Files

- Access and download associated files and data from [IntroToPython/examples](https://github.com/pdeitel/IntroToPython/tree/master/examples)
- Create `examples` subfolder in the root project repository folder: `datafun-07-applied`
- Add downloaded associated files and data to the `examples` subfolder

## Start the project
### CC 7.4: Start a New Jupyter Notebook
- Open `datafun-07-applied` root project repository in VS code
- Open a terminal in your root project repository folder and run `git pull` to make sure you have the latest changes from GitHub
- Create new notebook in root project repository named: `tmontague_ml.ipynb`
- Add Markdown cell at the top of new notebook with Title, Author, and clickable link to project repository
- Add Python cell with import statements
```python
import pandas
import seaborn
import matplotlib
```


