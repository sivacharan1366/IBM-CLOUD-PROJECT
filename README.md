# IBM-CLOUD-PROJECT
 Analyzing Demographic and Regional Disparities in TeleLaw Case Registrations for Inclusive Legal Access

 Analysis of Demographic and Regional Disparities in Tele-Law Case Registrations
Overview
This project is a capstone data analysis of the "District-wise Tele-Law Case Registration" dataset from India's Open Government Data Platform. The primary goal is to analyze and visualize demographic and geographic disparities in the utilization of the Tele-Law service, an initiative aimed at providing legal aid to citizens through Common Service Centres (CSCs). The analysis is performed using Python in a Jupyter Notebook hosted on IBM Cloud.

Problem Statement
Despite the expansion of the Tele-Law initiative, there is a limited understanding of its utilization patterns across different demographics and regions. This project addresses the challenge of analyzing case registration data to uncover gender-wise, caste-wise, and geographic disparities. The findings aim to provide data-driven insights to evaluate the program's inclusivity and help optimize its service delivery for more equitable legal access.

Key Features & Analysis
Gender-wise Disparity Analysis: Calculates and visualizes the distribution of cases between male and female beneficiaries to identify any gender gap in service access.

Caste-wise Disparity Analysis: Examines the representation of various caste categories (General, OBC, SC, ST) among the beneficiaries to assess the program's reach within marginalized communities.

Geographic Disparity Analysis: Aggregates data at the state level to identify regional trends. This includes:

Ranking states by the total number of registered cases.

Visualizing the concentration of cases across India using a choropleth map.

Calculating a "cases per CSC" metric to allow for fair comparisons between states with different numbers of service centers.

Technology Stack
Cloud Platform: IBM Cloud

Development Environment: Jupyter Notebook

Programming Language: Python

Core Libraries:

Pandas: For data ingestion, cleaning, and aggregation.

Matplotlib & Seaborn: For creating pie charts and bar graphs.

Geopandas: For generating the choropleth map of India.

Visualizations Produced
Pie Chart: Overall Gender-wise Distribution of Cases.

Pie Chart: Overall Caste-wise Distribution of Cases.

Bar Chart: Top 15 States by Total Case Registrations.

Choropleth Map: Tele-Law Case Registrations Across India.

How to Run the Analysis
Prerequisites: Ensure you have a Python environment with the libraries listed in the Technology Stack installed.

Dataset: Place the DistrictswiseCR_AEdataf_24-25.csv file in the same directory as the Jupyter Notebook.

Execute Notebook: Open and run the .ipynb file in a Jupyter environment. The notebook will perform the complete analysis and generate all visualizations.

Results & Conclusion
The analysis successfully highlights significant disparities in service utilization. Key findings include a notable gender gap favoring male beneficiaries, a high concentration of service uptake in a few states, and a need for potentially more targeted outreach to ST communities. These insights can be instrumental for policymakers in formulating strategies to enhance the inclusivity and effectiveness of the Tele-Law program.
