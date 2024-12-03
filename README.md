# Guided Capstone Project for Stony Brook University Data Science Bootcamp

In this guided capstone project for the Stony Brook University Data Science Bootcamp program, the Data Science Method is used to explore the following question:


What opportunities exist for Big Mountain Resort to best capitalize on their facilities and adjust their ticket price to increase revenue in order to account for higher operating costs this upcoming ski season?


A dataset including information from ski resorts across the country was examined to understand which facilities winter sports enthusiasts are willing to pay more for, and how Big Mountain Resort stacks up among its competitors.


While exploring the dataset,  initial cleaning steps were performed to edit missing or unusual values, check for duplicate resorts, differentiate a resort’s region versus state, and visualize the distribution of features. 


Next, initial modeling was performed to develop an algorithm to predict resort price based on its features. The data was split into a 70/30 train/test split, and a two models were constructed: a linear regression model and a random forest model. The random forest model was selected since it had a lower mean absolute error and less variability as determined through cross validation. 


The finalized random forest model was used to estimate the ticket price for Big Mountain Resort. Its modeled price was determined to be $\$$95.87, which is higher than its actual price of $\$$81.


In conclusion, it is recommended that Big Mountain Resort should add a run to a point 150 feet lower down and install an additional chair lift to bring skiers back up. The increase in suggested ticket price from these additional features, along with the modeled ticket price, supports a final ticket price of approximately $98. Even with the new features to install and the increased operating cost due to the new chairlift, the higher ticket price should produce enough revenue to account for these expenses. Additionally, Big Mountain could test closing a few runs and reducing ticket price accordingly and observe how this affects the number of visits and revenue. In the future, it would be useful to create a program or an app where the business executives could manipulate the values of the features of Big Mountain resort and see how this affects the modeled price.


The original README for this project can be found below.


# DataScienceGuidedCapstone

Hello students!
Welcome to the Data Science Guided Capstone! 

## Getting Started

Start by forking this repository to your personal GitHub account and cloning the fork to your local machine. 

**Note**: If forking and cloning a repo is new to you and/or github is new to you then it is strongly suggested to use [GitHub desktop](https://desktop.github.com/) and follow instructions in the docs [here](https://docs.github.com/en/free-pro-team@latest/desktop/contributing-and-collaborating-using-github-desktop/cloning-and-forking-repositories-from-github-desktop).

From https://github.com/springboard-curriculum/DataScienceGuidedCapstone press the green "code" dropdown and then press "Open with GitHub Desktop". This will fork the springboard repository into your own github account and then clone that fork to your local machine - it is in here that you will do your work and push your changes back to your fork of the repo in your own github account. 

You will find the notebooks in the Notebooks/ directory. 

You will find instructions on how to complete and submit each step of the Guided Capstone in the course materials. Each subunit will focus on one step of the Capstone, corresponding to a step of the Data Science Method. Find the Jupyter Notebook corresponding to the subunit you are working on, and open it. Follow along as you are guided through the work, and fill in the blanks!

When you are done with the notebook, push the changes to your personal GitHub account.

## Pipenv

The `Pipefile` has all the python dependencies and requirements you should need. So you can use [Pipenv](https://pipenv-fork.readthedocs.io/en/latest/) is you want to create a seperate python enviornment for this project. 

To install pipenv see [here](https://pipenv-fork.readthedocs.io/en/latest/#install-pipenv-today).

To create the env and install the required libraries (once you have pipenv installed) you can just do:
```
pipenv install
```

Then to activate the env and launch jupyter from this env you can do something like the below two commands:
```
pipenv shell
jupyter lab
```
