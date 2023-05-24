# Data Science Portfolio - Seungbae Son
This portfolio is the compilation of all data science projects I created to find solutions by exploring data. This portfolio contains 4 categories with a wide range of topics, such as Classification, Regression, Neural Networks, Image Recognition, and AI algorithms.

## Classification Problems

### Credit Default Prediction
Credit Default Prediction is a Kaggle competition from American Express. The objective of this competition was to build a model to predict credit default by using customers' data. The dataset contains 5.5M+ data with 189 features and a lot of missing data. Since there was no information about explanatory variables, I applied a variety of feature engineering techniques to create significant features. I finished this competition in the top 5% among 4,874 teams on the public leaderboard. The project can be found [here](https://github.com/KevinSBSon/Credit-Default-Prediction).<br>
<br>
*XGBoost, LightGBM, Scikit-Learn, Classification, Feature Engineering, Data Processing

## Regression Problems

### Predicting House Prices with Linear Regression and Gradient Boosting: A Comparative Study
Predicting house prices accurately is a challenging task due to the complex and dynamic nature of the housing market. In recent years, machine learning techniques have been widely used for house price prediction. In this paper, we conduct a comparative study of Lidge, Lasso linear regression, and Gradient Boosting for house price prediction on a Kaggle competition dataset. We first perform exploratory data analysis and feature engineering to prepare the data. Then, we train and evaluate models using Lidge, Lasso linear regression, and Gradient Boosting with hyperparameter tuning. Our experimental results show that Gradient Boosting outperforms Lidge and Lasso linear regression in terms of predictive accuracy, with a root mean squared error (RMSE) of 0.0129. However, Lasso linear regression and Lidge provide interpretable feature importance scores, which can be useful for feature selection and model interpretation. Our study highlights the importance of choosing appropriate machine learning techniques for house price prediction, depending on the specific requirements of the application.
<br>
<br>
*Regression, Ridge, Lasso, Gradient Boosting, Scikit-Learn

### Coming Year's Most Popular Music Prediction
The objective of this project was to build a model to predict the new trend in music in the coming year. I used a music dataset from Spotify that consists of 169k songs with their characteristics, such as danceability, energy, duration, etc. The predictive model is built by combining multiple time series regression models on each feature. The cosine similarity is applied to identify the close relationship between predicted data and the new most popular songs. The project can be found [here](https://github.com/KevinSBSon/Coming-Years-Most-Popular-Music-Prediction).
<br>
<br>
*Regression, Random forest, XGBoost, Scikit-Learn

## Neural Networks

### Vehicle Proximity Warning System
This project was built to support driver recognition when a dynamic driving situation. When I participated in car racing, I realized that it is difficult for drivers to detect cars nearby, especially on high-speed roads. So, I came up with the idea that giving alerts to drivers about approaching vehicles can be helpful for safe driving. Since most modern cars are equipped with a rearview camera, this can easily be applied. By using YOLO and CNN to detect only vehicles, the display shows a warning with red color when vehicles approach nearby. By doing so, drivers can easily identify cars very close. The project can be found [here](https://github.com/KevinSBSon/Vehicle-Proximity-Warning-System).
<br>
<br>
*CNN, OpenCV, YOLO, Image Recognition, Image Processing, Tensorflow

### Weather Image Classification Using Residual Network(ResNet)
In this project, I built an image classification model to identify the weather in the picture. The data set contained 1125 images with four classes. I built ResNet 50 from scratch by using Tensorflow. In addition to building the main model, I built four different ResNet models, such as ResNet18, 34, 50, and 101, and compared their performances with plain deep Neural Network models to see the problem of vanishing gradients.The project can be found [here](https://github.com/KevinSBSon/ResNet_ImageClassification).
<br>
<br>
*Image Classification, Tensorflow, Neural Network, Residual Network

## AI Algorithms

### Travelling Salesman Problem(TSP) Solver Using Search Algorithms in AI
This project was to build algorithms to create the efficient path that a salesman would take while traveling between cities. The solution to any given TSP would be the shortest way to visit a finite number of cities, visiting each city only once and then returning to the starting point. More information about the problem is available on Wikipedia. Our team took two approaches, the first one was ‘Branch and Bound Depth First Search Algorithm’ to find the optimal solution, and the other one was ’Stochastic Local Search Algorithm’ to improve the performance of our problem solver. The project can be found [here](https://github.com/KevinSBSon/Travelling-Salesman-Problem-Solver-Using-Search-Algorithms-in-AI).
<br>
<br>
*Artificial Intelligence, Branch and Bound Algorithm, Stochastic Local Search Algorithm
