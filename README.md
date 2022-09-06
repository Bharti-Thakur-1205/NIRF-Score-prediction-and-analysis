# NIRF-Score-prediction-and-analysis
India has its higher educational institute ranking, called the NIRF ranking. It is an annual ranking scheme based on various parameters. So its necessary to have a check on this ranking system and have an analysis of ranks and scores given to universities and colleges.  Our objective is to develop an efficient web app for NIRF score prediction, firstly we need to know which algorithm is less prone to errors and is compatible for our system. In order to do so, we first studied different algorithms and then had a meaningful comparison among them. And once we know which one algorithm is the most suitable we go ahead to make our web app. Now after selecting the compatible algorithm, we will start building our model. Our web app predicting the NIRF scores will be using the multiple linear regression algorithm and front end isdeveloped by using streamlit library.

# NIRF Dataset Description
The dataset is downloaded from the official website of National Institute Ranking Framework(20).

The dataset contains five important factors and parameters on which NIRF ranking depends:

Teaching, Learning & Resources (TLR)
Research Productivity, Impact and IPR (RPII)
Graduation Outcome (GO)
Outreach and Inclusivity (OI)
Perception (PR)
The columns of the actual dataset are :

Institute Id
Institute Name
State
TLR_21
RPC_21
GO_21
OI_21
Perception_21
Score_21
Rank_21

And the dataset used in this model contains 200 rows.
![image](https://github.com/Aanchal0001/NIRF-Score-prediction-and-analysis/blob/main/images/dataset.png)








# Proposed approach and model
The steps of building the project involves :

Data Acquisition : This includes the collection of valid dataset.
Data Cleaning : This includes handling of missing values, erroneous data and noisy data.
Building the applicable regressor models.
Analysis of the results of different models on the basis of predicted values for testing tuples.
Building the web app using the chosen model.
Methodology for Multiple Linear Regression Model -

![image](https://github.com/Aanchal0001/NIRF-Score-prediction-and-analysis/blob/main/images/model.png)

# Methodology of WebApp -

![image](https://github.com/Aanchal0001/NIRF-Score-prediction-and-analysis/blob/main/images/webapp.png)

# How to use and install the project
1. Ensure your system has anaconda or any python environment.
2. Ensure the python environment must include required libraries - Tensorflow,Keras,Numpy,Pandas,Streamlit.
3. Download the folder- main and dataset (csv file)
4. Open the anaconda command prompt
5. Run the command to reach where app.py is located: cd <path>
6. Run the following command to run the webapp: streamlit run app.py

