**INTRODUCTION**

This report comprehensively explores car insurance claim data to uncover valuable insights into car insurance claims. Car insurance is a service that offers financial protection to people who own cars in case of unexpected events, such as accidents or theft. The goal is to uncover meaningful patterns and information hidden within the provided data by examining customer information, car characteristics, and insurance claims.

***NOTE: The dataset used for the creation of this report can be found for free on Onyx Data: [Onyx Challenge](https://onyxdata.ck.page/8cbde7b71b)***

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

<img width="574" alt="Dashboard" src="https://github.com/cjajawachuku/Car_Insurance_Claims_Analysis/assets/75726348/0b3aa4c5-282c-4011-9029-8f850bce5147">


*DashBoard Preview* [View Full Dashboard](https://github.com/cjajawachuku/Car_Insurance_Claims_Analysis/blob/main/Dashboard.pdf)

<img width="862" alt="Raw Dataset" src="https://github.com/cjajawachuku/Car_Insurance_Claims_Analysis/assets/75726348/eeafbd1c-6ef4-41c7-8f2d-11e11fa2eb94">

*Raw Dataset*

<img width="902" alt="Cleaned Dataset" src="https://github.com/cjajawachuku/Car_Insurance_Claims_Analysis/assets/75726348/4173f44c-78e5-4950-8834-aaaa7134d452">

*Cleaned Dataset*

**FINDINGS**
- There seems not to be any real distinction based on gender when it comes to Car Insurance Claims, with females requesting Insurance claims 50.1% of the time while males sort claims 49.9% of the time.
- It was observed that single male and female individuals are most likely to file for insurance claims. Married people closely follow this group.
- It was observed that people between the ages of 36 -55 as most likely to file for car insurance claims
- Bachelor degree holders are the highest in terms of car insurance claims
- Coverage zones and Household income have no real correlation with Car Insurance Claims
- It was observed that most Car Insurance Claims were made on incidents relating to Cars manufactured in the year 2000s
- Individuals with no kids, regardless of marital status, will likely file for Car Insurance Claims.

**RECOMMENDATIONS**
- **Tailored Policies for Single Individuals and Age Groups 36-55:** Considering that single males and females and people between the ages of 36 to 55 are most likely to file for insurance claims, insurance companies could develop insurance packages tailored explicitly to single individuals' needs. These packages could address the unique risks and concerns that this group may have, potentially offering more competitive rates or coverage options.
- **Engage with Bachelor Degree Holders:** As bachelor degree holders are shown to have the highest number of car insurance claims, insurance companies could engage with this demographic to understand their unique concerns and preferences. This could lead to the development of customized insurance solutions that cater to the needs of individuals with higher education backgrounds.
- **Education and Awareness for Car Models:** Since most car insurance claims are related to incidents involving cars manufactured in the 2000s, insurance companies could proactively educate policyholders about the potential risks associated with these specific car models. This could include sharing information about common issues, maintenance tips, and safety features to help reduce the likelihood of accidents and claims.
- **Tailored Policies for Individuals without Children:** Individuals without children, regardless of marital status, are more likely to file car insurance claims. Insurance companies could design policies that address the needs and preferences of this demographic. These policies offer benefits like lower deductibles, specialized coverage options, or discounts that cater to the specific circumstances of childless individuals.
- **Personalized Communication for Married Individuals:** Insurance companies could create personalized communication campaigns targeting married policyholders because married individuals also file claims quite often. This could include sharing information about family-oriented coverage options, benefits for married couples, and how having dependents might influence their insurance needs.
- **Risk Assessment and Premium Calculation:** While coverage zones and household income do not correlate strongly with car insurance claims, Insurance companies should continue to use a comprehensive approach to assess risk and calculate premiums. These factors may not directly impact claims, but they still play a role in determining a policyholder's overall insurance risk profile.
