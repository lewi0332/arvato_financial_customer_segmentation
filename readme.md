
# Arvato Financial Customer Segmentation and Propensity to Respond

Capstone project for the [Udacity Data Science NanoDegree Program](https://www.udacity.com/course/data-scientist-nanodegree--nd025)

---

## Goal

Arvato Financial Service is looking to determine a more efficient method of marketing to customers. Using a data file with information about the general population of Germany and a second file of similar data of current customers. This project uses K-Means clustering to look for attributes of indivduals that match the current customer base.

Next, the project uses similar data from a recent direct mail effort and the subsequent responses to train a model to predict which future mailing are likely to respond. Thereby potentially reducing the cose of future marketing by targeting only those with a higher potential to respond. 

Finally, I will submit the results of the trained model to Kaggle to compete in the corresponding competition to this program. 

---

## Data

- `Udacity_AZDIAS_052018.csv`: Demographics data for the general population of Germany; 891 211 persons (rows) x 366 features (columns).
- `Udacity_CUSTOMERS_052018.csv`: Demographics data for customers of a mail-order company; 191 652 persons (rows) x 369 features (columns).
- `Udacity_MAILOUT_052018_TRAIN.csv`: Demographics data for individuals who were targets of a marketing campaign; 42 982 persons (rows) x 367 (columns).
- `Udacity_MAILOUT_052018_TEST.csv`: Demographics data for individuals who were targets of a marketing campaign; 42 833 persons (rows) x 366 (columns).

Publishing the data by Arvato Financial Services for this project is not allowed due to the terms and conditions.

## Files 

- [Arvato Project Workbook.ipynb](https://nbviewer.jupyter.org/github/lewi0332/arvato_financial_customer_segmentation/blob/master/Arvato%20Project%20Workbook.ipynb) - This is the primary file with EDA, segmentation and model training. 
- recreate the K-Means clustering on a new dataset.
- [output.html](output.html) - This is a `pandas Profiler` file with information to guide initial EDA. 
- [customer_segmentation/clusters.pkl](customer_segmentation/clusters.pkl) - This file is a Sklearn Pipeline Object with the trained scaler, PCA and K-Means algorithms to 
- [value_unknown_codes.csv](value_unknown_codes.csv) - This is a list of codes which represent `unknown` or `missing` data in our data set by attribute. It is used in cleaning data for new 
  
## Installation

1. Install necessary libraries using Anaconda
    - `conda env create -f environment.yml`

2. Activate the Envirnoment
    - `conda activate cust_segm`

## Author

-   **Derrick Lewis**  [Portfolio Site](https://www.derrickjameslewis.com) - [linkedin](https://www.linkedin.com/in/derrickjlewis/)


## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

## Acknowledgments

I would like to thank [Udacity](https://eu.udacity.com/) for this amazing project, and [Arvato](https://www.arvato.com/)  for providing the data.