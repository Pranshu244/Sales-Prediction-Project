# Sales-Prediction-Project
Sales Prediction model using Linear Regression 
This project predicts sales based on TV, Radio, and Newspaper budgets using Linear Regression. Trained on 200 samples from the Advertising dataset.

## Performancce
- MSE=3.17

- RMSE = 1.78

- R<sup>2</sup> = 0.9
  
## How to see Sales Prediction model in action on a website?
1. Open 'Linear Regression Model' folder.
2. Download 'model.pkl' file.
3. Now open Website Code.
4. Open 'Sales_Prediction_Website.ipynb' in google colab.
5. Click 'Run all'.
6. Copy IPv4 address from output of second last cell.
7. You will get an URL in second last cell with a line 'your url is: __'.
8. Click on that link.
9. You will be redirected to an website.
10. On that website add IPv4 address you copied earlier in 'Tunnel Password' box and submit it.
11. Sales Prediction Website will be open.
12. Upload 'model.pkl' in 'Drag and drop file here'.
13. Now write TV Ad Budget, Radio Ad Budget, Newspaper Ad Budget and clcick 'Predict Sales' buttoon.
14. You will get 'Predicted Sales'.
    
## How to view code of Linear Regression.
1. Open 'Linear Regression Model' folder.
2. Open 'CSV Dataset' folder.
3. Download 'Advertising Budget and Sales.csv'.
4. Now come back to 'Linear Regression Model' folder.
5. Open 'Sales_Prediction.ipynb' in google colab.
6. Upload 'Advertising Budget and Sales.csv' in files of  'Sales_Prediction.ipynb' in google colab.
7. Click 'Run all'.

## Dataset Source
The dataset is taken from Kaggle.
https://www.kaggle.com/datasets/yasserh/advertising-sales-dataset
   
## Dependencies
- Python
- Scikit-learn
- Streamlit
- NumPy
- Pandas
- Matplotlib
- Pickle
  
## License
MIT License
