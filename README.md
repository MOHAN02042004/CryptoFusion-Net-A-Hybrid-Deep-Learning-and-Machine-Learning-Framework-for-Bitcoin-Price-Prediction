# CryptoFusion-Net-A-Hybrid-Deep-Learning-and-Machine-Learning-Framework-for-Bitcoin-Price-Prediction
Built a predictive modeling framework to forecast Bitcoin closing prices using historical market data. The system integrates advanced preprocessing, exploratory analysis, and hybrid modeling for enhanced financial forecasting.

• Processed and cleaned historical Bitcoin data by handling missing values via interpolation, removing outliers with Z-score filtering, and normalizing features using MinMaxScaler.

• Performed exploratory data analysis including correlation heatmaps, pair plots, volume vs market cap scatterplots, and rolling averages to understand market behavior and guide feature selection.

• Engineered predictive features such as time-shifted closing prices and rolling means to enhance temporal awareness in modeling.

• Trained multiple models—Random Forest, XGBoost, ARIMA, and LSTM—each optimized for different aspects of temporal and non-linear patterns in the data.

• Developed a hybrid model by averaging LSTM and XGBoost outputs, improving stability and predictive performance over standalone models.

• Evaluated models using Mean Squared Error (MSE) and R² metrics, and visualized predicted vs actual price curves to validate performance.

Skills & Tools Used: Python, Pandas, NumPy, Scikit-learn, TensorFlow, Keras, XGBoost, Matplotlib, Seaborn, ARIMA, LSTM, Time-Series Forecasting, Data Cleaning, Feature Engineering, Hybrid Modeling, Financial Data Analysis

