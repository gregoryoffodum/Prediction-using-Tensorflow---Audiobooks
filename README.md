# Prediction-using-Tensorflow---Audiobooks

## Scope

- Machine learning
- Deep learning
- Tensorflow

## About the dataset

[Audiofiles](https://github.com/gregoryoffodum/Prediction-using-Tensorflow---Audiobooks/blob/main/Audiobooks_data.csv) data was gathered from an audiobook application. The input data represents 2 years worth of engagement, the target/conversion (binary) represents 6 months data, checking if a customer bought another book.
    
Each row represents a customer, columns include some information in tandem with customer behaviour: book length, average book length, overall price, average price, review, miuntes listened, completion, support requests, last visited minus purchase date, targets.

The [project](https://github.com/gregoryoffodum/Customer-Churn-Machine-Learning/blob/main/Customer%20Churn.ipynb) aims to create a machine learning algorithm that can predict if a customer will buy again.


## Methodology

- Preprocessing
  - Balancing targets
  - Standardizing inputs 
  - Shuffling dataset
  - Train, test, split 
- Loading data
- Create model
   - keras, tensorflow
   - 2 hidden layers of size 50 each
   - activation functions: relu and softmax
   - optimizer: Adaptive Moment Estimation, loss: sparse categorical crossentropy   
- Test model
  
## Results

Validation set gave an accuracy of 82%, after testing, an accuracy of 77% was acheived




