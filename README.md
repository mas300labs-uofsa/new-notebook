# Notebook testing environment 

This is a template to start a clean notebook without needing to modify the environment for the other notebooks.

These instructions are specific to the mas300labs-uofsa organization.

Starting from [the main page of this repo](https://github.com/mas300labs-uofsa/new-notebook):
- click the green button **Use this template**
- choose **Create a new repository**
- choose **Owner** as mas300labs-uofsa
- contact me if you don't see mas300labs-uofsa in the drop-down menu

Starting from your new repo, modify the following:

## README.md
Update the Binder button below:
- change 'new-notebook' with whatever you called the repo for your new notebook
- remove the `code quotes` around the button
```
Click on the Binder button to open the Notebook:
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/mas300labs-uofsa/new-notebook/HEAD?labpath=index.ipynb)
```

## environment.yml
Modify the environment to add any libraries you need.  Currently, it only has:
- pandas
- numpy
- matplotlib
- wget
- pip


## index.ipynb
Then modify the Notebook.
