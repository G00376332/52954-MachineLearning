# GMIT Machine Learning Assignment Tasks 2020

This repository contains a Jupyter notebook with Machine Learning and Statistics assignment tasks for completion in the semester 2020

[See here for the instructions](https://github.com/G00376332/52954-MachineLearning/blob/master/assessment.pdf)

## The main goal and the key points of each task

| **Task** | **Description** |
| --- | --- |
| 1 | Write a Python function called sqrt2 that calculates and prints to the screen the square root of 2 to 100 decimal places.Your code should not depend on any module from the standard library or otherwise. You should research the task first and include references and a description of your algorithm. |
| 2 | The Chi-squared test for independence is a statistical hypothesis test like a t-test. It is used to analyse whether two categorical variables are independent. The Wikipedia article gives the table below as an example, stating the Chi-squared value based on it is approximately 24.6. Use scipy.stats to verify this value and calculate the associated p value. You should include a short note with references justifying your analysis in a markdown cell. |
| 3 | The standard deviation of an array of numbers x is calculated using numpy as np.sqrt(np.sum((x - np.mean(x))**2)/len(x)) . However, Microsoft Excel has two different versions of the standard deviation calculation, STDEV.P and STDEV.S . The STDEV.P function performs the above calculation but in the STDEV.S calculation the division is by len(x)-1 rather than len(x) . Research these Excel functions, writing a note in a Markdown cell about the difference between them. Then use numpy to perform a simulation demonstrating that the STDEV.S calculation is a better estimate for the standard deviation of a population when performed on a sample. Note that part of this task is to figure out the terminology in the previous sentence. |
| 4 | Use scikit-learn to apply k-means clustering to Fisher’s famous Iris data set. You will easily obtain a copy of the data set online. Explain in a Markdown cell how your code works and how accurate it might be, and then explain how your model could be used to make predictions of species of iris. |


## How to run code the in Jupyter Notebook

There are a couple of ways to view and run notebook.

   1. The file can be downloaded locally and run on the PC with Jupyter Notebook installed
   2. It can be viewed in the web browser on the [nbviewer](https://nbviewer.jupyter.org/github/52954-MachineLearning/blob/master/Tasks.ipynb)
   3. Directrly on the [GitHub](https://github.com/G00376332/52954-MachineLearning/blob/master/Tasks.ipynb)

### How to install Jupyter Notebook

The most convenient way to quickly install Jupyter Notebook is the use of Anaconda package.  
Anaconda conveniently installs Python, the Jupyter Notebook, and other commonly used packages for scientific computing and data science.

Use the following installation steps:

Download Anaconda. Is recommend downloading Anaconda’s latest Python 3 version (currently Python 3.9).
Install the version of Anaconda which was downloaded, following the instructions on the download page.

To run the notebook type in the cmd or commander:
 **jupyter notebook**



## References

1. [Jupyter - Installing Jupyter Notebook](https://jupyter.readthedocs.io/en/latest/install.html)
1. [Jupyter - nbviewer](https://nbviewer.jupyter.org/)
