Statistical analysis of anatomical networks

This repository contains data and a python notebook for carrying out statistical tests on a data fame of network parameters measures from a series of networks. This pipeline could be applied to any other type of network data, or indeed any data frame comprising a mixture of continuous and categorical variables.
To run:

1. Download the notebook file and Parameters_Tet.csv data file and place within a single directory.

2. Sample data of the original network files can be found at https://figshare.com/articles/dataset/Tetrapod_Skull_Adjacency_Matrices/1327537 if you wish to add additional networks to the data, but note that these networks require prior analysis to extract the network parameters using the methods described in the paper linked to the web address above.

3. Open the notebook in your preferred .ipynb editor, such as Jupyterlab, and run the whole notebook. 

4. If you wish to analyse the impact of different network parameters, the sections on linear modelling can be easily modified by replacing the names of the variables throughout the code. Our example data shows little of note in the principal component axes after PC2, but note also the ability to assess the impact of additional axes of variation in the Principal Component Analysis section. This may be useful using your own data if you wish to explore more variation. 


