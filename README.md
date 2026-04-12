# Loan-Bias-Detector

AI-powered system to detect and visualize bias in automated loan approval decisions.  
Built using Streamlit for the Google Solution Challenge under the **Responsible AI** theme.

---

##  Problem Statement

Automated decision systems in finance may introduce bias based on gender, income, education, or other demographic factors.  
This project detects and visualizes bias in loan approval datasets to ensure fairness.

---

##  Features

- Data Cleaning (missing values, duplicates)
- Bias Detection across categorical attributes
- Fairness Score calculation
- Interactive visualizations
- Automatic column selection
- Numeric data distribution analysis
- Streamlit dashboard UI

---

##  Tech Stack

- Python
- Streamlit
- Pandas
- NumPy
- Matplotlib

---

##  Dataset

Financial Loan Approval Dataset (from Kaggle)

---

## Installation

### 1. Clone the repository
```bash
git clone https://github.com/The-Navigators-Org/Loan-Bias-Detector.git
```

### 2. Navigate to project directory
```bash
cd Loan-Bias-Detector
```

### 3. Install dependencies
```bash
pip install -r requirements.txt
```

### 4. Run the application
```bash
streamlit run app.py
```

---

##  Project Structure

```text
Loan-Bias-Detector/
├── app.py                
├── Loan Dataset.csv      
├── requirements.txt      
└── README.md
```

---

##  How It Works

1. Load dataset  
2. Clean missing values  
3. Detect categorical columns  
4. Generate bias comparison  
5. Calculate fairness score  
6. Visualize numeric distributions  

---

##  Fairness Score Formula

```
Fairness = 1 - (max approval rate - min approval rate)
```

Higher score indicates **lower bias**.

---

##  Google Solution Challenge Theme

**Responsible AI** — Ensuring fairness and detecting bias in automated decision systems.

---

##  Authors

- Anant Rajput  
- Tanish Gupta  
- Pushkar Mishra
- Tanishka Yadav

---

##  License

This project is for educational and research purposes.
