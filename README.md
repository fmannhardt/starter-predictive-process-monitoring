# Predictive Process Monitoring - A Starter Package for Jupyter

The notebooks in this repository are part of the assignment in the course Advanced Process Mining and intended as a starter for building your own prediction models for predictive process monitoring. They can be used as:

* Cloud notebooks via MyBinder  
* Local stand-alone notebooks
* Local Dockerized notebooks

refer to the Installations \& Usage section below for usage instructions.

You may also refer to the PM4Py documentation on Machine Learning for further options or an alternative to this implementation:
https://processintelligence.solutions/static/api/2.7.11/api.html#machine-learning-pm4py-ml

The collection of notebooks is a *living document* and subject to change.

## Table of Contents

*  [Data Loading](python/0_data_loading.ipynb) [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/fmannhardt/starter-predictive-process-monitoring/HEAD?urlpath=lab%2Ftree%2Fpython%2F0_data_loading.ipynb)
*  [Data Preparation](python/1_data_preparation.ipynb) [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/fmannhardt/starter-predictive-process-monitoring/HEAD?urlpath=lab%2Ftree%2Fpython%2F1_data_preparation.ipynb)
*  [Prediction Outcome](python/2_prediction_outcome.ipynb) [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/fmannhardt/starter-predictive-process-monitoring/HEAD?urlpath=lab%2Ftree%2Fpython%2F2_prediction_outcome.ipynb)

## Installation \& Usage

### Cloud notebooks via MyBinder

Click on the `launch binder` links for either the R or the Python notebook. You could also  use the [Google Colab service](https://colab.research.google.com/); however, you may need to prepare the Google Colab environment to have the respective packages installed (see standalone instructions).

### Local notebooks

#### Docker Compose

Build and run a Docker image with Compose:

```
docker compose up -d
```

#### Standalone

Please make sure to have installed the following requirements:

**Python**

```
pip install -r requirements.txt
```

Make sure to install GraphViz for the visualization as per PM4Py documentation https://processintelligence.solutions/static/api/2.7.11/install.html

You should be able to run the Jupyter notebooks directly in a Jupyter environment using:
```
jupyter lab
```



