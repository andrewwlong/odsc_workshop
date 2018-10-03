# Introduction to Clinical Natural Language Processing: Predicting Hospital Readmission with Discharge Summaries

Clinical notes from physicians and nurses contain a vast wealth of knowledge and insight that can be utilized for predictive models to improve patient care and hospital workflow. In this workshop, we will introduce a few Natural Language Processing techniques for building a machine learning model in Python with clinical notes. 

As an example, we will focus on predicting unplanned hospital readmission with discharge summaries using the MIMIC III data set. After completing this tutorial, the audience will know how to prepare data for a machine learning project, preprocess unstructured notes using a bag-of-words approach, build a simple predictive model, assess the quality of the model and strategize how to improve the model. 

# Getting Access to MIMIC III

The MIMIC III data set requires requesting access in advance, so please request access as early as possible. You can follow step-by-step instructions for requesting access here (https://towardsdatascience.com/getting-access-to-mimic-iii-hospital-database-for-data-science-projects-791813feb735) or follow the instructions on the MIMIC III website here (https://mimic.physionet.org/gettingstarted/access/). Once you request access, it usually takes a few days to get approved so please do this as early as possible. 

# Getting Started

For this workshop, you will need the following Python packages:
1. Python 3
2. `skikit-learn`
3. `pandas`
4. `numpy`
5. `jupyter`
6. `ipykernel`

## Easiest way: Anaconda Distribution of Python
For those with the Anaconda Distribution, I have created a yml environment file (odsc_west_2018.yml) that can be used to create a virtual environment with the required information. 

1. `$ conda env create -f odsc_west_2018.yml`
2. `$ activate odsc_west_2018.yml`
3. `$ python -m ipykernel install --user --name odsc_west_2018`

## Run the Jupyter Notebook
	$ jupyter notebook

 