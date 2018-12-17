# Loan Repayment Prediction

A comparison of automated feature engineering using Featuretools and manual feature engineering
for the Home Credit Default Risk machine learning competition currently [running on Kaggle](https://www.kaggle.com/c/home-credit-default-risk).

<p float="left">
  <img src="images/time_comparison.png" width="280" />
  <img src="images/features_comparison.png" width="280" />
  <img src="images/score_comparison.png" width="280" />
</p>

### Notebooks

The notebooks are as follows:

1. `Manual Loan Repayment.ipynb`
2. `Automated Loan Repayment.ipynb`
3. `Featuretools on Dask.ipynb`
4. `Semi-Automated Loan Repayment.ipynb`
5. `Feature Selection.ipynb`
6. `Results.ipynb`

`utils.py` contains a number of useful helper functions and `random_search.py` in the
`scripts` directory was used for the random search implementation. To generate the final feature matrix,
use the `Featuretools on Dask` notebook or run the `ft.py` script. The script takes nearly 
a full day to run, while depending on your system, the notebook can run in a few hours.

### Data

The data can be downloaded [here](https://www.kaggle.com/c/home-credit-default-risk/data).

To run the notebooks, place the following data files in the `input` directory:
`application_train.csv`, `application_test.csv`, `bureau.csv`, `bureau_balance.csv`,
`POS_CASH_balance.csv`, `credit_card_balance.csv`, `previous_application.csv`,
and `installments_payments.csv`. The `HomeCredit_columns_description.csv` file may
be helpful as it contains the data decscriptions.

## Feature Labs
<a href="https://www.featurelabs.com/">
    <img src="http://www.featurelabs.com/wp-content/uploads/2017/12/logo.png" alt="Featuretools" />
</a>

Featuretools is an open source project created by [Feature Labs](https://www.featurelabs.com/). To see the other open source projects we're working on visit Feature Labs [Open Source](https://www.featurelabs.com/open). If building impactful data science pipelines is important to you or your business, please [get in touch](https://www.featurelabs.com/contact.html).

### Contact

Any questions can be directed to help@featurelabs.com
