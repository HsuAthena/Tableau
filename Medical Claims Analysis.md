# Medical Claims Analysis
This dataset, sourced from a medical claim data analysis study, includes columns for Payer, Service, Age Group, Gender, Year, and Cost. It provides a comprehensive view of healthcare expenditures segmented by payer type, service type, age group, and gender across multiple years.


<img src="https://github.com/HsuAthena/Tableau/blob/main/Image/Medical%20Claims%20Analysis%20Dashboard.png" alt="Trends in Healthcare Costs Dashboard">

Filters:
Payer
Service
Age Group
Year

Top: "Costs by Payer"  Line Chart
To show the trends in healthcare costs over time, broken down by different payers.
Costs for Private Health Insurance are the highest and show a consistent upward trend.
Medicaid and Medicare costs also increase steadily over time.
Out of Pocket and Other Payers and Programs have lower costs but show an increasing trend as well.

Middle: "Costs by Services": Line Chart
To show the trends in healthcare costs by different types of services over time. Each line represents a different type of service, including Dental Services, Durable Medical Equipment, Home Health Care, Hospital Care, and more.
Hospital Care has the highest costs and the most significant growth, followed by Prescription Drugs and Physician and Clinical Services.

Button:"Cost by Age" Line Chart
To illustrate the healthcare costs trends for different age groups over time.
The 19-64 age group incurs the highest healthcare costs, followed by the 65+ age group, with both showing significant upward trends. The 0-18 age group has the lowest costs but still shows an increase over time.




<img src="https://github.com/HsuAthena/Tableau/blob/main/Image/Medical%20Claims%20Healthcare%20Costs%20by%20Payer%2C%20Age%20Group%2C%20and%20Gender%20Over%20Time.png" alt="Small Multiples">

The graphs above, "Costs by Payer" and "Costs by Services" give a high level of view of costs, but do not show any relationship between gender and age groups. Small multiples multi-line chart graph can encode additional variables. Each small multiple (individual chart) represents a specific payer category and shows the cost trends over time for different age groups. The lines in each chart differentiate costs between males and females.

Small multiples visualize the distribution and trends of healthcare costs across different payer categories, segmented by age group and gender. It aims to provide insights into how costs vary over time for various demographics, helping us understand cost patterns and identify areas for further investigation or intervention.

Medicaid: Costs for both genders are increasing steadily across all age groups. Males have slightly higher costs than females in the 0-18 age group.
Medicare: There is a significant rise in costs for the 65+ age group. For the 0-64 age group, both genders exhibit similar trends.
Other Payers and Programs: Costs increase gradually over time.
Out of Pocket: Costs increase gradually over time.
Private Health Insurance: There is a significant increase in costs in the 19-64 and 65+ age groups.


This graph effectively demonstrates the rising trend of healthcare costs across various payer categories, age groups, and genders. It highlights the areas where costs are increasing the most, such as Medicare for the elderly (65+) and private health insurance for middle-aged individuals (19-64). Gender differences are also evident, with females usually having equal or higher costs than males. Females tend to have higher costs in specific age groups and payer categories. This information can be crucial for policymakers, healthcare providers, and insurance companies to develop strategies for managing healthcare costs and addressing disparities.