
# Food Marketing Analysis

## Project overview

This project explores customer demographics, purchasing behavior, and marketing campaign acceptance using `u_food_marketing.csv`. The analysis is performed in `food_market.ipynb` with pandas, seaborn, and matplotlib.

## Data cleaning and preparation

- Checked for duplicate rows and removed all rows belonging to duplicate groups using `drop_duplicates(keep=False)`.
- Added new column `Total_Children`, the sum of children and teenagers in each household.
- Combined the marital-status indicator columns into a numeric `Marital_Status` code and a descriptive `Marital_Status_Label`.
- Combined the education indicator columns into an `Education_Level` code and an `Education_Level_Label`.
- Created `Accepted_Campaigns`, set to 1 if a customer accepted at least one campaign (including `Response`), and 0 otherwise.
- Grouped ages into ranges: 23–30, 31–40, 41–50, 51–60, 61–70, and 71–85.

## Analysis performed

- Numeric correlations with campaign acceptance.
- Campaign acceptance and spending by age group.
- Web, catalog, and store purchase totals, for all customers and those who accepted campaigns.
- Relationships between household children, education, and spending or campaign acceptance.
- Examined spending and campaign acceptance according to marital status.

## Analysis Findings

- Customers aged 30–70 are identified as higher spenders, while some younger and older age groups are noted as having higher campaign acceptance.
- Catalog customers are described as more likely to accept campaigns, while store purchases contribute more spending.
- Households with fewer children are associated with higher spending and campaign acceptance.
- Education and marital status are described as having limited influence overall, though married, single, and together customers contribute more total spending.

## Running the analysis

1. Place `u_food_marketing.csv` in the project directory.
2. Open `food_market.ipynb` in Jupyter or Visual Studio Code.
3. Run the notebook cells in order.
