# Udacity Data Scientist Nanodegree Program 
## Data Scientist Capstone Project - Sparkify
***

This repository has been created for Udacity Data Scientist Nanodegree Program Capstone Project - Sparkify

![sparkify](https://user-images.githubusercontent.com/36535914/89719293-83263b80-d9cf-11ea-9f6d-444406d9c4c5.png)


## Description
Like Spotify and fizy, Sparkify is music streaming application. Udacity provides datasets of Sparkify user log transactions. Mini dataset (128MB) and the full dataset (12GB) are also available in the Udacity workspace.

In this project, I tried to perform data cleaning, exploratory data analysis and feature engineering steps in order to build a machine learning model which will be used to predict potential users who might churn. With the help of this model, Sparkify is able identify users who are likely to cancel their membership then Sparkify can send marketing offers or campaing to prevent churn and lose customer.

The project has been conducted on the mini dataset (128MB) via Jupyter Notebook and consisted of below steps. 

- Data load & cleaning
- Churn labeling 
- Exploratory data analysis 
- Feature engineering 
- Algorithm testing and identification of best model.
- Model tuning 

## Defined Features and Models:

Churn is defined as Cancellation Confirmation events in mini_sparkify_event_data.json data. <br>

Following 9 features have been extracted to build model:

- Gender (M/F)
- Total number of songs listened
- Registration duration
- The number of thumbs up
- The number of thumbs down
- The number of add friends
- The number of add playlist
- Level (Paid/Free)
- Churn Status / Label

**Random Forest Model** performs the best on the dataset provided which provides a **F1 score of 0.949** and **Accuracy of .**

The codes can be found on the notebook in the repository **but please click here to see my Medium Post** which tells my motivation and strategiy behind the project completion.

## Next Steps

- Run the script on AWS cluster and apply analysis to the full data set
- Add more parameters and corresponding values to the hyper parameter space
- Put more effort into the feature selection process, e.g. to eliminate superfluous features

## Dependencies

In order to run the notebook flawlessly, please run: <br>

        - pip install plotly==4.9.0 
        - pip install pandas 
        - pip install numpy 
        - pip install -U scikit-learn 
        - pip install seaborn 
        - pip install matplotlib
        - pip install joblib
        - conda install -c conda-forge pyspark
        - conda install -c plotly plotly-orca==1.3.1 psutil requests #To save plotly graphs as png or jpeg. 

## Author

The repository has been created by ***Evren Ermiş*** <br>

- [Linkedin](www.linkedin.com/in/evrenermis92)
- [Github](https://github.com/eermis1)
- [Kaggle](https://www.kaggle.com/evrenermis/)
