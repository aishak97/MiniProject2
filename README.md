# **Business Context**

The company “Trips & Travel.Com” is planning to launch a new product, a Wellness Tourism Package. 

Wellness Tourism is defined as Travel that allows the traveler to maintain, enhance or kick-start a healthy lifestyle, and support or increase one’s sense of well-being. 

For this purpose, available data shall be used to predict the potential customer who is going to purchase the newly introduced travel package

# **Dataset**

Target: ProdTaken

4888 rows

20 columns

14 Numaric Columns

6 Categorical Columns

# **Dataset Description**

CustomerID : Unique customer ID

ProdTaken : Product taken or not (0: No, 1: Yes)

Age : Age of customer

TypeofContact : How customer was contacted (Company Invited or Self Inquiry)

CityTier : City tier depends on the development of a city, population, facilities, and living standards. The categories are ordered i.e.

DurationOfPitch : Duration of the pitch by a salesperson to the customer

Occupation : Occupation of customer

Gender : Gender of customer

NumberOfPersonVisiting : Total number of persons planning to take the trip with the customer

NumberOfFollowups : Total number of follow-ups has been done by the salesperson after the sales pitch

ProductPitched : Product pitched by the salesperson

PreferredPropertyStar : Preferred hotel property rating by customer

MaritalStatus : Marital status of customer

NumberOfTrips : Average number of trips in a year by customer

Passport : The customer has a passport or not (0: No, 1: Yes)

PitchSatisfactionScore : Sales pitch satisfaction score

OwnCar : Whether the customers own a car or not (0: No, 1: Yes)

NumberOfChildrenVisiting : Total number of children with age less than 5 planning to take the trip with the customer

Designation : Designation of the customer in the current organization

MonthlyIncome : Gross monthly income of the customer


# **Steps for the Project**

### Data Collection & Preprocessing:
Collect the customer data.

Clean and preprocess the data (handle missing values, outliers, etc.).

Ensure the dataset is tidy and ready for analysis.
### Exploratory Data Analysis (EDA):
Analyze the distribution of key features (Designation, Passport, Tier City, Marital Status, Occupation, Monthly Income, Age, and Property Preference).

Visualize relationships between features and package purchase behavior.
### Feature Selection:
Identify significant features influencing the purchase decision.

Use statistical methods or machine learning techniques for feature selection.
### Model Building:
Split the data into training and testing sets.

Build at least three machine learning models to predict the likelihood of purchasing the wellness tourism package. Examples:

Logistic Regression

Decision Trees/Random Forests

Gradient Boosting Machines (GBM)

Support Vector Machines (SVM)

Neural Networks
### Performance Metrics:
Choose appropriate metrics to evaluate model performance (e.g., Accuracy, Precision, Recall, F1-score, AUC-ROC).
### Hyperparameter Tuning:
Tune the hyperparameters of each model to improve performance.
### Model Comparison:
Compare the models based on performance metrics.

Select the best-performing model for predicting customer purchase likelihood.
### Recommendations:
Provide insights and recommendations to the policy maker and marketing team.

Identify the customer segments to target more effectively.
