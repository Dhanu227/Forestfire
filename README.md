# Forest Fire Prediction 🔥🌲

This project is designed to predict the likelihood of forest fires in Algeria using machine learning. It includes data analysis, model training, and a Flask-based web app to deploy the model.

---

## 📁 Project Structure

```
Forestfire-main/
│
├── application.py               # Flask web application
├── requirements.txt             # Python dependencies
├── models/
│   ├── ridge.pkl                # Trained Ridge Regression model
│   └── scaler.pkl               # StandardScaler object
├── notebooks/
│   ├── EDA ON DATASET.ipynb     # Exploratory Data Analysis
│   ├── Model Training.ipynb     # Model training and evaluation
│   └── Algerian_forest_fires_dataset_UPDATE.csv  # Dataset
├── templates/
│   ├── index.html               # Home page
│   └── home.html                # Result page
├── .ebextensions/
│   └── python.config            # AWS Elastic Beanstalk config
└── README.md                    # Project description
```

---

## 🚀 Getting Started

### 1. Clone the repo

```bash
git clone https://github.com/yourusername/Forestfire.git
cd Forestfire
```

### 2. Create a virtual environment

```bash
python -m venv venv
source venv/bin/activate  # or venv\Scripts\activate on Windows
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Run the Flask app

```bash
python application.py
```

Then open your browser and go to `http://127.0.0.1:5000/`.

---

## 📊 Dataset

- **Name**: Algerian Forest Fires Dataset
- **Source**: Provided in `notebooks/Algerian_forest_fires_dataset_UPDATE.csv`
- The dataset contains meteorological data and fire occurrence records used to train the model.

---

## 🧠 Machine Learning

- Model used: Ridge Regression
- Preprocessing: StandardScaler
- Evaluation and training are done in the Jupyter notebooks under `notebooks/`

---

## 🌐 Web Application

Built using Flask, the app takes environmental conditions as input and predicts the probability of a fire.

---

## ☁️ Deployment

The project includes `.ebextensions/python.config` to support AWS Elastic Beanstalk deployment.

---

## 📌 Future Improvements

- Add more robust models (e.g., Random Forest, XGBoost)
- Improve UI/UX
- Incorporate real-time weather APIs

---

## ⭐️ Show Your Support

Give a ⭐️ if you like this project!

