# Coursera_Capstone
Data Science Coursera Capstone

Intro/Business Problem

My problem is to determine the accident severity based on different variables in the dataset such as the location, type of road, junction type, weather, and vehicle conditions. 
Specifically, the question I will be investigating is how to classify a new record in the data set as 1 or 2 in severity code based on the above mentioned variables?
This problem will use machine learning techniques such as classification as well as Python and libraries to achieve the above analysis.
The audience of the analysis and evaluation is traffic police of different regions and how they can avoid future accidents. Moreover, it can be used as a part of marketing campaign to make everyone aware of the conditions that lead to a more severe, fatal accident and key steps on avoiding it.
They would care about the problem because it really helps to reduce fatalities overall and help increase awareness by using data science methods to clean and reveal hidden insights from the data.

Data
I will be using the offered metadata on accidents and severity in this course to execute my idea. It is widely available on the Canadian government website and can also be found from Week 1 link in the course.
In order to execute my problem, I will (1) clean the data to remove excess columns, replace NaN data values, or clear empty columns. Then, I will (2) ensure all data types of each data is correct and (3) create multiple regression to see which variables most impact the accidence severity code and then finally use (4) KNN or Decision Tree or Logistic Regression to classify new conditions as either 1 or 2 in severity code.
As an example, ROADCOND is likely to be important. When road conditions are wet, the risk of accident increases to 2. So I will analyze it as a part of classification process while also doing accuracy evaluations depending on the machine learning technique deployed. If it is a decision tree, I will compute entropy and gain to get the best ordering of different variables in classification and finally use Jaccard or confusion matrix to provide accuracy metrics.
