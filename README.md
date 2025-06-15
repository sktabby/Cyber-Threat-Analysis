# 🚨 Cybersecurity: Suspicious Web Threat Interactions

Detect and analyze suspicious web traffic patterns using AWS CloudWatch data and machine learning. This project focuses on identifying potential cybersecurity threats through anomaly detection, classification models, and insightful visualizations.

---

## 📁 Project Structure

```
Cyber-Threat-Analysis/
├── data/
│   └── CloudWatch_Traffic_Web_Attack.csv       # Raw dataset
├── images/                                     # Visualization exports
│   ├── 1.jpg – EDA visualizations
│   ├── 2.jpg – Model performance charts
│   ├── 3.jpg – Network graphs
│   ├── 4.jpg – Correlation matrices
│   ├── 5.jpg – Traffic over time
│   └── 6.jpg – Anomaly detection results
├── model/
│   ├── network_intrusion_model.h5              # CNN-based model
│   ├── neural_network_model.h5                 # Fully connected NN
│   └── random_forest_model.pkl                 # Random Forest model
├── results/
│   └── analyzed_data.csv                       # Cleaned and labeled data
├── requirements.txt                            # Python dependencies
└── Cyber_Threat_Analysis.ipynb                 # Main Jupyter notebook
```

---

## 🔍 Key Features

* **📊 Exploratory Data Analysis**
  Understand web traffic trends and threat distribution patterns.

* **🧠 Machine Learning Models**

  * Random Forest Classifier
  * Neural Networks (including CNN)
  * Isolation Forest for anomaly detection

* **📈 Visualizations**

  * Country-wise threat maps
  * Traffic pattern heatmaps
  * Network interaction graphs
  * Time-series traffic analysis

---

## ⚙️ Installation

```bash
git clone https://github.com/sktabby/Cyber-Threat-Analysis.git
cd Cyber-Threat-Analysis
pip install -r requirements.txt
```

---

## 🚀 Usage

1. Open and run the `Cyber_Threat_Analysis.ipynb` notebook.
2. The notebook includes:

   * Data loading and preprocessing
   * Exploratory analysis and feature engineering
   * Model training and evaluation
   * Generation of visual reports

---

## 🧪 Results

* **Achieved 100% accuracy** on the provided dataset
  *(Note: This might indicate data leakage—further validation on a more diverse dataset is recommended)*

* **Key Observations**:

  * High `bytes_in` with low `bytes_out` may signal infiltration attempts.
  * Specific country codes consistently flagged as sources of suspicious traffic.
  * Non-standard ports are commonly used in unauthorized access attempts.

---

## 🖼️ Sample Visualizations

![Model accuracy-loss](https://github.com/user-attachments/assets/ccfcde1d-789e-4bca-868c-e96937568dc4)

---

## 🤝 Contributing

Contributions are welcome!
Please fork the repository, make your improvements, and submit a pull request.

---

## 📜 License

This project is licensed under the [MIT License](LICENSE).

---
