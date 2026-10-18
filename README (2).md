# County Rainfall and Planting Advisory

## Project Summary
This project analyses monthly rainfall data from five Kenyan counties using NumPy. It cleans missing Machakos rainfall readings, calculates annual totals, identifies wettest months and dry months, and recommends two-month planting windows.

## How to Run
1. Install the required library using pip install -r requirements.txt.
2. Open rainfall_analysis.ipynb in Google Colab or Jupyter Notebook.
3. Run all cells from top to bottom.
4. The notebook generates rainfall_summary.csv.

## Planting Advisory
- Nairobi: Use the calculated two-month planting window with the highest combined rainfall.
- Nakuru and Kisumu: Consider the calculated planting windows alongside local weather forecasts.
- Mombasa and Machakos: Follow the calculated windows while considering local conditions and the imputed Machakos rainfall readings.
