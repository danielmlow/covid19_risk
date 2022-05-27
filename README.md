


Data and code for Torrente et al. "Risk perception, health protection behaviors, and the effect of risk-related messages on acceptance of restrictive measures in the face of the second wave of COVID-19 in Argentina" 


## 1. Data

Available at `./data/input/`

* `COVID-19_risk.csv` Main Dataset



## 2. Reproduce

**Google Colab**

The `.ipynb` can run on Google Colab (for which data should be on Google Drive; code to load data from Google Drive is available in scripts)
You can install packages with `!pip install <package-name>`


**Jupyter Notebook**

To run the `.ipynb` on Jupyter Notebook, open terminal, create a virtual environment and install the `requirements.txt`:

```
conda create --name argentina_covid --file requirements.txt
conda activate argentina_covid
```


**Scripts**



Regression analysis:
```
jupyter notebook regression.ipynb
```












