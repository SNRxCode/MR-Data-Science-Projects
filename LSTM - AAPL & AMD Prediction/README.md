# LSTM - AAPL & AMD Stock Predicition (1980 - 2019)

![AAPL & AMD](https://github.com/user-attachments/assets/4081ebda-de3e-4138-964f-dfbc7ae98869)
### Description
This repository features a data science project aimed at forecasting the stock prices of Apple Inc. (AAPL) and Advanced Micro Devices, Inc. (AMD) by utilizing Long Short-Term Memory (LSTM) networks. The initiative covers historical stock data from 1980 to 2019 and utilizes deep learning methods to predict future stock prices.

### Details for each column in the dataset
| Variable        | Description                                                |
|-----------------|------------------------------------------------------------|
| Date            | The date of trading                                        |
| Close           | The price at which the stock closed on that day            |

## Conclusion
| ![image](https://github.com/user-attachments/assets/fd183de9-524a-4131-9785-9936a064f2b9) | ![image](https://github.com/user-attachments/assets/3f7ce921-286b-46c1-a582-0bc3c57bcc3d) |
|-                                                                                          |-                                                                                          |
| The LSTM model's prediction for AAPL (Apple Inc.) has an RMSE of 5.9859 and an MAE of 5.0600. RMSE measures the average magnitude of error, taking into account both variance and bias in the model's predictions. An RMSE of 5.9859 indicates that the model's predictions differ from actual values by an average of 5.986 units, which might be considerable depending on the range of AAPL's stock prices. The MAE of 5.0600, which measures the average absolute difference between projected and actual values, suggests a somewhat significant prediction error, suggesting that the model may struggle to capture the intricate patterns in AAPL's stock price fluctuations. | AMD's (Advanced Micro Devices, Inc.) Simple LSTM model has an RMSE of 0.0277 and an MAE of 0.0171. These error metrics are significantly lower than those for the AAPL prediction, indicating that the model performs better with AMD stock data. The low RMSE of 0.0277 implies that the predictions are extremely close to the actual values, with little variance on average. Similarly, the MAE of 0.0171 indicates a high level of accuracy because the average error between predicted and actual values is very tiny. This could mean that AMD's stock prices follow more predictable patterns, or that the model is better matched to AMD's data features. |
