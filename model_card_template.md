# Model Card

For additional information see the Model Card paper: https://arxiv.org/pdf/1810.03993.pdf

## Model Details
created by Olivia Burns on 2/10/2025. This is a RanfomForestClassifier Model.

## Intended Use

the use of this model is to determine is someone makes ober 50,000 a year based on the following characteristics:
age
workclass
fnlwgt
education
education-num
martial-status
occupation
relationship
race
sex

## Training Data

The training data was using 80% of the full census dataset

## Evaluation Data

To evaluate the data with the model, the other 20% was used

## Metrics
_Please include the metrics used and your model's performance on those metrics._

Precision: 0.7242 | Recall: 0.6207 | F1: 0.6685

## Ethical Considerations

There are many factors that will contribute to someones salary that cannot be measured. This data has a wide variety of variables, but in the real world there are so many other factors that play a part.

## Caveats and Recommendations

This data is from 1994 when salaries were much lower. If this was more up to date, I think the results would be a lot different.
