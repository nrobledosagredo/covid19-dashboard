# COVID-19 dashboard

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Jupyter Notebook](https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=for-the-badge&logo=jupyter&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black)
![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)

This dashboard visualizes the progression of confirmed cases, recoveries, and deaths due to COVID-19 in various countries. It uses **Jupyter Notebooks** and **Voila** to provide dynamic graphs for comparing pandemic trends between countries. Users can toggle between viewing **cumulative cases** or **daily new cases**.  

Created as a learning project to explore data visualization and dashboards.  

## Features  

- Visualization of **confirmed cases**, **recoveries**, and **deaths**.  
- Country-to-country data comparison.  
- Toggle options for **cumulative cases** or **new daily cases**.  
- COVID-19 data sourced from multiple reliable repositories.  

## Requirements  

- **Python 3.8.5** or higher.  
- Required dependencies:
   ```text
   pytest
   numpy
   matplotlib
   ipympl
   pandas
   voila
   voila-material
   mplcursors
   ```  

## How to run  

To run the dashboard locally, execute the following command:  

```bash
voila --port=8866 --Voila.ip=0.0.0.0 --no-browser --template=material covid19-dashboard.ipynb
```  

The dashboard will be accessible at [http://localhost:8866](http://localhost:8866).  