# Student Exam Score Prediction

This project is a Multiple Linear Regression model that predicts student exam scores based on their study hours, sleep hours, attendance rates, and social media usage.

## 📊 Dataset Features
The model uses the following attributes from the dataset:
* **Independent Variables (Features):** Study Hours, Sleep Hours, Attendance Rate, Social Media Hours
* **Dependent Variable (Target):** Exam Score[cite: 1]

## 🛠️ Technologies & Libraries Used
* **Python 3**[cite: 1]
* **Pandas & Numpy** for data manipulation[cite: 1]
* **Scikit-Learn** for model building, data splitting, and feature scaling (`StandardScaler`)[cite: 1]
* **Matplotlib & Seaborn** for data visualization and residual analysis[cite: 1]

## 📈 Model Performance
The dataset was split into training (75%) and testing (25%) sets.[cite: 1] The performance of the Multiple Linear Regression model on the test data is as follows:
* **R² Score:** 0.915[cite: 1]
* **Mean Absolute Error (MAE):** 3.27[cite: 1]
* **Mean Squared Error (MSE):** 14.60[cite: 1]

## 🚀 How to Run
1. Clone this repository.
2. Install the required dependencies using `pip install -r requirements.txt`.
3. Open the Jupyter Notebook (`.ipynb` file) and run the cells sequentially to train and evaluate the model.[cite: 1]
