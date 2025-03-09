# R-Data-Analytics-Project-Covid-India-Statewise-Vaccine

I developed a comprehensive interactive dashboard in R-Studio using R and an Excel dataset to analyze state-wise COVID-19 vaccination trends. The project involved data preprocessing, cleaning, and visualization, featuring dose comparisons, booster coverage, age-wise trends, and key insights using ggplot2, Plotly, and Flexdashboard.

# Covid India Statewise Vaccine Data Analysis Dashboard 
## Interactive Dashboard creation using R language

## Project Objective

The objective of this project is to analyze COVID-19 vaccination data across Indian states and Union Territories. The analysis aims to provide insights into vaccination coverage, dose distribution, and booster dose uptake. By visualizing trends and patterns, the dashboard helps stakeholders understand progress, identify gaps, and optimize vaccination strategies.

## Dataset used
- <a href="https://github.com/satishrdudhat/R-Data-Analytics-Project-Covid-India-Statewise-Vaccine/blob/main/COVID-19%20India%20Statewise%20Vaccine%20Data.csv">View Dataset</a>

## Key Questions (KPIs)

1.	Total Vaccination Trends
    - How many total doses have been administered across India?
    - Which states have the highest and lowest vaccination rates?
      
2.	Dose-1 vs Dose-2 Coverage
    - How does Dose-1 coverage compare to Dose-2 across states?
    - What percentage of the population is fully vaccinated?
      
3.	Booster Dose Administration
    - What is the distribution of precautionary (booster) doses across different states?
    - Which states have the highest and lowest booster dose coverage?
      
4.	Age-wise Vaccination Patterns
    - How does vaccination coverage vary across different age groups (12-14 and 15-18 years)?
      
5.	State-wise Performance
    - Which are the top-performing states in terms of vaccination coverage?
    - Which states need policy interventions to improve coverage?

## Dashboard Interaction 
 <a href="https://github.com/satishrdudhat/R-Data-Analytics-Project-Covid-India-Statewise-Vaccine/blob/main/Screenshot%20(8015).png">View Dashboard One</a></br>
 <a href="https://github.com/satishrdudhat/R-Data-Analytics-Project-Covid-India-Statewise-Vaccine/blob/main/Screenshot%20(8016).png">View Dashboard Second</a></br>
 <a href="https://github.com/satishrdudhat/R-Data-Analytics-Project-Covid-India-Statewise-Vaccine/blob/main/Screenshot%20(8017).png">View Dashboard Third</a>

 ## Process
 
1.	Data Collection & Cleaning:
    - Imported state-wise COVID-19 vaccination data in CSV format.
    - Replaced missing values with zero to ensure data consistency.
  	
3.	Feature Engineering:
    - Created new metrics such as Vaccination Coverage %, Fully Vaccinated %, and Booster Coverage %.
    - Filtered the top and bottom 5 states based on full vaccination percentage.
  	
5.	Visualization & Analysis:
    - Scatterplot & Bar Charts: Show overall vaccination progress per state.
    - Stacked Bar Charts: Display vaccination trends by age group.
    - Pie Chart: Represents the proportion of precautionary doses administered.
    - Interactive Tooltips: Allow users to explore data dynamically.

## Dashboard
Dashboard One
![Screenshot (8015)](https://github.com/user-attachments/assets/53107aa6-2a06-492f-b35a-343470a34980)  <br>
Dashboard Second
![Screenshot (8016)](https://github.com/user-attachments/assets/717d86c0-44ec-45fb-a91b-9f80b0fc7f86)  <br>
Dashboard Third
![Screenshot (8017)](https://github.com/user-attachments/assets/906dfd20-37e0-46c1-a290-d0f6e442ac43)  

## Project Insights

1.	Overall Vaccination Coverage:
    - India has administered a significant number of COVID-19 vaccine doses.
    - Some states have a much higher vaccination rate compared to others.
      
2.	Dose-1 vs Dose-2 Gap:
    - Several states show a large gap between Dose-1 and Dose-2 administration, indicating a need for awareness campaigns to ensure full vaccination.
      
3.	Booster Dose Challenges:
    - The uptake of precautionary (booster) doses is lower than expected in many states.
    - States with higher precautionary dose coverage have likely implemented better awareness programs.
      
4.	Age-wise Disparities:
    - The vaccination rate among younger populations (12-18 years) varies significantly between states.
    - Some states lag in vaccinating school-aged children, which may affect herd immunity.
      
5.	Top & Bottom Performing States:
    - States with high population density often show both high vaccination numbers and significant gaps in booster dose coverage.
    - Low-performing states require targeted interventions to increase vaccine adoption.

## Final Conclusion

The vaccination rollout in India has been largely successful, but disparities exist across states. While some states have achieved high vaccination coverage, others still need targeted efforts to improve dose completion rates and booster uptake. Interactive visualizations provide a deeper understanding of regional trends, enabling policymakers to make data-driven decisions to enhance COVID-19 vaccine outreach and public health impact.






