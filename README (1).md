
# ⚡ Smart Energy Monitoring System (Colab Project)

This project simulates and visualizes current usage data in real-time using Python, with the goal of promoting energy efficiency. It is based on a smart energy system concept and built to run in Google Colab.

## 🛑 Problem Statement

**Background:**  
As energy consumption continues to rise globally due to urbanization and the proliferation of electronic devices, many users remain unaware of their real-time energy usage. This lack of visibility results in inefficient energy use, higher electricity bills, and unnecessary strain on power infrastructure.

**Problem:**  
There is a significant gap in accessible, real-time tools for individuals and small institutions to monitor, predict, and manage energy usage effectively. Traditional monitoring systems are often hardware-intensive or expensive. Users need a lightweight, software-based solution to simulate, track, and analyze energy consumption without requiring physical sensors.

**Goal:**  
To design and develop a Python-based smart energy monitoring system that:
- Simulates current usage data
- Detects and alerts high energy usage
- Logs readings to CSV for analysis
- Visualizes usage patterns using plots
- Optionally uploads data to Google Sheets
- Trains a machine learning model to predict usage trends

**Outcome:**  
A fully functional, cloud-ready prototype using Google Colab that empowers users to monitor and understand their energy usage patterns—paving the way for smarter, more efficient energy consumption habits.

## 📌 Features

- Simulates energy consumption data
- Flags high current readings with alerts
- Saves logs to CSV (`energy_data_log.csv`)
- Visualizes current usage using `matplotlib`
- Optional: Uploads data to Google Sheets
- Optional: Trains a machine learning model to predict current based on time

## 📁 Files Included

- `smart_energy_colab.ipynb` - Main notebook with simulation, logging, and plotting
- `requirements.txt` - Dependencies list
- `sample_energy_data_log.csv` - Sample dataset (you can upload your own)
- `train_energy_model_colab.ipynb` - Optional ML model training notebook (if used)

## 🛠 Requirements

```
pandas
matplotlib
scikit-learn
gspread
gspread_dataframe
```

> Note: Use `gspread` packages only if uploading to Google Sheets from Colab.

## 🚀 How to Use (In Google Colab)

1. Open the notebook in [Google Colab](https://colab.research.google.com/)
2. Run each cell step-by-step
3. Upload the sample or your own energy data CSV
4. View simulation, alerts, and plots in real time

## 📈 Optional: Train ML Model

Use the `train_energy_model_colab.ipynb` notebook to:
- Load energy data
- Train a Random Forest Regressor
- Visualize predictions vs actual readings

## 📄 License

MIT License – free to use and modify.

---

Made with ❤️ for Smart System Innovation Projects.
