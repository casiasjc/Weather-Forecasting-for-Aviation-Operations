![images](https://user-images.githubusercontent.com/122251100/233484236-c2f67625-f536-498e-915c-8104947d55b6.jpeg)

# Forecasting Weather for Deicing Operations at Dublin Airport
Aer Lingus needs to maintain flight schedules while minimizing the additional time required for deicing operations. Using historical weather data from the Irish meteorological service - Met Eireann, this project analyzes the relationship between rain and temperature to determine the likelihood of structural icing and the potential impact on deicing time. Based on the analysis, a Naive Model is recommended to create a deicing schedule that can minimize the additional time required for deicing and prevent flight delays.

### Business Understanding and Data Understanding: 
Structural icing due to inclement weather can cause significant delays in the deicing process at Dublin Airport. To create a deicing schedule that minimizes the additional time required for deicing and prevents flight delays, this project analyzes historical weather data from Met Eireann to identify patterns in the relationship between `rain`, `temperature`, and holdover times. By analyzing these variables, the project aims to provide insights that can inform data-driven decisions and improve deicing schedules.

#### Data
The dataset came from Kaggle. To download the dataset, please click [here](https://www.kaggle.com/datasets/conorrot/irish-weather-hourly-data). All data was sourced from the Irish meteorological service - [Met Eireann](https://www.met.ie/). 

### Modeling and Evaluation: 
The project evaluates the performance of several machine learning models, including Naive Model, Random Walk, Random Walk with a drift, Autoregression, Moving Average, ARMA, and Neural Prophet. The Naive Model performs the best, particularly in predicting temperature.
![download](https://user-images.githubusercontent.com/122251100/233484538-cb2451bb-d74c-43f9-880c-33510eb54d16.png)
![download (1)](https://user-images.githubusercontent.com/122251100/233484776-8b518fde-86c4-4587-9672-19e3ac509594.png)

### Conclusion: 
Based on the analysis, it is recommended that Aer Lingus be prepared for shorter holdover times during the months of October to April. Additionally, it may be worth considering additional factors beyond just temperature in determining when to deice. While the Naive Model performed well, it is important to remain flexible and adaptable to changing weather conditions.
![download (3)](https://user-images.githubusercontent.com/122251100/233485150-f60f9e54-3c8c-4fe2-baed-eb4a389119be.png)
![download (2)](https://user-images.githubusercontent.com/122251100/233485170-bc72c152-7bf3-476d-9ffe-b1f4ce0d919d.png)

### Recommendations: 
The project recommends that Aer Lingus use the Naive Model to create a deicing schedule that minimizes the additional time required for deicing and prevents flight delays. Additionally, the project suggests that other factors beyond just temperature, such as Type I deice, Type IV anti-ice, and flight scheduling, be considered in the deicing process.

### Next Steps: 
To further test the accuracy of the model, it would be beneficial to evaluate the model's performance on a holdout set of data that it has not seen before. Additionally, it may be worth exploring other machine learning algorithms and techniques to potentially improve the accuracy of the model.


# Repository Navigation:
Presentation](https://github.com/casiasjc/Weather-Forecasting-for-Aviation-Operations/blob/main/Presentation.pdf) - Google slides of presentation
[Final_Clean_Notebook](https://github.com/casiasjc/Weather-Forecasting-for-Aviation-Operations/blob/main/Final_Clean_Notebook.ipynb) - The final notebook

To reproduce the results, please follow the instructions provided in the notebook.
