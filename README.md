# Helath_Analysis

Project Title:
Predicting Stress Levels using Linear Regression

Problem Statement:
Predict the stress levels of individuals based on various independent variables.

Introduction:
In this project, we aim to predict stress levels in individuals using a linear regression approach. We will utilize a dataset containing several independent variables, including sleep duration, quality of sleep, physical activity level, heart rate, and daily steps, among others. Our goal is to establish a reliable predictive model that can help assess the impact of these factors on an individual's stress level.

Dataset:
The dataset consists of the following columns:

'Person ID'
'Gender'
'Age'
'Occupation'
'Sleep Duration'
'Quality of Sleep'
'Physical Activity Level'
'Stress Level'
'BMI Category'
'Blood Pressure'
'Heart Rate'
'Daily Steps'
'Sleep Disorder'
Tools and Statistical Methods:
Programming Language: Python
Environment: Google Colab
Libraries: NumPy, Matplotlib, Seaborn, Pandas, Statsmodels, Scikit-Learn

Data Exploration and Insights:

In this section, we explore the dataset and gain insights into the data's characteristics.

Data Overview: We begin by loading the dataset and examining its structure, including the column names and types.

Descriptive Statistics: We calculate summary statistics, such as mean, minimum, maximum, and standard deviation, for the dataset's numeric variables. This provides an initial understanding of the data distribution.

![Screenshot 2023-10-03 at 11 52 44 AM](https://github.com/Shalin96/Helath_Analysis/assets/139086441/775274e3-0637-490c-be1a-9da58d81306e)

Based on our data analysis, it is evident that the standard deviation of the sleep duration variable is 0.80. This relatively low standard deviation indicates that individual data points tend to be closely clustered around the mean value. This characteristic suggests that the dataset exhibits a structured and consistent pattern, which bodes well for the accuracy and reliability of our prediction model. The reduced variability within the data enhances the model's potential to make precise predictions based on the relationships we uncover

Correlation Analysis: We perform correlation analysis to assess the relationships between variables. This includes calculating correlation coefficients to quantify the strength and direction of relationships. For example, we discovered a strong negative correlation between sleep duration and stress levels.

![Screenshot 2023-10-03 at 12 01 40 PM](https://github.com/Shalin96/Helath_Analysis/assets/139086441/cb13fa94-9463-4567-8459-945af79a417b)

Furthermore, our analysis reveals several other noteworthy correlations within the dataset. Notably, there exists a negative correlation between physical activity, age, and quality of sleep. In these cases, as one variable increases, the other tends to decrease. Conversely, we observe a positive correlation between daily steps and certain variables. This positive relationship aligns with our intuition, suggesting that as daily steps increase, certain factors within the dataset also tend to increase. These findings contribute to our understanding of the complex interactions between the variables under consideration.

Data Visualization: We create visualizations to better understand the data relationships. For instance, a scatterplot is used to illustrate the negative linear relationship between sleep duration and stress levels.

![Screenshot 2023-10-03 at 11 58 50 AM](https://github.com/Shalin96/Helath_Analysis/assets/139086441/c2a59ac1-a40b-4e81-8f38-05b43bc808fa)

Linear Regression Modeling:

We employ linear regression, a statistical technique that models the relationship between the dependent variable (stress level) and independent variables (e.g., sleep duration). Here's a summary of this phase:

Data Split:

The dataset is split into training and testing sets, with 80% used for training the model and 20% for testing.
Linear Regression Equation: We derive a linear regression equation that relates stress level to sleep duration:


Stress Level = (-1.82) * Sleep Duration + 18.40


This equation quantifies how stress levels change with variations in sleep duration.

The coefficient for Sleep Duration (-1.8271) represents how much Stress Level is expected to change for each additional hour of Sleep Duration. In this case, as Sleep Duration increases by one hour, Stress Level is predicted to decrease by approximately 1.8271 units.
The intercept (constant) term (18.4088) is the predicted Stress Level when Sleep Duration is zero. However, this value may not have a meaningful interpretation in practice since Sleep Duration is unlikely to be zero for individuals.

Model Evaluation: We assess the model's performance using statistical metrics such as R-squared. In our case, the model explains approximately 66.4% of the variance in stress levels based on sleep duration.

![Screenshot 2023-10-03 at 12 15 42 PM](https://github.com/Shalin96/Helath_Analysis/assets/139086441/47517caf-38ed-40d4-b449-22888945117c)

Visualization: Visual representations, such as regression plots, help illustrate the linear relationship between sleep duration and stress levels.

Conclusion:

In conclusion, our linear regression model successfully predicts stress levels based on sleep duration, with an accuracy of 63%. This model can be used as a tool for assessing stress factors and making informed recommendations to individuals to manage their stress levels effectively.

Future Work:

Future work may involve expanding the model to consider other independent variables and exploring more complex regression techniques. Additionally, data collection efforts could be extended to enhance the predictive capabilities of the model.


This refined project presentation provides a clear structure and narrative flow, making it more professional and understandable to both technical and non-technical audiences. Feel free to incorporate these improvements into your project.
















