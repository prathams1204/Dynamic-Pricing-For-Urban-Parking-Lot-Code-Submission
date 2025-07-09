
# Dynamic Pricing for Urban Parking Lots

## Problem Statement
Implement dynamic pricing models for 14 urban parking lots using real-time data streams.

## Implemented Models
1. Baseline Linear Model (Model 1): Price increases linearly with occupancy rate.
2. Demand-Based Model (Model 2): Uses occupancy, queue length, traffic, special day, and vehicle type to calculate demand and adjust price.

## Tech Stack Used
- Python
- Pandas, Numpy
- Pathway (streaming data pipeline)
- Bokeh, Panel (visualisation)

## How to Run
1. Upload `dataset.csv` to Colab.
2. Install dependencies:
```
pip install pathway bokeh panel
```
3. Run the notebook cells sequentially.

## Architecture Flow

1. Data Ingestion: Read dataset.csv using pandas
2. Preprocessing: Combine date & time, create features (vehicle_type, queue length, traffic, special_day)
3. Streaming Pipeline: Simulate real-time data using Pathway
4. Pricing Models: Apply Baseline Linear and Demand-Based models
5. Visualisation: Plot price variations using Bokeh in Panel dashboard

## Architecture Diagram (ASCII)

[Dataset CSV]
      |
      v
[Pandas Preprocessing]
      |
      v
[Pathway Streaming Pipeline]
      |
      v
[Pricing Models 1 & 2]
      |
      v
[Bokeh Visualisation]

---

© Summer Analytics 2025 - Final Submission
