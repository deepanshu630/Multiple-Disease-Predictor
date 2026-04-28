# Multiple Disease Prediction Web App

## Overview

The **Multiple Disease Prediction Web App** is a machine learning-based application that predicts the likelihood of various diseases based on user input data. It provides an easy-to-use interface where users can input health parameters and receive predictions in real time.

---

## Features

* Predicts multiple diseases using trained machine learning models
* User-friendly web interface
* Real-time prediction results
* Supports multiple input parameters for better accuracy
* Scalable and modular design

---

## Tech Stack

* **Programming Language:** Python
* **Frontend:** HTML, CSS
* **Backend:** Streamlit / Flask
* **Libraries & Frameworks:**

  * Scikit-learn
  * Pandas, NumPy
  * Pickle (for model serialization)

---

## Project Structure

```id="6s8n3q"
Multiple-Disease-Prediction-Webapp/
│── dataset/              # Dataset files
│── models/               # Trained ML models
│── app.py                # Main application file
│── requirements.txt      # Dependencies
│── README.md             # Documentation
```

---

## Installation

### 1. Clone the repository

```bash id="4wljmz"
git clone https://github.com/sohammanjrekar/Multiple-Disease-Prediction-Webapp.git
cd Multiple-Disease-Prediction-Webapp
```

### 2. Create virtual environment (optional)

```bash id="n1b4r3"
python -m venv venv
source venv/bin/activate   # On Windows: venv\Scripts\activate
```

### 3. Install dependencies

```bash id="5d5v64"
pip install -r requirements.txt
```

---

## Usage

Run the application:

```bash id="y4gmno"
python app.py
```

* Open the web interface in your browser
* Enter required medical parameters
* Click on the predict button
* View the prediction results

---

## Supported Diseases

* Diabetes
* Heart Disease
* Parkinson’s Disease
  *(Can be extended to more diseases)*

---

## How It Works

1. User inputs health-related data
2. Data is preprocessed and fed into trained ML models
3. Model predicts the likelihood of a disease
4. Results are displayed on the web interface

---

## Future Improvements

* Add more disease prediction models
* Improve model accuracy with larger datasets
* Deploy the app on cloud platforms
* Enhance UI/UX for better usability

