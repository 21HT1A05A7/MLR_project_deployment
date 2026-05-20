# MLR_project_deployment
# Profit Prediction System 📈

A Machine Learning web application that predicts company profit based on business spending and location information.

---

## Overview

This project predicts profit using business-related features such as:

- Research and Development spending
- Administration costs
- Marketing spending
- State information

Users enter input values through a web interface and receive a predicted profit value instantly.

---

## Features

✅ User-friendly interface

✅ Real-time profit prediction

✅ Flask integration

✅ Bootstrap responsive design

✅ Machine Learning prediction model

✅ Simple input form

---

## Project Preview

### Home Page

![Home Page](images/home.png)

### Input Form

![Input Form](images/input_form.png)

### Prediction Result

![Prediction Result](images/result.png)

---

## Technologies Used

### Frontend
- HTML5
- CSS3
- Bootstrap

### Backend
- Python
- Flask

### Machine Learning
- Scikit-learn
- Pandas
- NumPy

---

## Input Features

| Feature | Description |
|-----------|-------------|
| R&D | Research and Development spending |
| Admin | Administration expenses |
| Marketing | Marketing expenses |
| State | Business location |

---

## Project Structure

```bash
Profit-Prediction/
│
├── app.py
├── model.pkl
├── templates/
│   └── index.html
│
├── static/
│   ├── css/
│   │   └── style.css
│   │
│   └── images/
│       ├── home.png
│       ├── input_form.png
│       └── result.png
│
├── README.md
└── requirements.txt
```

---

## How to Run

### Step 1: Clone Repository

```bash
git clone https://github.com/your-username/profit-prediction.git
```

### Step 2: Install Dependencies

```bash
pip install -r requirements.txt
```

### Step 3: Run Application

```bash
python app.py
```

### Step 4: Open Browser

```bash
http://127.0.0.1:5000/
```

---

## Workflow

1. User enters business information
2. Data is sent to Flask backend
3. Backend processes input data
4. Machine Learning model predicts profit
5. Result is displayed on screen

---

## Output Example

```text
R&D: 150000
Admin: 120000
Marketing: 300000
State: California

Predicted Profit: $192,450
```

---

## Future Improvements

- Add charts and analytics
- Add multiple ML algorithms
- Improve UI design
- Deploy on cloud services
- Add database integration
- Store prediction history

---

