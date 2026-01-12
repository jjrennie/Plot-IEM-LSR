## Plotting National Weather Service Local Storm Reports
### Written By Jared Rennie (@jjrennie)

This Notebook will download one year's worth of Local Storm Reports from the <a href='https://mesonet.agron.iastate.edu/lsr/' target='_blank'>Iowa Environment Mesonet</a> repository and 
- Plot each LSR (point)
- Aggregate and plot by state

### What You Need
First off, the entire codebase works in Python 3. In addition to base Python, you will need the following packages installed:

- requests (to access the IEM api)
- pathlib and zipfile (to move and unzip data from IEM)
- numpy, pandas and geopandas (to slice annd dice the data)
- matplotlib and cartopy (to plot!)

The "easiest" way is to install these is by installing <a href='https://www.anaconda.com/' target='_blank'>anaconda</a>, and then applying <a href='https://conda-forge.org/' target='_blank'>conda-forge</a>. Afterward, then you can install the above packages.