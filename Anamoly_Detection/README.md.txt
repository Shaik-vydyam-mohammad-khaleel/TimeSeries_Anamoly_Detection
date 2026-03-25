# Time Series Anomaly Detection (IoT Sensor Data)

This project implements anomaly detection on time-series CPU utilization data using **Isolation Forest** and **Autoencoder** models.

---

## Files Included
- `anomaly_detection_final.ipynb` → Main notebook
- `ec2_cpu_utilization_5f5533.csv` → Dataset
- `combined_labels.json` → Ground truth anomaly labels
- `visualization/` → Saved visualizations

---

## Requirements

Install the required libraries:

```bash
pip install pandas numpy scikit-learn tensorflow matplotlib seaborn

## How to Run
1. Open the notebook in Jupyter Notebook or Google Colab
2. Place the following files in the same directory:
- `ec2_cpu_utilization_5f5533.csv`
- `combined_labels.json`
3. Run all cells sequentially
