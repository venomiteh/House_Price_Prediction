# 🏠 USA Housing Price Prediction (PyTorch)

A simple linear regression model built with **PyTorch** to predict housing prices using the **USA Housing Dataset**. The project covers data preprocessing, model training, evaluation, and saving the model for future use.

---

## 📌 Project Overview

- **Dataset**: USA Housing Dataset (CSV)
- **Goal**: Predict housing prices based on features like number of bedrooms, bathrooms, square footage, etc.
- **Model**: Linear Regression using PyTorch
- **Preprocessing**:
  - Dropped irrelevant columns (`street`, `city`, `date`, etc.)
  - Removed rows with missing values
  - Normalized input and output using `StandardScaler`
- **Evaluation**: Mean Squared Error on test data
- **Persistence**: Trained model and scalers saved with `torch.save` and `joblib`

---

## 📂 Project Structure

├── USA_Housing_Predictor.py # Main Python script ├── USA Housing Dataset.csv # Dataset file ├── linear_regression_model.pth # Saved PyTorch model ├── scaler_X.pkl # Scaler for features ├── scaler_y.pkl # Scaler for target ├── README.md # Project documentation


---

## 🔧 Tech Stack

- Python
- PyTorch
- NumPy
- Pandas
- scikit-learn
- joblib

---

## 🚀 How It Works

1. Load and clean the dataset.
2. Drop non-numeric or irrelevant columns.
3. Handle missing values.
4. Normalize features and labels.
5. Split the data into training and testing sets.
6. Build a linear regression model using PyTorch.
7. Train and evaluate the model.
8. Save the trained model and scalers.

---

## 📊 Sample Output

Epoch 50/100, Loss: 0.0283 Epoch 100/100, Loss: 0.0127 Test Loss (Normalized): 0.0154

Actual: $643,200.00 - Predicted: $658,412.75 Actual: $512,600.00 - Predicted: $499,804.31 Actual: $803,400.00 - Predicted: $792,110.67



---

## 🔮 Future Enhancements

- Switch to a deep neural network for better accuracy
- Integrate advanced optimizers like Adam or RMSprop
- Build a front-end interface using Streamlit or Flask
- Deploy model as an API

---

## 🧪 Installation

Clone the repository and install the required libraries:

```bash
pip install torch pandas numpy scikit-learn joblib

📝 License
This project is licensed under the MIT License.

##🤝 Contributing
Pull requests are welcome! For major changes, please open an issue first to discuss what you'd like to change.


