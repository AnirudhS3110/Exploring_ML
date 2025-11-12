# Outliers:
### THey are Unusual Datapoints which are very different from rest of the observation.
### Having these Outliers wold gheavily impact the model, So its better to remove these before training our model.
## Techniques:
### - Percentile
### - C-Score
### - Standard Deviation
### -  Through Visualisation: Box Plot or scatter plot

## Percentile Technique:
### - We are removing quantiles from Extreme left and right ends of the range.
### - For example we will remove the records whose values is greater than .95 percentile and less than 0.5 percentile


### Note:
#### - we can use   .sample(n) to sample random 'n' rows from the DataFrame