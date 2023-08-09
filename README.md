# Peugeot 206 Type 2 Price Prediction
This project aims to train a machine learning model to predict the price of a Peugeot 206 Type 2 car. To obtain the necessary data for training, we will perform web scraping on the Divar website, which contains car sales ads. We will use the Selenium library for web scraping and the BeautifulSoup library for parsing the extracted data. Additionally, we will employ linear regression as the machine learning algorithm for price prediction.

## Steps
### 1. Web Scraping
We will extract valuable information from car advertisements on the Divar website using Selenium. The important factors that can affect the car's price, such as the year, mileage, color, and other relevant features, will be extracted and saved. Moreover, descriptions and photos of the cars might provide bonus points in terms of extracting additional valuable information.

### 2. Data Pre-processing
Once the data is collected, we will perform the necessary pre-processing steps to prepare it for training the machine learning model. This may include handling missing or invalid data, converting categorical variables into numerical representations, scaling numerical features, and splitting the data into training and testing sets.

### 3. Model Training
We will train a linear regression model using the pre-processed data. Linear regression is a suitable choice for this project as it can capture the linear relationship between the car's features and its price. The model will learn from the training data and optimize its parameters to make accurate predictions.

### 4. Model Evaluation
To evaluate the trained model, we will use appropriate evaluation metrics such as mean squared error (MSE) or root mean squared error (RMSE). These metrics will help us assess how well the model performs in predicting the price of Peugeot 206 Type 2 cars. We will analyze the results and determine the model's accuracy and reliability.

### 5. Saving the Trained Model and Developing a Prediction Script
Once the model is trained and evaluated, we will save it in a suitable format for future use. We will then develop a script that takes car information as input and predicts whether the price suggested by the seller is reasonable or not. This script will utilize the trained model to make predictions based on the provided car details.


## Contributing
Contributions to this project are welcome. If you find any issues or have suggestions for improvements, please open an issue or submit a pull request on the GitHub repository.
