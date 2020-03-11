# Yield Map charting with Eikon Data API
This python model is designed to visualise a bond portfolio as a scatter plot and construct yield curves from its constituents automatically. Another feature of this module is the label placement algo, which prevents scatter datapoint annotations from overlapping. [Full article is provided here](https://developers.refinitiv.com/article/yield-map-charting-eikon-data-api).

This package contains 3 Jupyter notebooks. The main model is stored in <b>ymap_charts.ipynb</b>. To run it, make sure to store it in the same folder with the other notebooks from this repository: bond_metadata.ipynb and curve_fitting.ipynb.

#### Pre-requisites:

Refinitiv Eikon or Refinitiv Workspace with access to Eikon Data APIs.

<b>Required Python Packages:</b> eikon, pandas, numpy, matplotlib, numba, scipy, ipynb.
<b>Other dependencies:</b> bond_metadata.ipynb, curve_fitting.ipynb
