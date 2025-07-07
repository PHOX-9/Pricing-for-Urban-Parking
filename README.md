#🚗 Dynamic Pricing for Urban Parking Lots

##🧠 Project Overview
This project simulates a real-world pricing engine for 14 urban parking lots using real-time data. The objective is to improve parking lot utilization by dynamically adjusting prices based on real-time demand indicators such as occupancy, queue length, traffic conditions, special events, and vehicle types.

The pricing engine is developed in three stages:

🔹 Model 1: Baseline Linear Model
A simple linear pricing formula based on occupancy rate.

🔹 Model 2: Demand-Based Model
A more intelligent model using multiple features to compute a demand score and adjust prices accordingly.

The solution processes data in real-time using Pathway and visualizes price trends using Bokeh to ensure smooth, explainable price adjustments.

##🧰 Tech Stack
Tool / Library	Purpose
Python	Core language for logic and modeling
Pandas	Data manipulation and preprocessing
NumPy	Numerical computations
Pathway	Real-time data stream processing and simulation
Bokeh	Interactive visualizations of pricing trends
Google Colab	Notebook-based development and execution environment
