# Cryptocurrency Price Prediction

This project predicts the future prices of three major cryptocurrencies (Bitcoin, Ethereum, Ripple) for specific dates based on historical data using machine learning. It includes a user-friendly GUI to make predictions.

---

## Features
- Fetch historical data from Yahoo Finance.
- Perform feature engineering and preprocess the data.
- Train machine learning models (Random Forest, LSTM, etc.).
- Use a GUI to predict future cryptocurrency prices for user-selected dates.

---

## Technologies Used
- Python
- Libraries: `yfinance`, `pandas`, `numpy`, `scikit-learn`, `tkinter`
- Machine Learning Models: Random Forest, LSTM

---

## File Structure
### **1. `/data/`**
- Contains the raw and processed datasets for cryptocurrencies.

### **2. `/models/`**
- Contains the trained machine learning model saved as a `.pkl` file.

### **3. `/scripts/`**
- **`data_preprocessing.py`**: Code for data cleaning, missing value handling, feature engineering, and splitting datasets.
- **`model_training.py`**: Code for training the machine learning model and saving it.
- **`gui_application.py`**: Code for the GUI application to predict cryptocurrency prices.

### **4. `requirements.txt`**
- A list of Python libraries required to run the project.

### **5. `README.md`**
- Provides an overview of the project, usage instructions, and file structure.

---

## How to Use

### Step 1: Clone the Repository
```bash
git clone https://github.com/your-username/CryptoPricePrediction.git
cd CryptoPricePrediction
