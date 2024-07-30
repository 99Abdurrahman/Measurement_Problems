# Measurement Problems

This repository contains solutions to two important business problems in e-commerce and digital marketing. The solutions are implemented using Python and include data analysis, visualization, and statistical testing.

## Business Problems

### 1. Correct Calculation of Product Ratings and Review Rankings
One of the most important problems in e-commerce is the correct calculation of the points given to the products after the sale. Correctly calculating these points means more customer satisfaction for the e-commerce site, product prominence for sellers, and a smooth shopping experience for buyers. Another problem is the correct ranking of the comments given to the products. Misleading reviews can directly affect the sales of a product, causing both financial and customer loss. Solving these problems will help e-commerce sites and sellers increase their sales while customers will complete their purchasing journey smoothly.

#### Dataset
This dataset of Amazon product data includes product categories and various metadata. The most reviewed product in the electronics category has user ratings and reviews.

#### Variables:
- `reviewerID`: Reviewer's ID, e.g., A2SUAM1J3GNN3B
- `asin`: Product's ID, e.g., 0000013714
- `reviewerName`: Reviewer's name
- `helpful`: Helpfulness rating of the review, e.g., 2/3
- `reviewText`: Review text
- `overall`: Product rating
- `summary`: Summary of the review
- `unixReviewTime`: Review time (unix time)
- `reviewTime`: Review time (raw)
- `day_diff`: Number of days since the review
- `helpful_yes`: Number of helpful votes
- `total_vote`: Total number of votes

### 2. Comparison of A/B Test and Conversion of Bidding Methods
Facebook recently introduced a new type of bidding, “average bidding”, as an alternative to the existing type of bidding called “maximum bidding”. One of our clients, bombabomba.com, decided to test this new feature and run an A/B test to see if average bidding brings more conversions than maximum bidding. The ultimate success metric for bombabomba.com is Purchase. Therefore, for statistical testing, the focus is on the Purchase metric.

#### Dataset
This dataset, which contains a company's website information, includes information such as the number of advertisements seen and clicked by users, as well as information about the earnings from these advertisements. There are two separate datasets for the Control and Test groups. Maximum Bidding was applied to the control group and Average Bidding to the test group.

#### Variables:
- `impression`: Number of ad views
- `Click`: Number of clicks on the displayed ad
- `Purchase`: Number of products purchased after clicking ads
- `Earning`: Earnings from purchased products

## Notebooks
The repository includes the following Jupyter notebooks:

1. **Amazon Product Reviews Analysis.ipynb**: This notebook contains the solution to the problem of calculating product ratings and ranking reviews.
2. **AB Test Analysis.ipynb**: This notebook contains the solution to the problem of comparing A/B test results for different bidding methods.

## How to Run the Notebooks
1. Clone the repository:
    ```bash
    git clone https://github.com/99Abdurrahman/Measurement_Problems.git
    ```
2. Navigate to the repository directory:
    ```bash
    cd measurement_problems
3. Install the required dependencies:
    ```bash
    pip install -r requirements.txt 
4. Open the Jupyter notebooks:
    ```bash
    jupyter notebook
    ```
    
## Acknowledgements
- The Amazon dataset is sourced from Amazon product data.
- The A/B test dataset is sourced from a company's website information.

Feel free to reach out if you have any questions or suggestions!

---

**Author:** Abdurrahman Güzel

---
