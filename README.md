# Predicting-Budget-Earning-per-Hour-EPH-for-2024


In today's fast-paced business environment, accurate prediction of financial metrics is crucial for effective planning and decision-making. One such metric is Budget Earning per Hour (EPH), which provides valuable insights into the efficiency and profitability of operations. In this project , we delve into a data-driven project aimed at predicting EPH for the year 2024, utilizing historical data and advanced machine learning algorithms.

### Gathering and Preparing Data
To begin our project, we gathered pre-order data spanning from 2018 to 2023. This dataset included information on customers, product hierarchies, sales values, row material costs (RMC), quantities, and standard minute values (SMV). After meticulous cleaning and preprocessing, we were ready to apply our predictive algorithms.

### The Algorithmic Approach
Our predictive model consists of several stages, each tailored to forecast specific components contributing to EPH.

![image](https://github.com/SachithShilshan/Predicting-Budget-Earning-per-Hour-EPH-for-2024/assets/91172509/8fae809f-047a-40bf-a72e-2f1ff90ec372)

1. **Predicting Sales Value:** Using polynomial regression, we forecasted sales value based on customer and product hierarchy information. This step laid the foundation for estimating revenue generation.

2. **Forecasting Row Material Cost (RMC):** Employing linear regression, we predicted RMC, considering factors such as customer behavior and product attributes. This insight was essential for understanding cost dynamics.

3. **Random Forest Regression for EPH:** The core of our model involved a random forest regression approach. Here, we integrated customer data, product hierarchy, quantity, SMV, predicted sales value, and predicted RMC as independent variables. The dependent variable was EPH, the key metric guiding our financial projections.

### Model Training and Evaluation
Before predicting EPH for 2024, we trained our model using data up to 2022, excluding 2023 to simulate real-world forecasting scenarios accurately. Once trained, we applied our model to predict EPH for 2023 and compared the results against budgeted and actual figures.

### Results and Insights
Our analysis revealed promising outcomes. The predicted EPH for 2023 closely aligned with actual performance, outperforming the budgeted expectations. Visual representations, such as bar charts, illustrated this comparison vividly, showcasing the effectiveness of our predictive model.

![image](https://github.com/SachithShilshan/Predicting-Budget-Earning-per-Hour-EPH-for-2024/assets/91172509/adaf9f02-dd21-4823-8eaf-2e92727be999)

![image](https://github.com/SachithShilshan/Predicting-Budget-Earning-per-Hour-EPH-for-2024/assets/91172509/ac508343-3976-4017-a662-4198d6287425)

![image](https://github.com/SachithShilshan/Predicting-Budget-Earning-per-Hour-EPH-for-2024/assets/91172509/733997b6-028b-4ac0-9daa-486eb0fec787)

![image](https://github.com/SachithShilshan/Predicting-Budget-Earning-per-Hour-EPH-for-2024/assets/91172509/8990f471-aff6-4703-82ab-f5f272a3872a)

![image](https://github.com/SachithShilshan/Predicting-Budget-Earning-per-Hour-EPH-for-2024/assets/91172509/1c515edf-8328-4dcd-b726-3f2f7435a9ff)

![image](https://github.com/SachithShilshan/Predicting-Budget-Earning-per-Hour-EPH-for-2024/assets/91172509/0fd83486-5f74-4515-b9bd-6d7277e8c0c6)

### Conclusion
In conclusion, our data-driven approach to predicting Budget Earning per Hour for 2024 yielded actionable insights for strategic planning and resource allocation. By leveraging historical data and advanced machine learning algorithms, we achieved a high degree of accuracy in forecasting EPH, enabling stakeholders to make informed decisions and adapt to evolving market conditions effectively. As businesses continue to embrace data-driven methodologies, projects like ours demonstrate the tangible benefits of harnessing the power of data for financial forecasting and operational excellence.
