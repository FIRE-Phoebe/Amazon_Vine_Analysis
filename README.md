# Amazon Vine Analysis

## Overview of the analysis
Amazon Vine Analysis project analyzes Amazon reviews that are written by members of the paid/unpaid Amazon Vine program. We perform the ETL process by using PySpark, AWS RDS instance, and pgAdmin to analyze the reviews of special product: software. Our goal is to determin if there is any bias toward favorable reviews from Vine members in our dataset.

## Results
According to our analysis, there are total 17,762 reviews. 
- Vine Program(paid) Reviews:
  - Reviews were written as the Vine program(paid) has 249.
  - There are 102 Vine reviews were 5 stars.
  - 5 stars reviews has 41.13%.

- Non-Vine Program(unpaid) Reviews:
  - Reviews were not part of the Vine program(unpaid) has 17,514.
  - There are 5,154 non-Vine reviews were 5 stars.
  - 5 stars reviews has 29.43%.

Reference:

<img src='images/summary.PNG' width=600 height=200>

### Resources
Codes for determination of analysis:

<img src='images/determination_code.PNG' width=600 height=300>

Exhibit 1: 
- Software review table:
https://github.com/FIRE-Phoebe/Amazon_Vine_Analysis/blob/2f8f8fc27d09ade588386386f8bec4ba239e66b4/images/review_table.PNG

Exhibit 2: 
- Software product table:
https://github.com/FIRE-Phoebe/Amazon_Vine_Analysis/blob/2f8f8fc27d09ade588386386f8bec4ba239e66b4/images/products_table.PNG

Exhibit 3: 
- Software customers table:
https://github.com/FIRE-Phoebe/Amazon_Vine_Analysis/blob/2f8f8fc27d09ade588386386f8bec4ba239e66b4/images/customers_table.PNG

Exhibit 4: 
- Software vine table:
https://github.com/FIRE-Phoebe/Amazon_Vine_Analysis/blob/2f8f8fc27d09ade588386386f8bec4ba239e66b4/images/vine_table.PNG

## Summary
In your summary, state if there is any positivity bias for reviews in the Vine program. Use the results of your analysis to support your statement. Then, provide one additional analysis that you could do with the dataset to support your statement.
