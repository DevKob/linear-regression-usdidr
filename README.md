# USD/IDR Exchange Rate Prediction using Linear Regression

This repository contains a Jupyter Notebook that demonstrates how to predict the USD/IDR exchange rate using Linear Regression. The project leverages historical exchange rate data and applies machine learning techniques to forecast future exchange rates.

## Overview

The project is divided into several key steps:

1. **Data Collection**: Historical USD/IDR exchange rate data from 2014 to 2024 is used. The data includes the date, open, high, low, and close exchange rates.

2. **Data Preprocessing**: The data is cleaned and preprocessed to make it suitable for machine learning. This includes converting the date format, aggregating monthly data, and preparing features for the model.

3. **Model Training**: A Linear Regression model is trained on the historical data. The model uses the year and month as features to predict the closing exchange rate.

4. **Model Evaluation**: The model's performance is evaluated using Root Mean Squared Error (RMSE) and R-squared metrics.

5. **Future Predictions**: The trained model is used to predict the USD/IDR exchange rate for the years 2025 to 2035.

6. **Visualization**: The results, including historical data and future predictions, are visualized using Matplotlib.

## Requirements

To run the Jupyter Notebook, you need the following Python libraries:

- `pyspark`
- `pandas`
- `numpy`
- `matplotlib`

You can install the required libraries using pip:

```bash
pip install pyspark pandas numpy matplotlib
```

## How to Use

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/LinearRegression_USDIDR.git
   cd LinearRegression_USDIDR
   ```

2. **Run the Jupyter Notebook**:
   ```bash
   jupyter notebook LinearRegression_USDIDR.ipynb
   ```

3. **Follow the Steps in the Notebook**:
   - The notebook is well-commented and guides you through each step of the process.
   - You can modify the code to experiment with different models or datasets.

## Key Features

- **Data Aggregation**: The data is aggregated on a monthly basis to smooth out daily fluctuations and provide a clearer trend.
- **Feature Engineering**: The model uses the year and month as features, which are derived from the date.
- **Model Evaluation**: The model's performance is evaluated using RMSE and R-squared, providing insights into its accuracy.
- **Future Predictions**: The model predicts the exchange rate for the next decade, offering valuable insights for financial planning.

## Results

The notebook includes visualizations that compare the historical exchange rates with the predicted values. These visualizations help in understanding the model's performance and the trends in the USD/IDR exchange rate.

## Contributing

If you have any suggestions or improvements, feel free to open an issue or submit a pull request. Your contributions are welcome!

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Acknowledgments

- The historical exchange rate data is sourced from a publicly available dataset.
- Special thanks to the developers of the libraries used in this project.

---

Feel free to explore the notebook and use the code to predict other financial metrics or adapt it for different datasets. Happy coding!
