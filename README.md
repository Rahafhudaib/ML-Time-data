# Freight Rate Prediction

## Overview
This repository contains the solution for the Freight Rate Prediction challenge. The approach focuses on building a robust baseline using `LightGBM` optimized for Mean Absolute Error (MAE) to handle extreme outliers.

## Validation Strategy
A strict time-based split was used to simulate a real-world production environment:
- **Train:** January to August 2025
- **Validation:** September to October 2025

## Instructions to Run
1. Install dependencies: `pip install -r requirements.txt`
2. Run the provided Jupyter Notebook sequentially to reproduce EDA, model training, and generate the predictions.