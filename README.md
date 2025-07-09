# 🚗 Real-Time Dynamic Parking Price Prediction

This project simulates **real-time pricing** for smart parking lots using streamed data. It leverages **[Pathway](https://pathway.com/)** for handling simulated data streams and applies **dynamic pricing logic** based on factors like queue length, time of day, traffic conditions, and special events.

---

## 📊 Problem Statement

Design a system that:

- Ingests real-time parking data in a streaming format  
- Processes and extracts time-aware features  
- Applies dynamic pricing logic based on real-time conditions  
- Outputs updated pricing for each parking lot  

---

## 🛠️ Tech Stack

| Tool       | Purpose                                 |
|------------|------------------------------------------|
| Python     | Core programming language                |
| Pathway    | Streaming data processing & simulation   |
| Pandas     | Data manipulation                        |
| Matplotlib | Price trend visualization                |

---

## 📁 Project Structure


---

## 📈 Features Engineered

- `timestamp`: Combined from `LastUpdatedDate` + `Time`  
- `hour_of_day`, `day_of_week`, `month`  
- `IsSpecialDay`, `TrafficConditionNearby`, `QueueLength`  

---

## 🧠 Pricing Logic Highlights

- 🕒 Higher prices during peak hours (8–10 AM, 5–7 PM)  
- 🚦 Increased price for **"Heavy"** traffic nearby  
- 🧳 Special events or holidays cause a **price surge**  
- 📉 Lower prices on weekends to **boost occupancy**

---

## 📉 Output Visualization

The notebook generates a **dynamic line plot** showing predicted price changes over time for one selected parking lot.

<p align="center">
  <img src="https://i.imgur.com/abcd123.png" alt="Pricing trend plot" width="600">
</p>

---

## ✅ Results

- Streaming behavior emulated via time delay  
- Real-time feature extraction on the fly  
- Dynamic pricing outputs stored and visualized effectively  

---

## 🚀 How to Run

1. Open `RealTimePricing.ipynb` in **Google Colab** (recommended)  
2. Upload `dataset.csv` to your Colab session  
3. Run all cells in the notebook  
4. Wait for the simulation to complete and view the output chart  

> **Note:** No API keys or external services required.

---

## 🙌 Acknowledgments

- **[Pathway](https://pathway.com/)** for enabling real-time streaming simulation  
- **OpenAI** for technical inspiration and guidance  

---
