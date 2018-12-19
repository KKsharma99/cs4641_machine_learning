
Randomized Optimization, Machine Learning Project 2
Kunal Sharma
Ksharma74@gatech.edu
====================================================================================================

Dataset:
Name: Pima Indians Diabetes Database
URL: https://www.kaggle.com/uciml/pima-indians-diabetes-database
Rows: 768

====================================================================================================

How to Run the Code:

The code that runs the algorithms are .java files. The output is converted to visualizations with
Visualizations.ipynb (Jupyter Notebook) The notebook file requires various dependencies that are included
in the anaconda package.

# Setup
Step 1: Install anaconda (Python version 3.5 or greater) and the java eclipse environment.
Step 2: Clone the ABAGAIL library.
Step 3: Follow the setup steps found here https://github.com/pushkar/ABAGAIL/blob/master/faq.md#user-content-how-to-use-abagail-with-eclipse

# Run Code
Step 4: Run the .java files in the eclipse environment and csv files will be generated in a folder called output in the main directory

# Data Visualization
Step 5: Once all the java files have been executed, go into the main directory that has the Visualizations.ipynb notebook and type
'jupyter notebook' into the command prompt to launch the notebook editor.
Step 6: Click on the the Visualizations.ipynb notebook file to launch the notebook, then click the menu option 'Cell' -> 'Run All'

====================================================================================================

Folder includes:

README.txt

#Analysis
ksharma74-analysis.pdf

#Sampled dataset
diabetes_data.txt        [sampled training data]
test_diabetes_data.txt   [sampled test data]

#Visualization Code
Visualizations.ipynb

#Code

#Section1
rhc.java                 [Finding NN Weights using Random Hill Climbing]
sa.java                  [Finding NN Weights using Simulated Annealing] 
ga.java                  [Finding NN Weights using Genetic Algorithm] 


#Section2
tsp.java                 [Traveling Salesman Problem]
tsp_ga.java              [GA Varying Parameters for TSP]
cpt.java                 [Continuous Peak Test]
cpt_sa.java              [SA Varying Cooling Rate for CPT]

#Backup (To Restore Data if txt files are corrupted)
data_preprocessing.ipynb [Run this notebook to generate data txt files]
diabetes.csv             [Original Dataset]
