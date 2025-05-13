# chatbudget
**ChatBudget** is a simple web app that helps people understand their spending and plan their budget. You can upload a CSV of your past transactions, and the app will analyze your spending to tell you how much to budget for things like groceries, rent, transportation, and other necessities.

I built this project to improve my skills in Python, data analysis, and web development while creating a helpful tool for managing personal finances.

---
## 🔧 What It Can Do

- Upload a CSV file with your transaction history
- Analyze your spending for each month
- Calculate how much to budget for **necessities** (groceries, rent, transport, etc.)
- Show personalized budget advice based on your past spending

---
## 🧰 Tools I Used

- **Backend:** Python, Flask  
- **Data Handling:** pandas (for data analysis)  
- **Frontend:** Basic HTML (for file upload and output display)  
- **Optional:** Matplotlib or Plotly (for visualizations)

---
## 📁 Sample CSV Format

The app expects your transaction data to be in a CSV file with the following columns:
Date,Description,Amount
2024-01-01,Groceries,50
2024-01-02,Transport,20
2024-01-03,Coffee,5

---
## ▶️ How to Run ChatBudget Locally

You can run ChatBudget on your computer by following these steps:

### 1. Download the Project
- Go to the GitHub page (this repo).
- Click the green **“Code”** button → **Download ZIP**.
- Unzip the downloaded file.

### 2. Install Python
Make sure Python is installed. If not, download it from:  
👉 [https://www.python.org/downloads/](https://www.python.org/downloads/)

### 3. Install Required Libraries
Open your terminal (or command prompt), go to the project folder, and run:

```bash
pip install -r requirements.txt
```

This will install everything the app needs (like Flask, Pandas, etc.).

### 4. Start the App

Run the following command in your terminal:

```bash
python app.py
```

### 5. Open in Your Browser

Once the app starts, open your browser and go to:

```
http://127.0.0.1:5000
```

You’ll see the ChatBudget interface running on your own computer.

---

## 🙋‍♀️ Can Others Use This App?

Yes! Anyone with Python installed can download the project, install the requirements, and run the app on their own computer — just like you. No need to change the address or settings.

---
