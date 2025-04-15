🏠 USA Housing Price Prediction (PyTorch)
This project is a Linear Regression model built with PyTorch to predict housing prices using the USA Housing Dataset. It includes data preprocessing, model training, evaluation, and saving for later use.

📌 Project Overview
📊 Dataset: USA Housing Dataset (CSV)

🔍 Goal: Predict house prices based on features such as number of bedrooms, bathrooms, square footage, etc.

🧠 Model: Simple Linear Regression built using PyTorch

🧹 Preprocessing:

Dropped irrelevant columns (street, city, date, etc.)

Handled missing values

Feature scaling using StandardScaler

🧪 Evaluation: Mean Squared Error on test data (normalized and original scale)

💾 Saving: Trained model and scalers are saved for future use

📂 Project Structure
bash
Copy
Edit
├── USA_Housing_Predictor.ipynb / .py     # Main Python script
├── USA Housing Dataset.csv              # Dataset file
├── linear_regression_model.pth          # Trained PyTorch model
├── scaler_X.pkl                         # Scaler for input features
├── scaler_y.pkl                         # Scaler for target values
🔧 Tech Stack
Python

PyTorch

NumPy, Pandas

scikit-learn

joblib

🚀 How It Works
Load and Clean the Dataset

Drop Unnecessary Columns

Handle Missing Values

Normalize Features and Labels

Split into Train/Test Sets

Build and Train Linear Regression Model

Evaluate the Model

Save Model and Scalers

📊 Sample Output
text
Copy
Edit
Epoch 50/100, Loss: 0.0283
Epoch 100/100, Loss: 0.0127
Test Loss (Normalized): 0.0154

Actual: $643,200.00 - Predicted: $658,412.75
Actual: $512,600.00 - Predicted: $499,804.31
Actual: $803,400.00 - Predicted: $792,110.67
🧠 Future Enhancements
Add support for non-linear models or neural networks

Use advanced optimizers like Adam or RMSprop

Deploy model using Flask or FastAPI

Add GUI using Streamlit or Tkinter

📥 Installation
bash
Copy
Edit
pip install torch pandas numpy scikit-learn joblib
📝 License
This project is open-source and available under the MIT License.
