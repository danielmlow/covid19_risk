


Data and code for Torrente, Low, Yoris (2022). "Risk perception, but also political orientation, modulate behavioral response to COVID-19: A randomized survey experiment". Frontiers in Psychology. 
https://www.frontiersin.org/articles/10.3389/fpsyg.2022.900684/full


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












