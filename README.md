# CPI-Forecasting
Forecasting Future Consumer Price Index (CPI) Using Machine Learning
The project aims to leverage the power of machine learning to develop a robust and accurate model for forecasting future Consumer Price Index (CPI). The Consumer Price Index is a crucial economic indicator that measures the average change over time in the prices paid by urban consumers for a market basket of consumer goods and services. Accurate CPI forecasts are essential for policymakers, economists, businesses, and individuals to make informed decisions regarding inflation, budgeting, investment, and financial planning.
The project utilizes the Long Short-Term Memory (LSTM) neural network architecture to forecast Consumer Price Index (CPI) values for the period between April and November 2023. The LSTM model is a type of recurrent neural network (RNN) that is particularly effective in capturing long-term dependencies and patterns in sequential data.

To train the LSTM model, historical CPI data from 2013 to April 2023 is used. This dataset includes CPI values for various time intervals, such as monthly or quarterly, along with relevant economic and financial indicators. The data is preprocessed to ensure consistency and quality, and any missing values or outliers are appropriately handled.

The LSTM model is then trained using the preprocessed dataset, where it learns the underlying patterns and relationships between past CPI values and the corresponding economic factors. The model considers the temporal aspect of the data and takes into account the dependencies and trends observed over time.

During the training process, the LSTM model adjusts its internal parameters based on the observed patterns and errors, optimizing its ability to capture and forecast CPI values accurately

Once the LSTM model is trained and validated, it is deployed to forecast CPI values for the period between April and November 2023. By inputting the available data up until April 2023, the model generates predictions for the upcoming months. These forecasts provide valuable insights into the expected inflation trends and can assist policymakers, businesses, and individuals in making informed decisions related to budgeting, investment, pricing strategies, and financial planning during that time period.

It is important to note that while the LSTM model has been trained on historical data and performs well during evaluation, the accuracy of the forecasts is subject to uncertainty and external factors that may impact CPI values in the future. Regular monitoring and updating of the model with the latest data are essential to maintain its forecasting performance over time.

Further, To complement the forecasting project, a dashboard and storytelling feature will be created using Tableau. The Tableau platform allows for the interactive visualization and presentation of data, enabling users to explore and understand the forecasted Consumer Price Index (CPI) values effectively.

The Tableau dashboard will serve as a centralized hub to present key insights and trends derived from the CPI forecast. It will consist of various visualizations and interactive elements designed to provide a comprehensive view of the projected CPI values for the period between April and November 2023.

The dashboard may include the following components:

Forecasted CPI Trends: Line charts or area graphs depicting the forecasted CPI values over time. This visualization will enable users to observe the projected inflation trends and identify any notable patterns or fluctuations.

Comparison with Historical Data: A side-by-side comparison of the forecasted CPI values with the actual historical CPI data. This visualization will help users assess the accuracy of the forecasting model and understand the deviations between the projected and observed values.
