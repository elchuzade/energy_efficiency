# energy_efficiency_dataset
#### The dataset was created by Angeliki Xifara (angxifara '@' gmail.com, Civil/Structural Engineer) and was processed by Athanasios Tsanas (tsanasthanasis '@' gmail.com, Oxford Centre for Industrial and Applied Mathematics, University of Oxford, UK)
#### The labels are encoded in the following way

###### X1 - Relative Compactness
###### X2 - Surface Area
###### X3 - Wall Area
###### X4 - Roof Area
###### X5 - Overall Height
###### X6 - Orientation
###### X7 - Glazing Area
###### X8 - Glazing Area Distribution
###### Y1 - Heating Load
###### Y2 - Cooling Load

##### The link to the dataset  https://archive.ics.uci.edu/ml/datasets/Energy+efficiency
I have separated the dataset into two different datasets with only one column to predict at each time.
Thus I have got X1-8 ~ Y1 and X1-8 ~ Y2. Then i have separated each dataset to input and output,
where in both cases the inputs were the same X1-8. Then I have 80/20 proportion for splitting the dataset intp train and test sets.
I have then used Linear Regression method to predict the output Y1 and Y2 separately.
##### Software used: Python, Jupyter-Notebook, SkLearn(library).
