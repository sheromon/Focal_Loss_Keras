# Multi-class classification with focal loss for imbalanced datasets

This repository was forked from [Tony607's repository](https://github.com/Tony607/Focal_Loss_Keras). I've made many changes, but thank you to [Tony607](https://github.com/Tony607) for putting together the initial Jupyter notebook!

## How to Run
### Clone or download this repo
```
git clone https://github.com/sheromon/Focal_Loss_Keras
```
### Install required libraries
`pip install -r requirements.txt`


Download the fraud data set from Kaggle, extract the csv file, and put it in a directory named `input` in the main project directory.
https://www.kaggle.com/ntnu-testimon/paysim1

From a terminal in the main project directory, run
```
jupyter notebook
```
The example baseline and focal loss code is in the notebook
```
src/fraud_detection_w_focal_loss.ipynb
```

Happy coding! Leave a comment if you have any questions.
