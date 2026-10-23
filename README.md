# California Housing

An end-to-end machine learning project that predicts the median house value of
a California district from census data, following chapter 2 of
*Hands-On Machine Learning* (Aurélien Géron).

## Data

`datasets/housing.csv` is the 1990 California census dataset. It has 20,640
districts and 10 columns: location, housing age, rooms, population, income,
`ocean_proximity` and the target `median_house_value`.

## Setup

```bash
python3 -m venv my_env
source my_env/bin/activate
pip install pandas numpy matplotlib scikit-learn jupyterlab
jupyter lab Housing.ipynb
```
