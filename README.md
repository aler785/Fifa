# Fifa

Analysis on the Fifa dataset obtained from Kaggle (https://www.kaggle.com/karangadiya/fifa19).

The project includes 2 subfolders grouping the material necessary to perform the analysis: 
* .ipynb_checkpoints, there is a file describing the dataset column name and a second file with the Handout instructions, 
* data, there is the FIFA dataset.

The files outside of these 2 folders are the ones necessary to the data science analysis performed.
Data.csv is the raw data used.
The 2 elaboration files are:
1. descriptive_stat.ipynb<br/>
File the descriptive statistics on the FIFA, the first part of this file is necessary to clean the dataset and to gather a first impression on the players, the second part of the file describes some key correlation matrices among the different features of the dataset. These are relevant and necessary to build machine learning algorithms and prediction formulas on the measures in play.
2. ml.ipynb<br/>
File with machine learning on the key FIFA measures, there are 3 exercises in total:<br/>
2.1 a linear regression to predict the 'Overall' value of a player considering the other technical characteristics<br/>
2.2 a linear regression to predict the 'Overall' value of a pòayer considering only 3 other factors: 'Value','Wage','Potential'<br/>
2.3 a decision tree classifier to show how is it possible to predict the simplified position of a player starting from his characteristics with a good approximation (85%)<br/>
