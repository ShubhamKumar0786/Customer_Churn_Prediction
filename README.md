# 🧠 Customer Churn Prediction Web App

This project is a **Customer Churn Prediction** system built using a deep learning model trained on the `Churn_Modelling.csv` dataset. The application provides a web interface using **Streamlit**, enabling users to input customer details and receive churn probability predictions.

---

## 🚀 Features

- Deep learning model built with TensorFlow/Keras
- Data preprocessing using scikit-learn (scaling, encoding)
- User-friendly web interface with Streamlit
- Real-time churn probability prediction
- Visual and interactive input for customer parameters

---

## 🧰 Tech Stack

- **Python**
- **TensorFlow / Keras**
- **Pandas / NumPy**
- **Scikit-learn**
- **Streamlit**
- **Matplotlib (for visualization, if needed)**
- **Pickle** (for model and encoder serialization)

---

## 📁 Project Structure

├── app.py # Streamlit application
------
├── model.h5 # Trained Keras model
------
├── label_encoder_gender.pkl # LabelEncoder for Gender
------
├── onehot_encoder_geo.pkl # OneHotEncoder for Geography
------
├── scaler.pkl # Scaler for feature normalization
------
├── Churn_Modelling.csv # Original dataset
------
├── requirements.txt # Python dependencies
------
├── prediction.ipynb # Model training notebook
------
├── experiments.ipynb # Experimentation and EDA
------


---

## 📝 Usage Instructions

1. **Install dependencies**

```bash
pip install -r requirements.txt
Run the Streamlit app

streamlit run app.py
Interact with the Web Interface

Choose values for customer details such as Geography, Gender, Age, etc.

Get real-time churn prediction and probability.
------------------------------------------------------------------------------------------------------------------------------------------
☁️ Deploying on Streamlit Cloud
You can easily deploy this app to Streamlit Cloud by following these steps:

Push your code to a GitHub repository.

Go to Streamlit Cloud and log in with your GitHub account.

Click on "New app" and connect your repository.

In the deployment form:

Repository: Select your GitHub repo

Branch: main or whichever branch your code is on

Main file path: app.py

Click "Deploy" and wait for it to launch.
-----------------------------------------------------------------------------------------------------------
📝 Make sure that:

All model files (model.h5, .pkl files) are in the repo.

You’ve added a requirements.txt with all the necessary packages.


--------------------------------------------------------------------------------------------------------------
📊 Input Features Used
Credit Score

Gender (Encoded)

Age

Tenure

Balance

Number of Products

Has Credit Card

Is Active Member

Estimated Salary

Geography (One-hot encoded)
------------------------------------------------------------------------------------------------------------------------
🧠 Model Overview
Trained using Keras with TensorFlow backend.

Binary classification output (Churn or Not Churn).

Model input data is scaled and encoded to match training configuration.
-------------------------------------------------------------------------------------------------------------------
📦 Dependencies
See requirements.txt:

tensorflow
pandas
numpy
scikit-learn
tensorboard
matplotlib
streamlit
scikeras

```


📬 Contact
Feel free to connect or raise an issue if you have suggestions or questions about the project
- 🌐 [GitHub Profile](https://github.com/ShubhamKumar0786https://github.com/ShubhamKumar0786)  
- 📧 Email:shubhamkashyap9501@gmail.com
- LinkedIn: [Linkedin_link](https://www.linkedin.com/in/shubham0786/)

