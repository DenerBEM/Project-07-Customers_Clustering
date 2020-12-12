# Project-07-Customers_Clustering
**Description**: *Clustering customers based on their energy consumption*

### :orange_book: Libraries used:

`import pandas as pd`<br>
`import numpy as np`<br>
`import matplotlib.pyplot as plt`<br>
`import seaborn as sns`<br>
`from sklearn.preprocessing import StandardScaler`<br>
`from sklearn.cluster import KMeans`<br>
`from sklearn.decomposition import PCA`<br>
`from sklearn.metrics import silhouette_score`<br>
`from yellowbrick.cluster.elbow import kelbow_visualizer`<br>
`import warnings`<br>


### :dart: About:

The goal of this project is to group customers with similar characteristics in the same group. So **first I loaded the dataset household_power_consumption.txt** and then I had to clean some data because of its format and variables types, this process is called **data wrangling**. After that I did the **pre-processing step**, in this step I have to prepare my dataset to the algorithm each is the last step. Finally I used the library **KMeans to group the data, and calculate de Silhouette Score of the models**, in this case the second model is the best one, with **Silhouette Score of 0.56 approximately.**

### :open_file_folder: Files:

*LICENSE
*Projeto09-Agrupando_Clientes_Por_Consumo_de_Energia.ipynb
*README.md
* The file.txt you can find here http://archive.ics.uci.edu/ml/machine-learning-databases/00235/household_power_consumption.zip

the files in the repository with a small description of each, a summary of the results of the analysis, and necessary acknowledgements. Students should not use another student's code to complete the project, but they may use other references on the web including StackOverflow and Kaggle to complete the project.
 
