# Analysis of Myntra_Apparel



## Table of Contents

-[Project Overview](#project-overview)

-[Data Source](#data-source)

-[Data Cleaning and Preparation](#Data-Cleaning-and-Preparation)

-[Data Analysis](Data-Analysis)

-[Data Retrieval and Lookup Function](Data-Retrieval-and-Lookup-Function)

---

### Project Overview

This data analysis project aims is to analyze a dataset of various apparel items to gain insights into pricing,
discounts, ratings, and available sizes of Myntra, a leading online fashion retailer.

---

### Data Sources

Myntra Dataset Link: https://drive.google.com/file/d/1CDaWFvkccjdUw1E_gipTKOfMqiHNhNQL/view

---

### Tools

- Excel
  - Data Cleaning and Preparation
  - Data Analysis
  - Data Retrieval and Lookup
 
---

### Data Cleaning and Preparation

In the initial data preparation phase, i have performed the following tasks:
1. Data loading and inspection.
2. Check for duplicate values in the dataset and remove them.
3. Standardize the "DiscountOffer" column to a single format, ensuring all values are uniform.
4. Identify rows where both "DiscountPrice" and "DiscountOffer" are null and fill the "DiscountPrice"
   with the average discount price of the respective category.
5. Replace all null values in the "SizeOption" column with the text "Not Available."

---

### Data Analysis

Exploring the data and performing few calculation's, such as:
1. Calculate the overall average original price for products with ratings greater than 4.
2. Count the number of products with a discount offer greater than 50% OFF.
3. Count the number of products available in size "M."
4. Create a new column to label the products as "High Discount" if the discount offer is greater
   than 50% OFF, otherwise label them as "Low Discount."

---

### Data Retrieval and Lookup Function

1. Use VLOOKUP/XLOOKUP to find the product brand, price, and rating of the product with Product_id "11226634".

![Screenshot 2024-08-06 162638](https://github.com/user-attachments/assets/b477d9f3-90d4-4681-b843-9adb08855194)


![Screenshot 2024-08-06 162736](https://github.com/user-attachments/assets/35523609-43ec-439a-91f7-fd8bd51efbe9)



3. Find the "DiscountPrice" for the product with the Product ID "6744434" using the INDEX and MATCH functions.

  ![Screenshot 2024-08-06 162510](https://github.com/user-attachments/assets/40520d83-f228-4c9e-ac01-ba3df71e1eb7)

