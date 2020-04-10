# <center>Plotting heatmap from excel for ChIP data</center>

This is a Jupyter notebook that you can use to plot interactively 
a heatmap from a sheet of an Excel file that looks like this 

![](heatmap_chip_sheet.png)

The exact header and row index labels are not important.

You will need to rename the sheet you want to plot sns_*, e.g. sns_mcm or sns_pcna

## Minimum requirements

- pandas 0.22.0 - 1.0.1
- seaborn 0.8.1 - 0.10.0
- matplotlib 2.2.2 - 3.1.3
- ipywidgets 7.1.2 - 7.5.1
- xlrd 1.1.0 - 1.2.0