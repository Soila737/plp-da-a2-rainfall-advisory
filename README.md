County Rainfall and Planting Advisory
Project Summary

This project analyses monthly rainfall readings for Nairobi, Nakuru, Kisumu, Mombasa and Machakos using Python and NumPy. It cleans invalid Machakos readings, calculates annual rainfall totals and monthly averages, identifies the wettest month and counts dry months for each county. It also identifies the consecutive two-month period with the highest combined rainfall to recommend a potential planting window.

How to Run the Notebook
Open rainfall_analysis.ipynb in Google Colab or Jupyter Notebook.
Install the dependency using pip install -r requirements.txt if needed.
Restart the runtime or kernel and run all cells from top to bottom.
Check the printed results and the generated rainfall_summary.csv file.
Planting Advisory
Nairobi: Use the calculated two-month rainfall window as an initial planting guide and confirm conditions with local forecasts.
Nakuru and Kisumu: Use each county's calculated rainfall window to plan planting and prepare seeds in advance.
Mombasa and Machakos: Follow the calculated county-specific windows while considering local weather, soil conditions and the Machakos data imputation caveat.
