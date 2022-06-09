# Perovskite-ML
This project is my attempt at using chemical features to predict the crystal quality or 'score' of lead-halide perovskite crystals.
The PSKITECSV.csv dataset contains a wealth of data regarding different A-site cations, reaction conditions and solvents that correspond to 
a crystal score for each experimental run. 

I attempt to use scikit-learn classification models along with EDA and feature engineering in order to maximize the accuracy of classifications
that can be made from the dataset. I focus only on one A-site cation perovskite, ethylamine hydriodide, because it is observed the most in the dataset. 
After removing redundant features, I conduct normalization, log and square root transformation, and PCA on the data in order to improve accuracy and
efficiency. After creating preliminary models, I use a grid search technique to optimize model hyperparameters and end up with my final models. The 
best ones in this project are able to predict crystal score with an accuracy of over 80%.

I created this project as a way to demonstrate to both myself and others that machine learning models could prove useful to the field of chemistry.
This dataset was one of my first projects in the world of Computational Chemistry and by going back to it now, after honing my ML skills for several months
I was able to return to this dataset and create meaningful models that could, in theory, be used to optimize perovskite synthesis.
