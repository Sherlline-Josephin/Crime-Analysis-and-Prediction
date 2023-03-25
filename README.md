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

![image](https://user-images.githubusercontent.com/109158067/227698078-a396e90f-d699-4b28-ae88-53351cff4765.png)
![image](https://user-images.githubusercontent.com/109158067/227698100-87633211-6e74-4d18-a5d0-919a0f670802.png)
![image](https://user-images.githubusercontent.com/109158067/227698109-911f6fb5-b07c-4f2b-8669-652b832765fc.png)
![image](https://user-images.githubusercontent.com/109158067/227698118-e808c298-ccd7-42b0-94d6-ad23d0737513.png)
![image](https://user-images.githubusercontent.com/109158067/227698130-16c4c0e2-09b8-4ac6-976b-d0bc549fb08b.png)
![image](https://user-images.githubusercontent.com/109158067/227698138-4bf39983-9998-442c-b531-7b95fd5ccb82.png)


