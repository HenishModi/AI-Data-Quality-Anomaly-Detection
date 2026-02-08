# AI Data Quality & Anomaly Detection

This project detects **data quality issues and anomalies** in financial datasets using Python. It flags unusual or suspicious values, helping analysts and risk teams maintain **clean and reliable data**.

---

## 🛠 Technologies Used

- Python  
- Pandas  
- NumPy  
- Jupyter Notebook  

---

## 📁 Repository Structure

- `AI_Data_Quality_Anomaly_Detection.ipynb` – Main Jupyter notebook demonstrating the anomaly detection workflow  
- `advanced_financial_dataset.csv` – Sample dataset used in the notebook  
- `ai_data_quality_output.csv` – Output file with flagged anomalies  
- `requirements.txt` – Python dependencies for easy setup  

---

## ⚡ Setup & Installation

1. **Clone the repository**

```bash
git clone https://github.com/HenishModi/AI-Data-Quality-Anomaly-Detection.git
cd AI-Data-Quality-Anomaly-Detection
```

2. **Create a virtual environment** (optional but recommended)

```bash
python -m venv venv
# Activate the environment
# Linux/Mac
source venv/bin/activate
# Windows
venv\Scripts\activate
```

3. **Install dependencies**

```bash
pip install -r requirements.txt
```

---

## 📄 Usage

1. Open the notebook:

```bash
jupyter notebook AI_Data_Quality_Anomaly_Detection.ipynb
```

2. Run all cells to:

- Load the dataset  
- Detect anomalies  
- Export results to `ai_data_quality_output.csv`

---

## 📝 Requirements.txt

Minimum dependencies:

```text
pandas>=1.5.0
numpy>=1.22.0
jupyter>=1.0.0
```

Optional libraries for advanced features:

```text
matplotlib>=3.5.0
seaborn>=0.12.0
scikit-learn>=1.1.0
pyod>=1.0.8
```

---

## 🎯 Benefits

- Detects **suspicious or erroneous data entries** before they affect reporting  
- Provides **explainable outputs** suitable for audits and compliance  
- Easily extendable to **ML‑based anomaly detection** or **interactive dashboards**  

---

## 🚀 Future Enhancements

- Cloud integration (Azure/AWS) for automated pipelines  
- Interactive dashboards using Power BI or Plotly  
- Advanced ML models for anomaly detection (Isolation Forest, Autoencoders, etc.)

- 👤 Author

Henish Modi
Data Analyst | AI & Data Quality Enthusiast

