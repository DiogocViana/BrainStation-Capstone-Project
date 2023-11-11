Capstone Project
Data Science Program
TED Talk
Author: Diogo Viana
contact: d.cviana@outlook.com


The principal objective of my project is to assist the TED talk speaker to achieve a high number of views based on the choice of the description

This document has the intention to guide you in the process of reading each file using the correct order. It also will guide you through the content of each document.
There are three csv files ‘talks_info.csv’, ‘talk_info_clean.csv’ and ‘talkes_info_clean_Tableau.xlsx’. In addition, there are three Jupyter Notebooks, Tableau workbooks (.twb) and the report in PDF format.

Before opening the Jupyter notebooks, I may suggest you read the report in the PDF file named ‘Report_Diogo_Viana_TED_Talk’ to have a brief idea of the project.

The notebook named Notebook_1_Data_Cleaning_and_EDA_TED_talk should be the first to be opened and the correct csv file is ‘talks_info.csv’. You will not need to install any conda environment. 
In this notebook, I completed the data cleaning process and exploratory data analysis. By the end of it, there will be a code to save the cleaned file with the name ‘talk_info_clean.csv’

The notebook named ‘Notebook_2_Modeling_TED_talk’ should be the second one to be opened. You have the option of using the csv file I sent with my work (‘talk_info_clean.csv’) or utilizing
the csv saved from the previous notebook. This notebook consists of the modeling part where I used Logistic Regression, KNN and Decision Trees to identify the best model to help to build an ideal description.
This notebook does not require any special conda environment.

Following the order, the next one should be the notebook ‘Notebook_3_RNN_TED_Talk’. The correct file for this notebook is the same from the second notebook, which is ‘talk_info_clean.csv’.
In this notebook I completed a Recurrent Neural Network and to run it, you will need a special conda environment.

Codes for creating the conda environment:

Step 1. Create the new empty environment named 'deeplearning'.

conda create -n deeplearning python=3.8

Step 2. Activate the new environment.

conda activate deeplearning

Step 3. Install all the basic packages we'll need (including jupyter notebook and lab).

conda install numpy=1.19.2 pandas matplotlib jupyter jupyterlab pydot pillow seaborn

Note: you may get an initial frozen solve warning, but wait it out and packages should get installed using a flexible solve.

Step 4 - Mac Instructions: Install TensorFlow in this environment.

Mac users should install Tensorflow 2.7.0: conda install -c conda-forge tensorflow==2.7.0
Windows users should install Tensorflow 2.3.0: conda install -c conda-forge tensorflow=2.3.0

Step 5. Install some more packages that we'll need in the TensorFlow Lecture.

conda install scikit-learn=0.24.1 nltk
conda install -c conda-forge gensim=3.8.3

Step 6. Install PyTorch and TorchVision.

conda install -c pytorch pytorch=1.4 torchvision=0.5.0
conda install -c conda-forge tqdm

Optional. Creating a Jupyter kernel for this environment (needed if you don't have nb_conda_kernels installed in your base environment):

ipython kernel install --name "deeplearning" --user

PS.: I had some issues related to Step 3 when I opened my notebook. I needed to come back and install a more recent version. But you may not have this problem.

As I mentioned in the beginning, there is also a Tableau workbook which will find a dashboard with some  graphics related to my analysis.

Please, feel free to reach out if you have any questions about the above guidance.
