Project can be run using Google Colab using the following:

First clone the repository
!git clone https://github.com/taranehrouh/CPEN355_FinalProject.git

Then change directory into the repository
%cd /content/CPEN355_FinalProject/

Plots can be found in training folder in the CNN and Random Forest folders, but the following instructions can be used to obtain the plots

To run the Random Forest model and obtain the loss plot, confusion matrix, and F1 scores, use:
!jupyter nbconvert --to notebook --execute training/random_forest/random_forest.ipynb

To run the CNN models and obtain the loss plot, confusion matrix, and F1 scores, use:
!jupyter nbconvert --to notebook --execute training/cnn/model_eval.ipynb