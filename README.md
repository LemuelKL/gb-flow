# GB FLOW

This short project builds a simple classifier to predict whether an interconnector of Great Britain is importing or exporting electricity. The data is taken from BMRS of Elexon. [Link](https://bmrs.elexon.co.uk/interconnector-flows)

## data_reshape.ipynb

This notebook reshapes the raw data into friendlier format and saves it as a csv file.

## ml.ipynb

This notebook builds a simple Random Forest classifier.

There is a simple time-series feature extraction, and encoding of numerical values as categorical values (different levels of flow and direction).
