# What Makes a Foodborne Outbreak Investigation Successful? An Analysis of Investigation Methods, Timeliness, and Sampling Approaches Using CDC Data

## 📌 Project Overview

This project analyzes foodborne outbreak investigation data from the U.S. Centers for Disease Control and Prevention (CDC) to identify the factors that contribute to successful outbreak investigations — defined by identifying the pathogen (agent), contaminated food, and contributing factors.

## 🎯 Research Questions

1. How quickly are foodborne outbreaks typically identified, and what factors influence the timing of identification?
2. How do environmental health assessment visits contribute to the effectiveness of outbreak investigations?
3.Do operational delays differ by establishment type (e.g., restaurants vs. institutions) or menu type (complicated vs. limited)?
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
- `02_statistical_analysis.ipynb` – correlation tests and group comparisons
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
