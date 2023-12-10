# WHEN TO USE EACH MODEL (SUPERVISED)
## Nearest neighbors:
- Small datasets
- Easy to train/explain
- Good baseline
## Linear models
- Go-to as first algorithm to try
- Good for large datasets
- Good for high dimensional data
## Naive bayes
- Only classification
- Good for large datasets and high dimensional data
- Often less accurate than linear models
## Decision trees
- Fast
- Dont need scaling
- Can be visualized
- Easily explained

## Random forest
- Robust and powerful
- Dont need scaling
- Not good for high dimensional and sparse data (text)

## Gradient Boosting
- Often slightly more accurate than random forests
- Need more tuning
- Faster to predict than random forests

## Support Vector Machines
- Powerfull for medium sized data with similar meaning
- Scaling of the data
- Sensitive parameters

## Neural Networks
- Very complex models for large datasets
- Sensitive to scale 
- Not that good with different meaning features
  
# Guidelines
- Working on a new dataset
  - Start with linear models/naive bayes,nearest neighbors
- After better understading of the data, move to more complex models