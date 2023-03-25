## Crime-analysis-and-Prediction
An analysis of crimes against women in India from 2001 to 2012 is taken and visualized. Then the crime rate is predicted until 2022 by using ARIMA and SARIMA models.Then the result of these two models are compared and the model that gives better prediction is considered the best.

## Functional Requirements
- Data collection
- Data processing
- Training and Testing
- Modeling
- Predicting

## SYSTEM COMPONENTS(MODULES)
### Import Libraries 
In this module, different libraries like pandas, NumPy, matplotlib, and statsmodels are imported, which are useful for data processing,visualization, accuracy, and prediction.

### Data Processing
In this module, the data undergoes pre-processing like cleaning the dataset and removing null and unwanted values.

### Visualization
- Initially, the data undergoes visualization for the crime given by the user.
- Next for the entered year, visualization is done for all the crime counts for all the states in India.
- Next the crime rate is compared for the years 2001 and 2012 (i.e for the initial and final data in the data set).
- Then the graph is plotted against the crime count district-wise for the entered state.

### Built ARIMA model
- An autoregressive integrated moving average model, a statistical 
  analysis model that uses time series data to better understand the 
  data set or predict future trends.
- Here the values in the data set range from 2001 to 2012.
- Here the data is fed from 2013 to 2022 manually.
- Then the model is built and the graph is displayed.

### Built SARIMA model
- A seasonal autoregressive integrated moving average model which is like ARIMA but more powerful.
- We can use statsmodels implementation of SARIMA.
- Then the model is built and the graph is displayed using a seasonal pattern.

### Streamlit
- Here Streamlit is used as GUI.
- The user can select a particular state and crime and the graphs of  ARIMA and SARIMA models are displayed with their predicted values


## Screenshots

![image](https://user-images.githubusercontent.com/109158067/227698171-dba3684a-b452-4782-aa34-58e0f47bac2e.png)
![image](https://user-images.githubusercontent.com/109158067/227698190-bd5068a3-1c5e-40bb-a6c8-77c2a74d8e71.png)
![image](https://user-images.githubusercontent.com/109158067/227698203-87d061d1-33c1-4fb1-91c5-b43dd3e6b876.png)
![image](https://user-images.githubusercontent.com/109158067/227698221-fe28cb16-52fb-45ba-9826-5309e95881de.png)
![image](https://user-images.githubusercontent.com/109158067/227698226-280b900d-37c8-4a91-ae12-4a26f65cba9f.png)
![image](https://user-images.githubusercontent.com/109158067/227698236-a210e3de-20d7-4c23-a27a-dcb94260cf17.png)



