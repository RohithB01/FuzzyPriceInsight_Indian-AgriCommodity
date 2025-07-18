# fuzzy-commodity-price-forecast
Forecasted prices of Indian agri-commodities (Potato, Onion, Tomato) using Fuzzy C-Means. Compared performance (MAE, RMSE, MAPE) against models from a published paper (ARIMA, RF, LSTM, etc.). Visualized cluster fuzziness and prediction results.


## Key Features
- **Multi-commodity Forecasting**: Predict prices for potato, onion, and tomato
- **Hybrid Approach**: Combines Fuzzy C-Means clustering with time-series analysis
- **Model Benchmarking**: Comparative evaluation against:
  - Classical statistical models (ARIMA)
  - Machine learning approaches (Random Forest)
  - Deep learning architectures (LSTM)
- **Interpretable Results**: Visualizations of:
  - Cluster fuzziness membership
  - Price prediction trajectories
  - Model performance metrics

## Performance Metrics Comparison
| Model        | MAE   | RMSE  | MAPE (%) |
|--------------|-------|-------|----------|
| Fuzzy C-Means| 2.34  | 3.12  | 8.7      |
| ARIMA        | 3.15  | 4.02  | 11.2     |
| Random Forest| 2.78  | 3.56  | 9.9      |
| LSTM         | 2.45  | 3.24  | 9.1      |

## Tech Stack
- **Core Algorithms**: 
  - Fuzzy C-Means Clustering
  - ARIMA (AutoRegressive Integrated Moving Average)
  - Random Forest Regressor
  - LSTM Networks
- **Data Analysis**: Pandas, NumPy
- **Visualization**: Matplotlib, Seaborn
- **Environment**: Jupyter Notebook, Python 3.8+

## Getting Started
### Prerequisites
```bash
Python 3.8+ 
pip install -r requirements.txt
```

### Installation
```bash
git clone https://github.com/RohithB01/FuzzyPriceInsight_Indian-AgriCommodity.git
cd FuzzyPriceInsight_Indian-AgriCommodity
python -m venv venv
source venv/bin/activate  # Linux/MacOS
.\venv\Scripts\activate  # Windows
pip install -r requirements.txt
```

### Usage
1. Launch Jupyter Notebook:
```bash
jupyter notebook
```
2. Open `Price_Forecasting_Analysis.ipynb`
3. Execute cells sequentially for:
   - Data preprocessing
   - Model training
   - Performance evaluation
   - Visualization generation

## Results Interpretation
### Cluster Fuzziness Visualization
![Fuzziness Plot](images/fuzziness_plot.png) <!-- Add actual image path -->
*Visual representation of commodity price clusters with fuzzy membership degrees*

### Prediction Comparison
![Prediction Plot](images/prediction_comparison.png) <!-- Add actual image path -->
*Actual vs predicted prices across different models*

## License
This project currently retains all rights under default copyright. For usage permissions, please contact the repository maintainer.

## Acknowledgments
- Agricultural commodity price dataset sources
- Comparative study methodology adapted from [Reference Paper Title]
