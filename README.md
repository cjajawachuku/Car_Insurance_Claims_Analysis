**INTRODUCTION**

This report comprehensively explores car insurance claim data to uncover valuable insights into car insurance claims. Car insurance is a service that offers financial protection to people who own cars in case of unexpected events, such as accidents or theft. The goal is to uncover meaningful patterns and information hidden within the provided data by examining customer information, car characteristics, and insurance claims.

***NOTE: The dataset used for the creation of this report can be found for free on Onyx Data: https://onyxdata.ck.page/8cbde7b71b***

**OBJECTIVES**
- **Understanding Claim Trends:** By examining the historical data of insurance claims, this report looks to identify trends and patterns in the frequency and severity of insurance claims.
- **Risk Assessment and Pricing:** By examining attributes such as age, marital status, vehicle details, and coverage zones, this report intends to uncover key drivers of insurance claims. 
- **Customer Segmentation:** The dataset contains a wealth of demographic information. By segmenting customers based on age groups, gender, education level, and household income, this report aims to identify high-risk customer segments and tailor insurance offerings to suit their needs better.
- **Recommendations for Policy Enhancements:** The report will provide recommendations for refining insurance policies based on the analysis outcomes. These suggestions can help insurance companies offer products that align more closely with customer preferences and needs.

**DATA EXAMINATION AND CLEANING**
- Checked for Duplicates
	* No Duplicates were found
- Created an "Age" column using the birth date provided in the Insurance claims dataset.
- An age range column called "age_groups" was created using Excel's IF statements.
- Changed data types for "claim_amt" and "household_income" from decimal to accounting to reflect their monetary format.
- Due to the large unique numbers of "car_year", a new column called "car_year_groups" was created based on individual car years. This task was achieved using Excel's IF statements.
- The previous step was replicated for household income to create a new column called "household_income_groups."
