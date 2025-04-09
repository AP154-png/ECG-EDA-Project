# 🫀 ECG EDA Project - MIT-BIH Arrhythmia Dataset

This project presents an **Exploratory Data Analysis (EDA)** of ECG signals using the MIT-BIH Arrhythmia dataset from Kaggle. The aim is to analyze the structure and characteristics of heartbeat signals recorded via **electrocardiogram (ECG)** and identify patterns across different types of heartbeats — without applying any machine learning models.

---

## Dataset Info

- **Source**: [MIT-BIH ECG Dataset on Kaggle](https://www.kaggle.com/datasets/shayanfazeli/heartbeat)
- **Files Used**:  
  - `mitbih_train.csv`  
  - `mitbih_test.csv`
- **Data Format**:
  - Each row contains 187 ECG time-series points + 1 class label
  - Labels represent different heartbeat types (Normal, Abnormal, etc.)

---

## Key Analysis Performed

- Plotting sample ECG signals by class
- Class distribution visualization
- Mean and standard deviation plots for each heartbeat type
- Signal heatmaps to visualize intensity variations
- t-SNE clustering for signal similarity exploration (no ML used!)

---

## Classes

| Label | Description                                |
|-------|--------------------------------------------|
| 0     | Normal beat                                |
| 1     | Supraventricular premature beat            |
| 2     | Premature ventricular contraction          |
| 3     | Fusion of ventricular and normal beat      |
| 4     | Unclassifiable beat                        |

---

## Bonus Visualizations

- ✅ ECG Heatmaps for class-level signal intensity
- ✅ Signal amplitude boxplots
- ✅ t-SNE projection for signal clustering
- ✅ Class-wise standard deviation analysis

These visualizations enhance understanding of signal structure, variability, and separability across different heartbeat types — which is critical in medical signal processing.

---

## Tools Used

- Python 
- Google Colab 
- Pandas, NumPy
- Matplotlib, Seaborn
- scikit-learn (for t-SNE only)

---

## Run It Yourself

You can open and run the notebook in Google Colab using the link below:

👉 [**Open in Google Colab**](https://colab.research.google.com/drive/1BrpjS48V9UXZvU-ZX15KCDVY94kVZgPv?usp=sharing#scrollTo=fwL1mypDdIQI)

---

## Author

**Aparna**  
Final Year B.Tech CSE - Healthcare Informatics  
VIT Bhopal  
