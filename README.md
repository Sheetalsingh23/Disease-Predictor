# Disease Predictor

# Problem Statement 
Health information needs are also changing the information seeking behavior and can be 
observed around the globe. Challenges faced by many people are looking online for health 
information regarding diseases, diagnoses and different treatments. If a recommendation system 
can be made for doctors and medicine while using review mining will save a lot of time. In this 
type of system, the user face problem in understanding the heterogeneous medical vocabulary as 
the users are laymen. User is confused because a large amount of medical information on 
different mediums are available.The idea behind recommender system is to adapt to cope with the special requirements of the health domain related with users.



# Explanation of Files
## training.csv
* This is the main dataset which has been used in this project. This dataset consist of mainly two columns "Disease" and "Symptoms" but this dataset is preprocessed so it helps in easily clasifying the data. This dataset is used to train our model.

## testing.csv
* This is the dataset which has been used to test our model so that we can know the accuracy of our model. this dataset is predefined with output.


* Decision Tree 
* Random Forest
* KNearestNeighbour
* Naive Bayes
These four algorithms is used to train our model and all gives an accuracy of over 90

## Database
The database used in this project is "sqlite" whose name is database.db which consist of four tables in which we have shown the results of four different algorithms.we are saving the results of users with their names for future preferences.


## GUI.py
This is the file which is used to create the interface of our system.GUI stands for Graphical User Interface and to create it we have used Tkinter which gives a software kind of view to our project where user can directly interact with the system by entering the symptoms of dieases and he/she will get the disease through various algorithms.

## Disease-Predictor.ipynb
This is the jupyter notebook which consist of complete code. This is used to explain the working of each and every module used in the project.
 

# Working with GUI

## Step 1:
Enter the name in the provided space infront of the label as "Name of the Patient". It is the mandatory field which user have to enter in order to get result.

![Alt Text](https://github.com/pritivasekar/Disease-Predictor/blob/main/Screenshots/mainPage.JPG)

## Step 2:
Select 5 Symptoms from the dropdown menu which are labelled as Symptom 1, Symptom 2, Symptom 3, Symptom 4, Symptom 5 respectively. If user is not aware of 5 symptoms then it is mandatory for him to enter atleast 2 starting systems, otherwise the result will not come and a message box will pop up for the same

![Alt Text](https://github.com/pritivasekar/Disease-Predictor/blob/main/Screenshots/output.JPG)
## Step 3:
As per user interest,he/she can predict the disease using different algorithms such as Decision tree algorithm, Random forest algorithm, Naive bayes algorithm and K-Nearest neighbour. According to algorithm click on buttons:</br>
Press Prediction 1 for Decision tree algorithm</br>
Press Prediction 2 for Random forest algorithm</br>
Press Prediction 3 for Naive bayes algorithm</br>
Press Prediction 4 for K-Nearest neighbour</br>
(User can predict the disease using  more than one algorithm at a time)
## Step 4:
Disease Recommendation will be available infront of the  labels of algorithm of user's choice.
## Step 5:
Click on "Reset" button to predict the disease for any other patient or Press "Exit System" button to come out of the GUI.

