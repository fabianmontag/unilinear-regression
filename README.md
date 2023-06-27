# unilinear-regression
Jupyter Notebook for unilinear regression from scratch with python

# Installation and Running
Download the `unilinear_regression.ipynb` file and run with [Juypter Notebook](https://jupyter.org) or in [VS-Code](https://code.visualstudio.com/docs/datascience/jupyter-notebooks).
To run the algorithm, call the `run` function.

# Parameters
- `data`, data to run the model on, default is [housing price data](https://www.kaggle.com/datasets/yasserh/housing-prices-dataset), **if you change the data you also might have to adjust `testM`**
- `testM`, size of subarray of data array which is used to test the model, default is `70`
- `start_weight`, initial weight, defualt is `0`
- `start_bias`, initial bias, default is `0`
- `iterations`, iterations of gradient descent, default is `300`
- `alpha`, learning rate, default is `0.1`

# preview
<p float="left">
  <img width="500" src="https://github.com/fabianmontag/unilinear-regression/assets/113472012/ea1ece49-5bdb-421f-a998-d40294d05977" />
  <img width="500" src="https://github.com/fabianmontag/unilinear-regression/assets/113472012/6ddf0b50-9228-49b7-81de-46325e2acb88" />
  <img width="500" src="https://github.com/fabianmontag/unilinear-regression/assets/113472012/5fcdc4cb-64c7-4489-a944-e2abc2aa9b63" />
</p>
