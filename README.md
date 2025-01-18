# Air Quality Analysis and Prediction

This project focuses on analyzing and predicting air quality using machine learning techniques. Leveraging a detailed dataset containing air pollutant concentrations, temperature, and humidity readings, the project builds and evaluates predictive models, including LSTM and RNN architectures, to forecast air quality metrics.

## Dataset
The project utilizes the **Air Quality UCI Dataset**, which contains 9,357 rows and 15 columns. Key attributes include:

- **Date and Time**: Timestamps of measurements.
- **Gas Concentrations**: CO, NMHC, NOx, NO2, and others.
- **Sensor Outputs**: Measurements from various air quality sensors.
- **Environmental Parameters**: Temperature (T), Relative Humidity (RH), and Absolute Humidity (AH).

The dataset provides a comprehensive view of air quality indicators over time.

## Project Features
1. **Data Preprocessing**:
   - Handling missing values and outliers.
   - Normalizing data for model readiness.
   - Feature engineering to enhance model performance.

2. **Machine Learning Models**:
   - Implementation of **Long Short-Term Memory (LSTM)** and **Recurrent Neural Networks (RNN)** for time-series forecasting.
   - Use of Keras to design and train deep learning models.

3. **Evaluation Metrics**:
   - RMSE, MAE, and R² scores to assess model performance.
   - Comparison of results between LSTM and RNN approaches.

## Repository Contents
- **Dataset**: Includes the processed Air Quality UCI dataset.
- **Notebook**: Step-by-step analysis and modeling in `amritdev_project3.ipynb`.
- **Models**: Pre-trained LSTM and RNN models provided in `.h5` and `.keras` formats.

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/air-quality-analysis.git
   ```
2. Install the required Python libraries:
   ```bash
   pip install -r requirements.txt
   ```
3. Open the Jupyter notebook to explore data preprocessing and modeling:
   ```bash
   jupyter notebook amritdev_project3.ipynb
   ```
4. Use the pre-trained models for predictions or train new models using the provided notebook.

## Applications
This project can be utilized for:
- Real-time air quality monitoring.
- Policy-making to improve environmental health.
- Research on the impact of pollutants on urban areas.

## Future Work
- Integration with real-time air quality sensors.
- Deployment of the models in a web application.
- Exploration of other deep learning architectures for improved accuracy.

## License
This project is licensed under the MIT License. See the LICENSE file for details.
