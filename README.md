# Notebook testing environment 

This is a template to start a clean notebook without needing to modify the environment for the other notebooks.

Starting from [the main page of this repo](https://github.com/mas300labs-uofsa/new-notebook), click the green button **Use this template** and choose **Create a new repository**.  For MAS labs, choose **Owner** as mas300labs-uofsa.  If you don't see mas300labs-uofsa in the drop-down menu, let me know so I can add you to the organization.

Starting from your new repo, modify the following:

## README.md
Update the Binder button below:
- change 'new-notebook' with whatever you called the repo for your new notebook.
- if you are not in mas300labs-uofsa, then change that part of the url as well
- remove the `code quotes` around the button. 
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
