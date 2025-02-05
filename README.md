# Stock Trend Prediction Using Python, Machine Learning, Flask & LSTM

## Overview
This project predicts stock trends using LSTM (Long Short-Term Memory) neural networks. The model is built using Python and integrated into a Flask web application to provide a user-friendly interface for trend forecasting.

## Features
- **Data Collection**: Fetches stock market data.
- **Preprocessing**: Handles missing values, scales data, and formats it for LSTM input.
- **LSTM Model**: A deep learning model trained to predict stock trends.
- **Flask Web App**: A simple UI to input stock ticker symbols and visualize predictions.

## Tech Stack
- **Programming Language**: Python
- **Machine Learning Frameworks**: TensorFlow, Keras
- **Web Framework**: Flask
- **Data Processing**: Pandas, NumPy
- **Visualization**: Matplotlib, Plotly

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/Neuro-kiran/Stock-Trend-Prediction-Using-Python-Machine-Learning-Flask-LSTM.git
   ```
2. Navigate to the project directory:
   ```bash
   cd Stock-Trend-Prediction-Using-Python-Machine-Learning-Flask-LSTM
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage
1. Run the Flask application:
   ```bash
   python app.py
   ```
2. Open a web browser and go to:
   ```
   http://127.0.0.1:5000/
   ```
3. Enter a stock ticker and view predictions.

## Folder Structure
```
📂 Stock-Trend-Prediction-Using-Python-Machine-Learning-Flask-LSTM
 ├── 📁 static          # Contains CSS, JS, and images
 ├── 📁 templates       # HTML templates for Flask app
 ├── 📁 models          # Trained LSTM models
 ├── 📄 app.py          # Flask application
 ├── 📄 train.py        # LSTM training script
 ├── 📄 requirements.txt # Project dependencies
 ├── 📄 README.md       # Project documentation
```

## Results
- The model provides real-time stock price predictions based on historical data.
- Visualized stock trends using interactive graphs.

## Future Improvements
- Improve model accuracy with advanced hyperparameter tuning.
- Add more stock market indicators as features.
- Deploy the app using cloud services.

## Contributing
Feel free to fork the repository and submit pull requests. Suggestions and contributions are always welcome!

## License
This project is licensed under the MIT License.

---
### Author
👤 **Kiran Marne**  
[LinkedIn](https://www.linkedin.com/in/kiran-marne-42436620a/) | [GitHub](https://github.com/Neuro-kiran)
