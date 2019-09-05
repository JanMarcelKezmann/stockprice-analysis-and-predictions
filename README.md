# Stockprice Analysis and Predictions

<p>This tool is meant to gain data from the <a href="https://finance.yahoo.com">Yahoo finance page</a> and display some historical features of a stock trend within a given period of time</p>

### Some Results of the Stockprice analysis and predictions: 
- The best model after testing over 10 different stocks is always the GradientBoosting Regressor
- Even Averaged models are combined not better the the GradientBoosting Regressor alone
- The accuracy depends strongly on the volatility of each stock (the more volatile the less better/accurate the prediction)
- The range of the accuracies for different tested stocks like Microsoft, Apple, Audi and many others are in a range of 97 - 99.9 % for the best model (GradientBoosting Regressor)
- other models performed from about 90 % for very volatile stocks to up to 99.5 % for very stable one

## Local Installation

### Clone the repo (or simply download it)
```shell
$ git clone https://github.com/JanMarcelKezmann/stockprice-analysis-and-predictions.git
```

### Install requirements
##### (in shell)

```shell
pip install -r requirements.txt
```

### Run with JupyterNotebook or JupyterLab
<p>Just open the .ipynb code in a Notebook of your choice and run it.


## Example: Microsoft
<p align="center">
  <img src="https://user-images.githubusercontent.com/50111329/64119384-0986d600-cd9a-11e9-9e62-d2f7d2822e62.png" width="600px" alt="">
</p>
