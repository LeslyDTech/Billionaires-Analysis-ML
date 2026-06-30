# Billionaires Analysis with Python
 
A simple data analysis project that explores global billionaire data using Python, Pandas, and Seaborn/Matplotlib.
 
Based on [this tutorial](https://thecleverprogrammer.com/2021/06/24/billionaires-analysis-with-python/).
 
## What it does
 
- Cleans and analyzes a billionaires dataset
- Visualizes the top 10 billionaires by net worth
- Shows the top sources, industries, and countries for billionaires
## Tech
 
Python, Pandas, NumPy, Seaborn, Matplotlib
 
## Run it
 
```bash
pip install pandas numpy matplotlib seaborn
python main.py
```
 
## What I learned
 
- Cleaning messy string data (like `"$177 B"`) into usable numbers with Pandas
- Picking the right chart for the data (bar plots vs. pie/donut charts)
- Building donut charts in Matplotlib using `plt.pie()` + a white center circle
- Loading a dataset straight from a CSV URL instead of a local file
