# Practical Machine Learning Project

## Contents
- `README.md`
- `index.Rmd` - R Markdown script that does the following: downloads the data directly from website; cleans data by removing missing values and unnecessary variables; creates a training and testing set to run prediction algorithms; compares prediction algorithms and selects best model based on accuracy rate; predicts classes from smaller out-of-sample test set.
- `index.html` - compiled HTML file.
- `figure` - folder that contains 4 figures: `baseline-model-1.png` illustrates the decision tree algorithm. `plot-accuracy-rf-1.png` and `plot-error-rf-1.png` show the cross-validation accuracy rate and the cross-validation error rate, respectively. `varimp-rf-1.png` lists the top 10 most important predictors (variable importance) given by the random forest model.
- `data` - folder with the csv files used in the analysis. 

## Getting Started
- Run the `index.Rmd` script to generate the predictions.
- For more information on the data and study, go to: http://groupware.les.inf.puc-rio.br/har
