🚗 Real-Time Dynamic Parking Price Prediction
This project simulates real-time pricing for smart parking lots using streamed data. It uses Pathway to handle simulated data streaming and applies pricing logic based on queue length, time features, and external factors like traffic and special events.

<br/>
📊 Problem Statement
Design a system that:

Ingests real-time parking data in streaming format

Processes and extracts time-aware features

Applies dynamic pricing logic based on real-time conditions

Outputs updated pricing for each parking lot

<br/>
🛠️ Tech Stack
Tool	Purpose
Python	Core programming language
Pathway	Streaming data processing & simulation
Pandas	Data manipulation
Matplotlib	Price trend visualization

<br/>
📁 Project Structure
pgsql
Copy
Edit
📦 smart-parking-price-prediction
 ┣ 📄 dataset.csv               ← Input dataset
 ┣ 📄 RealTimePricing.ipynb     ← Google Colab notebook with full project
 ┣ 📄 README.md                 ← Project description (this file)
<br/>
📈 Features Engineered
timestamp: combined from LastUpdatedDate + Time

hour_of_day, day_of_week, month, etc.

IsSpecialDay, TrafficConditionNearby, QueueLength

<br/>
🧠 Pricing Logic Highlights
🕒 Higher prices during peak hours (8–10 AM, 5–7 PM)

🚦 Increased price for "Heavy" traffic nearby

🧳 Special events or holidays cause a price surge

📉 Lower prices on weekends to boost occupancy

<br/>
📉 Output Visualization
The notebook generates a dynamic line plot showing price predictions over time for one parking lot.

<p align="center"> <img src="https://i.imgur.com/abcd123.png" alt="Pricing trend plot" width="600"> </p> <br/>
✅ Results
The simulation emulates streaming behavior using time delay

Real-time features are extracted on the fly

Dynamic pricing output is stored and visualized

<br/>
🚀 How to Run
Recommended: Run the notebook in Google Colab

Upload dataset.csv to your Colab session

Run all cells in RealTimePricing.ipynb

Wait for simulation to complete and view output chart

No API keys or external dependencies required

<br/>
🙌 Acknowledgments
Pathway for streaming data simulation

OpenAI for technical guidance# SA_CapstoneProject
