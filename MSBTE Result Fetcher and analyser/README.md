# MSBTE Result Automation & Analytics 📊

Capstone Project – Web Application for Institute Result Management

A powerful automation platform that makes it easy for institutes to handle MSBTE semester results. 

Core Workflow:
- User uploads a CSV file containing student enrollment numbers.
- The system automatically fetches results from the official MSBTE website using browser automation.
- Extracts detailed result data (semester-wise marks, subjects, grades, etc.).
- Generates enriched CSV files for further analysis and ML predictions.

## ✨ Key Features

### 🔄 Automation
- Batch Processing via CSV — Upload enrollment list → Automatic fetching from MSBTE portal
- Headless browser automation (no manual intervention)
- Detailed data extraction from result pages/PDFs
- Auto-generation of structured CSV output
- Individual result lookup + PDF download
- Real-time job progress tracking

### 🤖 ML-Powered Intelligence
- Semester percentage prediction
- KT/ATKT Risk Prediction (using Gradient Boosting)
- Class-wide at-risk student ranking
- Weak subject detection via z-score analysis

### 📈 Analytics Dashboard
- Pass vs KT trends
- Grade distribution & top performers
- Subject difficulty ranking
- Cohort progression
- Statistical anomaly detection
- Seasonal performance comparison

## 🛠️ Tech Stack
- Backend: Python (Flask/FastAPI)
- Automation: Selenium (headless browser)
- Data Handling: Pandas, NumPy
- Machine Learning: scikit-learn (Gradient Boosting, etc.)
- Visualization: Plotly, Matplotlib
- Frontend: HTML, CSS, JavaScript (responsive UI)

## 🚀 How It Works

1. Upload CSV with student enrollment numbers
2. System processes the list and starts automated fetching from MSBTE website
3. Extracts marks, grades, and other details
4. Generates enriched CSV files ready for analysis
5. Use the dashboard for insights, predictions, and visualizations
