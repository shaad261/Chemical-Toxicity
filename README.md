# LC-50 Value Prediction
Prediction of LC50 value using Quantitative structure activity relationship models ( QSAR models ). Develop quantitative regression QSAR models to predict acute aquatic toxicity towards the fish fathead minnow ( Pimephales promelas ) on a set of 908 chemicals based on 6 molecular descriptors. Dataset: https://archive.ics.uci.edu/ml/datasets/QSAR+fish+toxicity

LC50 data, which is the concentration that causes death in 50% of test fish over a test duration of 96 hours, was used as model response. The model comprised 6 molecular descriptors: MLOGP (molecular properties), CIC0 (information indices), GATS1i (2D autocorrelations), NdssC (atom-type counts), NdsCH ((atom-type counts), SM1_Dz(Z) (2D matrix-based descriptors). Regressor Models used:

K-Nearest Neighbours

Multiple Linear Regression

XGBoost Regressor

Support Vector Machine Regressor

Random Forest Regressor

Bayesian Ridge Regressor

## Understanding input values
CIC0 - information indices
SM1_Dz(Z) - 2D matrix based descriptors
GATS1i - 2D autocorrelations
NdsCH - atom type counts
NdssC - atom type counts
MLOGP - molecular properties

## Understanding target
LC50 - Lethal concentration 50 (LC50) is the amount of a substance suspended in the water required to kills 50% of a test animals during a predetermined observation period. LC50 values are frequently used as a general indicator of a substance's acute toxicity.

## Project Demonstration
Check out the project demo at 

## Deployed app link
Check out the deployed app at 




## Run Locally
### Software And Tools Requirements

1. [Github Account](https://github.com)
2. [AWS Account](https://https://aws.amazon.com/.com)
3. [VSCodeIDE](https://code.visualstudio.com/)
4. [GitCLI](https://git-scm.com/book/en/v2/Getting-Started-The-Command-Line)

Create a new environment

```
conda create -p venv python==3.8 -y

```
Install all the requirements
```
pip install requirements.txt
```
Run the application
```
python app.py
```