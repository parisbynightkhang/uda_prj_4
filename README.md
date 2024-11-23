# Starbucks Capstone Challenge: Predicting Effective Offers

This repository contains the code and reports for the **Udacity Data Scientist Nanodegree** capstone project, where I participated in the **Starbucks Capstone Challenge**. The goal of this project was to use Starbucks App user data to predict the effectiveness of different types of offers.

## 1. Installation

To run this project, you will need Python 3.* and the following libraries:

- **Pandas**: For data manipulation and analysis.
- **NumPy**: For numerical computing.
- **Scikit-learn**: For machine learning algorithms and tools.
- **TensorFlow**: For deep learning models.
- **Keras**: High-level neural network API for building deep learning models.
- **Matplotlib**: For data visualization.

You can install these libraries using pip:

```
pip install pandas numpy scikit-learn tensorflow keras matplotlib
```

### 2. Project Motivation
This project serves as the capstone for the **Data Scientist Nanodegree** program with **Udacity**. As part of the program, I tackled the **Starbucks Capstone Challenge**, aiming to predict the effectiveness of offers on the Starbucks mobile app.

The effectiveness of an offer is most influenced by:
1. **Reward**: The reward granted after completing an offer.
2. **Membership Duration**: The number of days a customer has been a member.
##### Model Selection:
Two models were used to predict the effectiveness of offers:
Simple Neural Network (NN): Also achieved 48.28% accuracy.
Random Forest: Showed signs of overfitting and was less effective than the neural network models.

## 3. File Descriptions

This repository contains the following files:

1. **`Starbucks_Capstone_notebook.ipynb`**: The main project report and notebook.
2. **Data files** located in the `data/` folder:
   - `portfolio.json`: Contains information on the different offers available.
   - `profile.json`: Contains customer demographic and behavioral information.
   - `transcript.json`: Contains records of customer interactions with offers.

## 4. Blog Post

For a detailed analysis of the project, visit my blog post:  
**[Customer Behavior Analysis at Starbucks](https://exploreseattle20241017.blogspot.com/2024/11/customer-behavior-analysis-at-starbucks.html)**

## 5. Licensing, Authors, Acknowledgements

The data for this project was provided by **Udacity** as part of the **Data Scientist Nanodegree** program. Special thanks to Udacity for the opportunity to participate in this challenge.

