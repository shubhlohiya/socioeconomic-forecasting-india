## Socio-economic analysis and forecasting for India

This repository contains our code for the course project of the [DS203 - Programming for Data Science](https://www.minds.iitb.ac.in/index.php/academics?id=20) course conducted at IIT Bombay.

### Usage

#### **Install Dependencies**

* Install python 3.7+
* Install required python packages
  
  ```bash
  pip install pandas numpy matplotlib seaborn statsmodels scikit-learn shap tqdm jupyter
  ```

#### **Run Code**

* Load and preprocess data by running all cells in `preprocessing.ipynb`
* Generate EDA results, and create feature data for forecasting by running all cells in `EDA.ipynb`
* Run all forecasting analyses by running all cells in `forecasting.ipynb`


### Repository Structure

```plain
.
├── README.md
├── code
│   ├── EDA.ipynb 
│   ├── forecasting.ipynb
│   └── preprocessing.ipynb
└── data
    ├── Components_of_Money_Stock.xlsx
    ├── Exchange_Rate_of_the_Indian_Rupee_vis-a-vis_the_SDR,_US_Dollar,_Pound_Sterling_(Monthly_Average_and_End-Month_Rates).xlsx
    ├── India's_Foreign_Trade_-_US_Dollars.xlsx
    ├── features.csv
    ├── fed_st_louis
    │   ├── not seasonally adjusted
    │   │   ├── CPI.xls
    │   │   ├── Immediate_Rates.xls
    │   │   ├── Interest_Rates.xls
    │   │   ├── Share Prices.xls
    │   │   └── Wholesale_Industry_Prices.xls
    │   └── seasonally adjusted
    │       ├── CPI_Seasonally_Adjusted.xlsx
    │       ├── Consumer_Goods_Manufacture.xls
    │       ├── GDP.xls
    │       ├── GovernmentExpenditure.xls
    │       ├── Gross_Fixed_Capital.xls
    │       ├── Immediate_Rates_SA.xlsx
    │       ├── Interest_Rates_SA.xlsx
    │       ├── Share_Prices_SA.xlsx
    │       └── Wholesale_Industry_Prices_SA.xlsx
    └── merged_data.csv
```

***
<p align='center'>Created with :heart: by <a href="https://www.linkedin.com/in/lohiya-shubham/">Shubham Lohiya</a> & <a href="https://www.linkedin.com/in/swarada-bharadwaj-5145a1174/">Swarada Bharadwaj</a></p>