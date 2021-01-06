# Stock price prediction

The model was trained by using a Decision tree regressor. This was the optimal choice based on an extensive grid search performed on different types of regression models. The testing was done using cross validation and performance of trained model was determined in terms of **MAPE (Mean Absolute Percentage Error)**.

The final trained model for the given a dataset with a **MAPE of 0.8** was saved using pickle library. 

There are 3 different files ipynb files and 1 pkl file: 
1. `training.ipynb` : For training and testing model 
2. `ml-model-testing` : For testing model 
3. `runmodel` : Model is loaded and predictions are made
4. `trainedmodel.pkl` : Save file 

