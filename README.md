# Atlas-Global-Bank-Emerging-Markets-Analysis

## Project Summary
Atlas Global Bank is focused on identifying expansion opportunities in high-growth emerging markets. These regions are characterized by rapid economic development, expanding middle classes, and increased consumption patterns. The goal is to explore how these factors drive investment potential in key sectors and to group countries based on economic performance to guide strategic decisions.

## Data Source
- **Provided by**: World Bank - World Development Indicators 
- **File types**: CSV and JSON
- **Information**:
  - `Country Name`
  - `Country Code`
  - `Year`
  - `BX.KLT.DINV.WD.GD.ZS`: Foreign direct investment, net inflows (% of GDP)
  - `FP.CPI.TOTL`: Consumer Price Index (CPI)
  - `NE.CON.TOTL.KD.ZG`: Final consumption expenditure growth (annual %)
  - `NE.EXP.GNFS.KD.ZG`: Exports of goods and services (annual % growth)
  - `NE.GDI.TOTL.KD.ZG`: Gross capital formation growth (annual %)
  - `NE.IMP.GNFS.KD.ZG`: Imports of goods and services (annual % growth)
  - `NY.GDP.MKTP.CD`: GDP (current US$)
  - `NY.GDP.MKTP.KD.ZG`: GDP growth (annual %)
  - `NY.GNS.ICTR.ZS`: Gross savings (% of GDP)
  - `SL.UEM.TOTL.ZS`: Unemployment (% of total labor force)
  - **Cluster**: Country groupings based on economic performance:
   
## Folders
Description of folder contents are as follows:

- **01 Project Management**: Contains the project brief and relevant documentation.
- **02 Data**: Includes two subfolders:
  - *Original Data*: Raw datasets from the World Bank.
  - *Prepared Data*: Cleaned and processed data for analysis.
- **03 Scripts**: Python code used in the analysis, written and executed using Jupyter notebooks.
- **04 Analysis**: Contains exploratory analysis and visualizations.

## Code Overview
Code was written in Python and executed in Jupyter notebooks.

- **Python libraries**:
  - `Pandas`: For data manipulation and analysis.
  - `NumPy`: For numerical computations.
  - `Matplotlib, Seaborn`: For data visualization and informative charts.
  - `OS`: For file and directory operations.
  - `Scikit-learn (sklearn)`: For clustering analysis using KMeans.
  - `Statsmodels`: For statistical modeling.
  - `Pylab`: For additional plotting utilities.

## Limitations
This analysis only included macroeconomic KPIs and did not account for sector-specific KPIs, which may affect the accuracy of the predictions. Additionally, the dataset from the World Bank may contain inherent biases, impacting the analysis results.

## Disclaimer
This analysis has been made for academic propuses.

[View the Tableau Dashboard on Banking Expansion Opportunities](https://public.tableau.com/app/profile/isaac.contreras/viz/AtlasGlobalBank/BankingExpansionOpportunitiesCaseAnalysis)

