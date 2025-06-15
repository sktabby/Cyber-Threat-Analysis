# Cyber-Threat-Analysis - README
# Cybersecurity: Suspicious Web Threat Interactions

## Project Overview
This project focuses on detecting and analyzing suspicious web traffic patterns to identify potential cybersecurity threats. Using machine learning techniques, we analyze AWS CloudWatch web traffic data to classify normal vs. suspicious activities and visualize threat patterns.

## Project Structure

UML_CYBER_THREAT_ANALYSIS/
├── data/
│   └── CloudWatch_Traffic_Web_Attack.csv       # Raw dataset
├── images/                                     # Visualization exports
│   ├── 1.jpg                                  # EDA visualizations
│   ├── 2.jpg                                  # Model performance charts
│   ├── 3.jpg                                  # Network graphs
│   ├── 4.jpg                                  # Correlation matrices
│   ├── 5.jpg                                  # Traffic over time
│   └── 6.jpg                                  # Anomaly detection results
├── model/
│   ├── network_intrusion_model.h5             # Neural network model
│   ├── neural_network_model.h5                # Alternative NN model
│   └── random_forest_model.pkl                # Random Forest model
├── results/
│   └── analyzed_data.csv                      # Processed/analyzed data
├── requirements.txt                           # Python dependencies
└── UML_Cyber_Threat_Analysis.ipynb           # Main Jupyter notebook


## Key Features
- *Data Analysis*: Exploratory analysis of web traffic patterns
- *Anomaly Detection*: Identification of suspicious activities using Isolation Forest
- *Machine Learning Models*:
  - Random Forest Classifier
  - Neural Networks (including CNN architecture)
- *Visualizations*:
  - Network interaction graphs
  - Traffic pattern heatmaps
  - Time-series analysis
  - Country-based threat distribution

## Installation
1. Clone this repository:
   bash
   git clone https://github.com/yourusername/cybersecurity-web-threat-detection.git
   
2. Install requirements:
   bash
   pip install -r requirements.txt
   

## Usage
1. Run the Jupyter notebook UML_Cyber_Threat_Analysis.ipynb
2. The notebook includes:
   - Data loading and preprocessing
   - Exploratory data analysis
   - Feature engineering
   - Model training and evaluation
   - Visualization generation

## Results
Our models achieved 100% accuracy in classifying suspicious web traffic (note: this may indicate data leakage in the sample dataset - further validation needed with larger, more diverse datasets).

Key findings:
- High bytes_in with low bytes_out often indicates infiltration attempts
- Specific country codes showed higher frequency of suspicious activities
- Non-standard ports were frequently associated with unauthorized access attempts

## Visualizations
![Network Traffic Analysis](images/3.jpg)
![Threat Classification](images/6.jpg)
![Traffic Patterns](images/5.jpg)

## Contributing
Contributions are welcome! Please fork the repository and create a pull request with your improvements.

## License
This project is licensed under the MIT License.
