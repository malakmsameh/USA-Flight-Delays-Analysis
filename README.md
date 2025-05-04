# ✈️ USA Flight Delays Analysis

This project explores flight delay and cancellation patterns in the United States using real-world aviation data. Through data cleaning, analysis, and visualization, we uncover insights into the most common causes of flight cancellations and which airlines are most affected.

---

## 📁 Datasets

The following datasets were used in the analysis:

- **`airlines.csv`** – Airline carrier codes and names.  
- **`airports.csv`** – Details about US airports.  
- **`flights.csv`** – Flight-level data, including delays, cancellations, and reasons.

---

## 🛠️ Libraries Used

- `numpy` – Numerical operations  
- `pandas` – Data manipulation and preprocessing  
- `matplotlib.pyplot` – Basic plotting  
- `seaborn` – Statistical data visualization

---

## 🧹 Data Cleaning

The dataset underwent preprocessing steps such as:

- Handling missing or null values  
- Removing irrelevant columns  
- Mapping categorical codes to human-readable labels  

These steps ensured a clean and consistent dataset for analysis.

---

## 📊 Analysis Overview

The notebook focuses primarily on flight cancellations. Key areas of analysis include:

- **Cancellation Reasons** – Exploration of the `CANCELLATION_REASON` column to quantify and visualize causes:
  - A: Airline/Carrier  
  - B: Weather  
  - C: National Air System  
  - D: Security  
- **Airline Impact** – Identification of airlines most frequently associated with each cancellation reason, especially those with high rates of airline-initiated cancellations.

---

## 🔍 Key Findings

- Weather and airline-related issues are the most common causes of flight cancellations.
- Certain carriers show significantly higher cancellation rates due to internal issues (reason A).
- Cancellations due to security concerns are rare but non-negligible.

---

## 🚀 Getting Started

To reproduce the analysis on your machine:

1. Install required libraries:
   ```bash
   pip install numpy pandas matplotlib seaborn
