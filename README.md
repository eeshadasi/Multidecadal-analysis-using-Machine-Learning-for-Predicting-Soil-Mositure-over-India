# Multidecadal Analysis using Machine Learning for Predicting Soil Moisture over India

## Project Overview
This project, in collaboration with ISRO, focuses on predicting soil moisture across different regions of India using multidecadal data. The project leverages machine learning models to analyze historical soil moisture trends and generate future predictions.

## Dataset
- **Source**: 30 years of soil moisture data stored in `.mat` files.
- **Regions Covered**: Various climatic zones across India.
- **Preprocessing**: Data extracted, cleaned, and transformed into a structured format suitable for machine learning models.

## Methodology
1. **Data Preprocessing**
   - Data extraction from `.mat` files.
   - Handling missing values and outliers.
   - Feature engineering to enhance predictive performance.
2. **Model Development**
   - Implemented **RNN-GRU** networks for time-series forecasting.
   - Compared performance with traditional ML models (Random Forest, SVR, etc.).
   - Evaluated models using RMSE, MAE, and R² scores.
3. **Visualization & Analysis**
   - Temporal trends of soil moisture variations.
   - Regional differences and long-term patterns.

## Implementation
### Dependencies
Ensure you have the required Python libraries installed:
```bash
pip install numpy pandas scipy scikit-learn tensorflow keras matplotlib h5py
```

### Running the Model
```python
from model import train_model
train_model()
```

### Evaluating the Model
```python
from model import evaluate_model
evaluate_model()
```

### Prediction
```python
from inference import predict_soil_moisture
prediction = predict_soil_moisture(sample_input)
print(prediction)
```

## Results
- Improved soil moisture prediction accuracy over baseline models.
- Insights into long-term climate impacts on soil moisture trends.

## Future Scope
- Integration with satellite data for enhanced predictions.
- Expansion to global soil moisture analysis.
- Deployment of a web-based visualization tool.

## Authors
- **Divya**

## References
- Research papers and datasets used in this project.
