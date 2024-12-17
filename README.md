# Battery Aging Analysis and Visualization 🚀
## Overview
This project provides a detailed analysis of the aging process in Li-ion batteries by visualizing critical parameters such as:

## Battery Impedance
1. Electrolyte Resistance (Re).
2. Charge Transfer Resistance (Rct)
The analysis leverages NASA's Battery Dataset, collected through charge/discharge cycles and impedance measurements, offering insights into how these parameters evolve over time.
Features

## Data Preprocessing:

- Cleans and processes raw data.
- Handles missing values using interpolation.
## Battery Impedance Calculation:
- Combines Re and Rct to compute overall battery impedance.
## Interactive Visualizations (using Plotly):
- Battery Impedance vs. Cycle
- Electrolyte Resistance (Re) vs. Cycle
- Charge Transfer Resistance (Rct) vs. Cycle
These visualizations provide insights into the aging behavior of batteries.
## Setup Instructions
1. Clone the Repository
Run the following commands in your terminal to clone the repository and navigate into the project directory:
```bash
git clone https://github.com/Pgangothri/thinklabs.git
cd thinklabs
2.Install Dependencies
Ensure you have Python 3.x installed. Then, install the required packages:
3.Prepare the Dataset
Download the NASA Battery Dataset.
Place the metadata.csv file inside a data/ folder in the project directory.
4. Run the script


