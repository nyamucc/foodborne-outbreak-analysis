# What Makes a Foodborne Outbreak Investigation Successful? An Analysis of Investigation Methods, Timeliness, and Sampling Approaches Using CDC Data

## 📌 Project Overview

This project analyzes foodborne outbreak investigation data from the U.S. Centers for Disease Control and Prevention (CDC) to identify the factors that contribute to successful outbreak investigations — defined by identifying the pathogen (agent), contaminated food, and contributing factors.

## 🎯 Research Questions

1. Does the type of epidemiologic investigation method affect the likelihood of identifying the outbreak agent?
2. Do more environmental assessment visits improve the chances of identifying contributing factors?
3. Does collecting clinical samples increase success in identifying the outbreak agent?
4. Does faster investigation timing (e.g., quicker contact and observation) result in higher investigation success?

## 📊 Data Source

CDC Foodborne Outbreak dataset — public health data on foodborne illness investigations in the U.S.

- Source: [CDC NORS](https://www.cdc.gov/nors/data.html)
- Format: CSV
- Columns include: establishment type, sample types, investigation timelines, methods used, outcomes, etc.

## 🛠️ Tools & Technologies

- Python (Pandas, NumPy)
- Visualization (Matplotlib, Seaborn)
- Statistics (SciPy, Statsmodels)
- Vs Code

## 🗂️ Project Structure

foodborne-outbreak-analysis/
├── data/
│ ├── raw/ # Raw dataset from CDC
│ └── processed/ # Cleaned data for analysis
├── notebooks/
│ ├── 01_data_cleaning_eda.ipynb
│ ├── 02_statistical_analysis.ipynb
│ └── 03_report.ipynb # Final summary/report (optional)
├── output/
│ └── figures/ # Saved visualizations
├── requirements.txt # Python dependencies
├── .gitignore # Ignore temp files
└── README.md # Project overview

### 📒 Notebooks

- `01_data_cleaning_eda.ipynb` – Load, clean, and explore the data with visuals
- `02_statistical_analysis.ipynb` – Hypothesis testing and logistic regression
- `03_report.ipynb` – Final insights, charts, and summary of findings


---

## ▶️ How to Run This Project

1. Clone this repository:
   ```bash
   git clone https://github.com/YOUR_USERNAME/foodborne-outbreak-analysis.git
   cd foodborne-outbreak-analysis

2. Create a virtual environment 
python -m venv cenv
source cenv/bin/activate   # (for macOS/Linux)

#### or on Windows Command Prompt:
cenv\Scripts\activate.bat

3. Install dependencies:
pip install -r requirements.txt




👤 Author
Charity Nyamuchengwa
www.linkedin.com/in/charity-nyamuchengwa/ nyamucc@gmail.com /