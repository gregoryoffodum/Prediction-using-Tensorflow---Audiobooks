# Prediction-using-Tensorflow---Audiobooks

## Scope

- Machine learning
- Deep learning
- Tensorflow

## About the dataset

[Audiofiles](https://github.com/gregoryoffodum/Prediction-using-Tensorflow---Audiobooks/blob/main/Audiobooks_data.csv) data was gathered from an audiobook application. The input data represents 2 years worth of engagement, the target/conversion (binary) represents 6 months data, checking if a customer bought another book.
    
Each row represents a customer, columns include some variables in tandem with customer behaviour: Customer ID, Book length in mins_avg (average of all purchases), Book length in minutes_sum (sum of all purchases), Price Paid_avg (average of all purchases), Price paid_sum (sum of all purchases), Review (a Boolean variable), Review (out of 10), Total minutes listened, Completion (from 0 to 1), Support requests (number), and Last visited minus purchase date (in days). These are the inputs for the model, excluding customer ID.

The targets are a Boolean variable (so 0, or 1). We are taking a period of 2 years in our inputs, and the next 6 months as targets. So, in fact, we are predicting if: based on the last 2 years of activity and engagement, a customer will convert in the next 6 months. If they don't convert after 6 months, chances are they've gone to a competitor or didn't like the Audiobook way of digesting information.

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




