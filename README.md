# Credit_Risk_Analysis

## Overview

### The purpose of this challenge was to predict the credit risk by oversampling and undersampling the data and then comparing the two machine learning models. 

## Results

### The results from this are:
· Naive Random Oversampling has a balanced accuracy score of 0.6742571941946299 with a precision of .99 and a recall of .61
· SMOTE Oversampling has a balanced accuracy score of 0.6623356588465208 with a precision of .99 and a recall of .69
· ClusterCentroids Resampler has a balanced accuracy score of 0.5442661782548694 with a precision of .99 and a recall of .40
· SMOTEENN has a balanced accuracy score of 0.6447701423556762 with a precision of .99 and a recall of .57
· Balanced Random Forest Classifier has a balanced accuracy score of 0.7885466545953005 with a precision of .99 and a recall of .87
· Easy Ensemble ADABoost Classifier has a balanced accuracy score of 0.9316600714093861 with a precision of .99 and a recall of .94

## Summary

### When looking at all of the results we can see that they all have the same precision score. Based off of all the information that we gathered with this dataset I recommendation would be that none of these methods would be good to use. I say this because when we check all the confusion matrix results all of them seem to have a very high false negative score. To me I think it'd be better to find one that doesn't have one that has that high of scores. I don't think it'd be in their best interest to go with any of them. 
