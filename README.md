

# **Financial Time Series Forecasting and Technical Analysis Using Corrector LSTM and Hybrid Deep Learning-Based Model**

## **Overview**
This research paper implements a novel approach to financial time series forecasting and technical analysis, leveraging the Corrector Long Short-Term Memory (cLSTM) model integrated with hybrid deep learning architectures. By combining advanced techniques such as cLSTM, ANN, RNN, and Stacked/Bi-directional LSTM, this study aims to improve predictive accuracy and address the limitations of traditional forecasting methods.

The dataset is sourced from the National Stock Exchange (NSE) of India, focusing on Tata Consultancy Services (TCS). The model's performance is evaluated using metrics like **R² score**, **MAE**, and **RMSE**.

---

## **Key Features**
- **Corrector LSTM (cLSTM)**: Enhances traditional LSTM models by integrating a data-correction mechanism based on SARIMA.
- **Hybrid Deep Learning Architecture**: Combines multiple neural network approaches for robust forecasting.
- **Hyperparameter Tuning**: Optimizes the model's learning process to improve accuracy and efficiency.
- **Technical Analysis Integration**: Includes statistical and machine learning-based indicators for forecasting.
- **Performance Evaluation**: Assesses model predictions using R², MAE, and RMSE metrics.

---

## **Dataset**
- **Source**: National Stock Exchange (NSE) of India.
- **Focus**: TCS stock prices.
- **Features**:
  - `Date`: Date of the stock data.
  - `Open`: Opening stock price.
  - `High`: Highest stock price of the day.
  - `Low`: Lowest stock price of the day.
  - `Close`: Closing stock price.
  - `Volume`: Number of shares traded.

---

## **Installation & Usage**

1. Clone this repository:
   ```bash
   git clone https://github.com/ankit485803/CorrectorLSTM_FinEco_Paper.git
   
   cd CorrectorLSTM_FinEco_Paper

2. **Technologies Used:** 
* Programming Language: Python
* Libraries:
    - TensorFlow/Keras
    - Statsmodels (SARIMA implementation)
    - NumPy, Pandas, Scikit-learn
    - Matplotlib, Seaborn

3. IDE: Google Colab Notebook (CPU, GPU, TPU -- cloud services) & Jupiter Notebook for training model



---

## Sample
![Model Architecture](https://github.com/ankit485803/CorrectorLSTM_FinEco_Paper/blob/main/Model/Bi_Directional_LSTM/OnEntireData_usingBiDirectionalLSTM.png) 



## Future Work
- Extend the model to multi-stock datasets for broader applicability.
- Incorporate additional external factors like market news or sentiment analysis.
- Deploy the model using a web-based interface for real-time forecasting.



## Contributing
- Contributions are welcome! Please fork this repository and submit a pull request with your improvements.
- **Contact Us**:  ankit127iitp@gmail.com




---

<!-- Authors -->


## Copyright and License 

* Hari K Chaudhary - Associate Prof, Indian Institute of Information Technology Guwahati, Assam, India
* Ankit Kumar - Student, Indian Institute of Technology Patna, India
* João Mendes Moreira - Professor, University of Porto, Portugal
