# Future Electricity Consumption Prediction
This project explores future electricity consumption trends in the U.S., addressing concerns like overexploitation and air pollution. The focus is on the American Electric Power company, covering the East U.S., employing data cleaning and feature engineering steps. Through exploratory data analysis and time series analysis, various forecasting models are applied, with Seasonal and Holt’s damped models showing optimal performance. The study predicts 2022 energy usage using ARIMA, highlighting winter peaks and the impact of temperature on consumption.

## Data Cleaning and Feature Engineering

![alt text](https://github.com/imkir0513/future_electricity_consumption_prediction/blob/master/images/data_cleaning_feature_engineering.png)

The data cleaning and feature engineering phase involved meticulous steps to enhance the dataset's quality and depth. The process included the deletion of extraneous variables and a thorough check for missing data. Unusual years, specifically 2012 and 2022, were excluded to ensure data integrity. Furthermore, the reformatting of DateTime variables was conducted to streamline the dataset, and crucial features, such as hour, holidays, and weekdays, were extracted, providing a more nuanced and enriched dataset for subsequent analysis.

## Analytics Techniques

![alt text](https://github.com/imkir0513/future_electricity_consumption_prediction/blob/master/images/analytical_techniques.png)

The analytical techniques employed in the project comprised two main components: exploratory data analysis (EDA) and time series analysis with a focus on predicting future electricity consumption based on historical trends. We utilized a range of simple forecasting models, including the Average_model, Naive model, Seasonal model, and Drift model. Additionally, they explored more advanced exponential smoothing models such as SES (Simple Exponential Smoothing), Holt’s model, and Holt’s damped model. The analysis also incorporated the ETS (Error, Trend, Seasonality) model and ARIMA (AutoRegressive Integrated Moving Average) to discern and predict patterns in the time series data, offering a comprehensive approach to understanding and forecasting electricity consumption.

## EDA

![alt text](https://github.com/imkir0513/future_electricity_consumption_prediction/blob/master/images/eda.png)

During the exploratory data analysis (EDA) phase, we considered multiple criteria to understand energy consumption patterns. We evaluated consumption based on specific factors such as hour, weekdays, holidays, season, day, and month. Notably, hourly consumption revealed lower energy usage between 7 am to 8 pm. Seasonal analysis indicated variations in consumption during summer and winter. Additionally, weekdays, particularly Tuesday, Wednesday, and Thursday, exhibited distinct consumption patterns. We also observed that non-holidays generally had higher consumption compared to holiday periods, providing valuable insights into the nuanced factors influencing electricity usage.

## Process and Results

![alt text](https://github.com/imkir0513/future_electricity_consumption_prediction/blob/master/images/process_and_results.png)

The process involved the application of various forecasting models to predict future electricity consumption. Among the simple forecasting models, the Seasonal model demonstrated the best performance, while in the category of exponential smoothing models, Holt’s damped model yielded optimal results. We also employed the ETS model, allowing it to autonomously select the best model based on AICc (Akaike Information Criterion with correction). For ARIMA modeling, a comprehensive approach was taken, including checking data stationarity and utilizing auto.arima to select the most suitable model based on AICc. The evaluation of different models was conducted by comparing their Root Mean Square Error (RMSE), providing a quantitative basis for assessing their forecasting accuracy.

## Conclusion

![alt text](https://github.com/imkir0513/future_electricity_consumption_prediction/blob/master/images/conclusion.png)

In conclusion, the Arima model emerged as the most effective in predicting 2022 energy usage, exhibiting the smallest Root Mean Square Error (RMSE) at 515513.3. This model was subsequently employed to forecast electricity consumption for the next 12 months of 2022. Noteworthy trends were identified, indicating that average electricity consumption peaks during winter months, specifically in December, January, and February. The analysis also highlighted the specific impact of temperature on electricity consumption. Moreover, the findings revealed lower electricity consumption during holidays and weekends compared to weekdays, providing valuable insights into consumption patterns based on temporal factors.

## Recommendation 

![alt text](https://github.com/imkir0513/future_electricity_consumption_prediction/blob/master/images/recommendation.png)

The recommendations for future steps involve expanding the scope of the study both temporally and geographically. Firstly, the suggestion is to extract data for additional years, providing a more comprehensive dataset for analysis. Geographically, the proposal is to broaden the study area from 13 eastern states to encompass the entire United States, offering a more inclusive perspective on electricity consumption trends. Additionally, the team advocates considering the impact of significant financial periods, specifically referencing 2007 and 2008. On the energy company front, collaboration with the government is advised to implement incentives, establish power consumption policies, regulate electricity consumption scope, and offer subsidies to residents meeting specified standards. Furthermore, cooperation with manufacturers of energy-saving products is recommended to promote and provide benefits for energy-efficient practices.

<br><br>
For more details please go to [Report](https://drive.google.com/file/d/1WDD44K2_g2_DSsd-xDUcCRhRSTaxlIEE/view?usp=sharing) ; [PowerPoint](https://drive.google.com/file/d/1mPR0WUUOsWAbQH8YkCUmjbgVQ4prc76a/view?usp=sharing)

