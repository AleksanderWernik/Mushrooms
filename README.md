# Mushrooms classification :mushroom:

Title: Secondary mushroom data

Sources:
	(a) Mushroom species drawn from source book: Patrick Hardin.Mushrooms & Toadstools. Zondervan, 1999
  (b) Inspired by this mushroom data: Jeff Schlimmer.Mushroom Data Set. Apr. 1987. url:https://archive.ics.uci.edu/ml/datasets/Mushroom.
	(c) Repository containing the related Python scripts and all the data sets: https://mushroom.mathematik.uni-marburg.de/files/ 
	(d) Author: Dennis Wagner
	(e) Date: 05 September 2020

### Objective 🎯
The main goal is to predict if the mushrooms are edible or poisonous. 

### Description Of Dataset 📊 
This dataset includes 61069 hypothetical mushrooms with caps based on 173 species (353 mushrooms per species). Each mushroom is identified as definitely edible, definitely poisonous, or of unknown edibility and not recommended (the latter class was combined with the poisonous class). 
Of the 20 variables, 17 are nominal and 3 are metrical.

Appropriate graphs and metrics were generated for the data analysis.

### Methodology ⚙️
10 classifiers were sorted out based on their roc_auc_score on the testing data. 3 of classifiers showed overfitting of the model. Best results gives SVM with 99,7% of roc auc score and GradientBoosting Classifier.
