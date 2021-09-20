# FinTech_Module_12 Challenge

# Background

In this challenge we dealth with data which hd inherent imbalance, in this case, for healthy and risky loans. In our sample set, risky loans occurred far less often but still at levels of loss unaccaptable for most businesses. In our first attempt to train and evaluate a logistric regression model, it became clear that while the model worked well for loans classfiied as "0" (healthy loans) with a recall of close to 99%, the performance for recall for risky loans led to almost 10% of risky loans not being detected by the model. 

Through resampling, we were able to amplify the balance between the healthy and risky loans and attain a higher recall score so critical in predicting which loans are likley to fail.

# Images

## Fig. 1: 

![Fig. 1](https://github.com/toniahurst/FinTech_Module_12/blob/main/images/Fig_1.png)

## Fig. 2: 

![Fig. 2](https://github.com/toniahurst/FinTech_Module_12/blob/main/images/Fig_2.png)

## Fig. 3: 

![Fig. 3](https://github.com/toniahurst/FinTech_Module_12/blob/main/images/Fig_3.png)

## Fig. 4: 

![Fig. 4](https://github.com/toniahurst/FinTech_Module_12/blob/main/images/Fig_4.png)
## Fig. 5: 

![Fig. 5](https://github.com/toniahurst/FinTech_Module_12/blob/main/images/Fig_5.png)


## Technologies

This program uses Python 3.7.10, Anaconda version 4.10.3, and JupyterLab 3.0.14. It also uses libraries from Pandas, Imbalanced-learn and PyDotPlus. It was written on macOS Catalina 10.15.7.

## Usage

Open the Jupyter Lab notebook at https://github.com/toniahurst/FinTech_Module_12/blob/main/credit_risk_resampling.ipynb or download the notebook and run from the CLI.

## Contributors

Antonia Hurst

## License
Copyright (c) 2015-2021 Project Jupyter https://github.com/jupyterlab/jupyterlab/blob/master/LICENSE



