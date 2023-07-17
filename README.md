## Regression Inference to Predict Snowy Plover Bird Weight from Egg Weight.ipynb

**This Jupyter Notebook provides a set of functions to create two bootstrap confidence intervals for the purpose of regression inference to predict Snowy Plover bird weight from egg weight.** The Snowy Plover, a small coastal bird found in parts of California and other regions, is classified as endangered in several areas of the United States. This Jupyter Notebook presents a collection of functions designed to construct two bootstrap confidence intervals for regression inference. The goal is to predict Snowy Plover bird weight based on egg weight.

- The first bootstrap confidence interval is for the true slope of the regression line that predicts `Bird Weight` from `Egg Weight`.
- The second bootstrap confidence interval is for the true value of the mean bird's weight for an egg of `x` grams. 

## snowy_plover.csv

Each row of the this table corresponds to one Snowy Plover egg and the resulting chick. The data was collected at the Point Reyes National Seashore.

- `Egg Length` and `Egg Breadth` (widest diameter) are measured in millimeters
- `Egg Weight` and `Bird Weight` are measured in grams; for comparison, a standard paper clip weighs about one gram
