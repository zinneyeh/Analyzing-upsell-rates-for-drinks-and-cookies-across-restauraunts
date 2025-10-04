# CIS530 Final Project Assignment

## Project Title:  
**Analyzing Upsell Rates for Drinks and Cookies Across Restaurants**

---

## Author:  
_Zin Min Thant_

---

## Overview  
This project analyzes the *Dig* dataset from *Python for MBAs* to answer the business question:

**Do certain restaurants have higher cookie or drink upsell rates, and can this inform targeted upselling strategies?**

Using Python and pandas, this analysis calculates upsell percentages by restaurant location and identifies trends to help inform targeted marketing and sales strategies.

---

## Dataset  
The analysis uses the following CSV files from the CIS530 dataset:  
- `Restaurants.csv` — Restaurant metadata including names and locations  
- `Simplified orders.csv` — Order-level data including counts of drinks and cookies ordered  
- `Items.csv` and `Summarized orders.csv` (loaded but not used in current analysis)

---

## Methodology  
1. Load and inspect relevant data files using pandas.  
2. Filter orders to find those including at least one drink or cookie.  
3. Calculate the total upsell counts and upsell percentages per restaurant.  
4. Merge upsell statistics with restaurant names for readability.  
5. Identify restaurants with highest upsell rates for drinks and cookies.

---

## Key Results  
- Total orders analyzed: 2,387,224  
- Highest drink upsell rate: Midtown (1.40%)  
- Highest cookie upsell rate: NYU (3.60%)  

| Restaurant      | Drink Upsell % | Cookie Upsell % |
|-----------------|----------------|-----------------|
| NYU             | 1.12%          | 3.60%           |
| Midtown         | 1.40%          | 2.73%           |
| Williamsburg    | 1.04%          | 2.63%           |
| Upper West Side | 0.93%          | 2.36%           |
| Flatiron        | 0.93%          | 2.35%           |
| Upper East Side | 1.10%          | 2.29%           |
| Columbia        | 0.57%          | 2.09%           |
| Bryant Park     | 0.76%          | 1.91%           |

---

## Conclusion  
The analysis demonstrates that upsell success varies significantly by restaurant location. The NYU and Midtown locations outperform others in upselling drinks and cookies, respectively. This insight suggests that targeted upselling strategies tailored by location could improve overall revenue.

High-performing locations should be studied as models for upselling tactics, while underperforming restaurants could benefit from revised training or digital upselling initiatives.

---

## How to Run  
1. Mount your Google Drive (if using Google Colab) to access the dataset files.  
2. Load the datasets as CSV files using pandas.  
3. Run the analysis cells in the Jupyter notebook sequentially.  
4. Review the output tables and visualizations (if any) to understand upsell trends.

---

## Dependencies  
- Python 3.x  
- pandas  
- Google Colab (optional, for drive mounting)  

---



---

