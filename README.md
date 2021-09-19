# module_14_challenge

## SVC Classifier Model
### 1. Actual Returns vs. Strategy Returns - Original Plot
![Original Plot](https://user-images.githubusercontent.com/85372363/133946513-6fbb4df0-8632-4e8a-84b6-527023c92337.png)

### 2. Tuned Plot - Size of training set was adjusted by reducing the training period from 3 months to 2 months. As a result the strategy returns are closer to actual returns than in the original plot (please note that the scale is smaller).
![Training Period 2 months](https://user-images.githubusercontent.com/85372363/133946527-e0031bc7-8709-4c2b-b898-ccaab901e99b.png)

### 3. Tuned Plot - The short window of the SMA was increased from 4 days to 10 days. This further improved the plot and the strategy returns are very close to actual returns.
![SMA_Short_Window_10](https://user-images.githubusercontent.com/85372363/133946591-f654e190-8b98-4222-aaf4-24dfcc12f6ff.png)

## New Machine Learning Classifier - Logistic Regression Model
### This logistic regression model performed worse than the SVC classifier baseline model and the tuned trading algorithms.
![Logistic_Regression](https://user-images.githubusercontent.com/85372363/133946822-786d912a-1630-42d0-8e75-5876b3bd59f2.png)
