# Tyre Degradation and Lap Time Analysis

This project looks at how tyre wear affects lap time during Lewis Hamilton's medium stint in the 2025 Abu Dhabi Grand Prix.

I used FastF1 to pull the race data, filtered it to the medium compound, and removed the first and last tyre-life points so the analysis focused on the main degradation period.

From there, I created a scatter plot, calculated the correlation, and fit a simple linear regression model and checked the residuals to see whether the linear model was a reasonable fit for the data

The results show a clear upward trend between tyre life and lap time, which matches the idea that tyre degradation leads to slower lap times over the stint.

## Tools
- Python
- FastF1
- Pandas
- NumPy
- SciPy
- Statsmodels
- Matplotlib

## Files
- `hamilton-tyre-analysis.ipynb` - main notebook
- `README.md` - project summary
