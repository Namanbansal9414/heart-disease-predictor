# Heart Disease Predictor 🫀

A machine learning-powered web application that predicts the risk of heart disease based on various medical parameters. Built with Streamlit and Logistic Regression.

## 🌟 Features

- **Interactive Web Interface**: User-friendly Streamlit interface for easy data input
- **Real-time Predictions**: Instant risk assessment based on medical parameters
- **Machine Learning Model**: Trained Logistic Regression classifier
- **Standardized Input**: Automatic feature scaling for accurate predictions
- **Clear Results**: Visual feedback with risk classification

## 🚀 Demo

The application analyzes the following health parameters:
- Age
- Sex
- Chest Pain Type
- Resting Blood Pressure
- Cholesterol Level
- Fasting Blood Sugar
- Resting ECG Results
- Maximum Heart Rate
- Exercise-Induced Angina
- Oldpeak (ST Depression)
- ST Slope

## 📋 Prerequisites

- Python 3.7+
- pip package manager

## 🔧 Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/Namanbansal9414/heart-disease-predictor.git
   cd heart-disease-predictor
   ```

2. **Install required packages**
   ```bash
   pip install -r requirements.txt
   ```

3. **Ensure model files are present**
   - `logreg_heart.pkl` - Trained logistic regression model
   - `scaler.pkl` - Feature scaler
   - `columns.pkl` - Expected column names

## 📦 Requirements

Create a `requirements.txt` file with:
```
streamlit
pandas
joblib
scikit-learn
```

## 🎯 Usage

1. **Run the Streamlit app**
   ```bash
   streamlit run app.py
   ```

2. **Open your browser**
   - The app will automatically open at `http://localhost:8501`

3. **Enter patient information**
   - Fill in all the medical parameters using the interactive widgets
   - Click the "Predict" button

4. **View results**
   - ✅ Green message: Low Risk of Heart Disease
   - ⚠️ Red message: High Risk of Heart Disease

## 🧠 Model Information

- **Algorithm**: Logistic Regression
- **Training Data**: Heart disease dataset with multiple clinical features
- **Preprocessing**: StandardScaler for feature normalization
- **Output**: Binary classification (High Risk / Low Risk)

## 📊 Input Features

| Feature | Type | Description |
|---------|------|-------------|
| Age | Numeric | Patient's age (18-100) |
| Sex | Categorical | M (Male) or F (Female) |
| Chest Pain Type | Categorical | ATA, NAP, TA, or ASY |
| Resting BP | Numeric | Resting blood pressure (mm Hg) |
| Cholesterol | Numeric | Serum cholesterol (mg/dL) |
| Fasting BS | Binary | Fasting blood sugar > 120 mg/dL |
| Resting ECG | Categorical | Normal, ST, or LVH |
| Max HR | Numeric | Maximum heart rate achieved |
| Exercise Angina | Binary | Y (Yes) or N (No) |
| Oldpeak | Numeric | ST depression (0.0-6.0) |
| ST Slope | Categorical | Up, Flat, or Down |

## 🏗️ Project Structure

```
heart-disease-predictor/
│
├── app.py                  # Main Streamlit application
├── Heartdisease.ipynb      # Model training notebook
├── logreg_heart.pkl        # Trained model
├── scaler.pkl              # Feature scaler
├── columns.pkl             # Column names
├── heart.csv               # Dataset
├── requirements.txt        # Python dependencies
└── README.md              # Project documentation
```

## ⚠️ Disclaimer

**This application is for educational and informational purposes only.**

- This tool is NOT a substitute for professional medical advice, diagnosis, or treatment
- Always consult with a qualified healthcare provider for medical concerns
- The predictions are based on machine learning models and may not be 100% accurate
- Do not make medical decisions based solely on this application's output

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 👤 Author

**Naman**
* B.Tech Computer Science Student
* Python & Machine Learning Enthusiast
- GitHub: [@Namanbansal9414](https://github.com/Namanbansal9414)
- LinkedIn: [@Namanbansal9509](https://www.linkedin.com/in/namanbansal9509/)

## 🙏 Acknowledgments

- Heart disease dataset providers
- Streamlit for the amazing framework
- scikit-learn for machine learning tools

## 📧 Contact

For questions or feedback, please open an issue on GitHub and direct DM on LinkedIn.

---
