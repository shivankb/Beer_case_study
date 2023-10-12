# Beer Rating Prediction

![bar-209148_1280](https://github.com/shivankb/beer_case_study/assets/121177364/ece090f9-ced6-4a30-8459-2582d7a7d92a)

This project is an exploration of predicting beer ratings based on various features using regression techniques, specifically RandomForest regression and XGBoost regression. The XGBoost model performed the best among the models evaluated.

# Table of Contents
    * Project Description
    * Dataset
    * Project Structure
    * Usage
    
# Project Description
In this project, the aim is to predict beer ratings by leveraging machine learning regression models. We utilized two popular regression algorithms, RandomForest regression and XGBoost regression, to predict beer ratings. The dataset contains various features related to beer and user information that can be used to make predictions. The project serves as an example of using machine learning for predictive analysis.

# Dataset
The dataset used for this project is described as follows:

    * index: An identifier for the review.
    * beer/ABV: The alcohol by volume of the beer.
    * beer/beerId: A unique ID indicating the beer reviewed.
    * beer/brewerId: A unique ID indicating the brewery.
    * beer/name: Name of the beer.
    * beer/style: Style of the beer.
    * review/appearance: Rating of the beer's appearance (1.0 to 5.0).
    * review/aroma: Rating of the beer's aroma (1.0 to 5.0).
    * review/overall: Rating of the beer overall (1.0 to 5.0).
    * review/palate: Rating of the beer's palate (1.0 to 5.0).
    * review/taste: Rating of the beer's taste (1.0 to 5.0).
    * review/text: The text of the review.
    * review/timeStruct: A dictionary specifying when the review was submitted.
    * review/timeUnix: Unix timestamp of the review submission time.
    * user/ageInSeconds: Age of the user in seconds.
    * user/birthdayRaw: Raw user birthday data.
    * user/birthdayUnix: Unix timestamp of the user's birthday.
    * user/gender: Gender of the user (if specified).
    * user/profileName: Profile name of the user.

# Project Structure
The project is structured as follows:

    * train/: Contains the dataset used for training and testing the models.
    * beer_ratin_prediction/: Colab notebook containing the code and analysis.
    * README.md: The file you are currently reading, providing an overview of the project.

# Usage
You can use the provided code and dataset to:

    * Train and evaluate regression models to predict beer ratings.
    * Modify and extend the project for your own datasets and use cases.
