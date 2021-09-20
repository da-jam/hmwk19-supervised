# hmwk19-supervised
for supervised learning


two datasets
training (2019), and a validation(2020Q1)

two methods
Regression, random forest

two sets
unscaled 
scaled

Unscaled
Regression - unscaled
Training Data Score: 0.6522167487684729
Testing Data Score: 0.6472906403940887
Validation Data Score: 0.5161633347511697

RandomForest - unscaled
Training Score: 1.0
Testing Score: 0.7697865353037767
Validation Score: 0.6278179498085921

Scaled
Regression - scaled
Training Data Scaled Score: 0.7041050903119869
Testing Data Scaled Score: 0.6991789819376026
Validation Data Scaled Score: 0.7579753296469588

RandomForest - scaled
Training Scaled Score: 1.0
Testing Scaled Score: 0.7694581280788177
Test ScaledScore: 0.6290940025521055

the unscaled data shows lower model scores, although the fit of the randomforest train maybe to data focus
It is expected that the unscaled data has a lower score due to the variance of the absolute values.

The regression model shows a better fit for the scaled data, than the randomforest.
The randomforest may still be overly controlled by the train data.

Even the higher scores are less than .80, which does not indicate a good model for predictions.

Note these are model fits with default parameters, likely investigating hyperparameters or K analysis for influencial nodes
is needed.
