This repository implements **Exploratory Data Analysis** for the **House Price** dataset provided at [github.com/ArinB/MSBA-CA-Data/CA01](https://github.com/ArinB/MSBA-CA-Data/tree/main/CA01). 
This data provides various features that might be useful for predicting house prices. 
The data includes a data description text file, a training set, and a test set.
In this assignment, we only work with the training data.

The code for EDA is in the `eda-duong-pham.ipynb` notebook. The code has 3 parts, which are also denoted in the notebook.

Part 1: We perform various visualizations of the data and a Data Quality Report that identifies potential problems that exist in this dataset.

Part 2: We fix the data problems identified above.

Part 3: We perform collinearity visualization to identify features that need to be dropped (feature selection).

After running, the code will generate 3 data files, corresponding to 3 stages of processing the data:

- `house-price-train-cleaned.csv` is the data after fixing data problems but before encoding.
- `house-price-train-cleaned-encoded.csv` is the data after fixing data problems and encoding categorical features.
- `house-price-train-cleaned-encoded-feature-selected.csv` is the data after fixing data problems, encoding categorical features, and dropping features with collinearity issues (feature selection).
