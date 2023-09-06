# E-Commerce Sales - Excel Dashboard and Pivot Tables

## Project Overview

This project focuses on analyzing and visualizing e-commerce sales data from different channels covering a variety of products.The Goal is to Analyze the general sales trends by examining info such as month, category, currency, and customer for each sale. This will give an idea about how the e-commerce business is performing in each channel.

## Data Cleaning

Prior to analysis, the raw data is subjected to a data cleaning process to ensure accuracy and reliability.
* Date Range - April 1, 2022 to June 29, 2022
* Columns to delete
    Unnamed: 22 - undeterminable data
    fulfilled-by - only value was amazon courier "easy-ship" with no other relationship
    ship-country - The shipping Country is India
    currency - the currency is Indian Rupee (INR)
    Sales Channel - assumed to be sold through amazon
* Columns to delete duplicates
    Order
    ASIN
* Columns to handle missing values 
    Courier Status - will fill missing with 'Unknown'
    promotion-ids - will fill missing with 'No Promotion'
    Amount - will fill missing with 0, since 97% of of all Orders with missing Amount are cancelled
    ship-city - will fill missing with 'Unknown'
    ship-state- will fill missing with 'Unknown'
    ship-postal-code - will fill missing with 'Unknown'
* Columns to Add
    Promotion status - TRUE for sales promotion, FALSE if there is No promotion to increase sales
    Customer type - Customer for regular customer, Business for B2B


## Findings

* The total revenue for Q2 2022 decreased by -18.77% from April to June, with May revenue experiencing a -9.06% decrease from April, and June revenue seeing a -10.68% decrease from May, which is a cause of concern.
* The revenue is dominated by the product category "Set," which accounts for 49.88% of total revenue, followed by kurta with 27.09% and Western Dress with 14.28%.
* The top 5 product categories by average price are Set (780), Kurta (427), Western Dress (724), Ethnic Dress (682), and Top (503), indicating that these products are high-value orders.
* The total number of cancelled and returned orders was 20,428, which represents 15.86% of all orders. Of these, 14.22% were cancelled and 1.64% were returned.
* Fulfilment by Amazon (FBA) boasts a higher rate of successful deliveries compared to Fulfilment by Merchant (FBM). FBM presents a range of potential issues that can arise during the shipping process, making customers more inclined to opt for stores utilizing FBA over FBM.
* Around 99% of orders are placed by Regular customers and the remaining by the Business customers.
  
## Recommendations

* Promotion to drive interest in the Western Dress category
* To capture consumer attention, strategies such as bundling purchases or offering a complimentary item from lower-selling categories with relatively lower-priced products (e.g., bottoms, blouses, dupattas) could be employed.
* Sellers should prioritize efficient delivery methods to ensure customer satisfaction. Understanding fulfillment processes and anticipating potential risks associated with different shipping methods are vital steps to providing a seamless shopping experience. This approach not only bolsters customer trust but also fosters lasting relationships.





![dashboard_page-0001](https://github.com/divya030/E-Commerce-Sales-Excel-Dashboard-/assets/96876070/f4f7730f-250d-4c01-a712-c02459906b8b)





