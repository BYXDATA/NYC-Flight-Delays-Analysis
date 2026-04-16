## NYC Flight Delay Analysis: Weather Impact Study

**Project Overview**
This project explores the correlation between weather conditions and aviation efficiency at NYC's major airports (JFK, LGA, and EWR). Using the `nycflights13` dataset and **Tableau**, I identified critical weather thresholds that impact operational punctuality.


**Dashboard Preview**

<img src="https://github.com/user-attachments/assets/b3cc11a5-4d05-4d48-89c5-0a855e37893b" width="700">


*Figure 1: Interactive Tableau Dashboard analyzing flight delays.*


**Key Insights**
* **Visibility Threshold:** A significant spike in delays occurs when visibility drops below **5 miles**. 
* **Wind Speed Threshold:** Delays escalate rapidly once wind speeds exceed **30 MPH**.
* **Correlation:** Visibility shows an inverse relationship with delays, while wind speed shows a direct positive correlation.


**Statistical Significance**
* **p-value < 0.05:** Confirms the relationships are statistically significant.
* **R² ≈ 17%:** Indicates that 17% of delay variance is explained by these two weather factors.


**Conclusions**
1. **Strategic Triggers:** Use "Visibility < 5 miles" as a benchmark for early passenger notification.
2. **Resource Management:** Prioritize tactical staffing during wind forecasts > 30 MPH.
3. **Future Scope:** Integrating airport congestion data could further refine predictive power.


**Tools & Links**
* **Tools:** Tableau, Excel, `nycflights13` dataset.
* **Live Dashboard:** [View on Tableau Public](https://public.tableau.com/views/Weather_Delay_Tableau/Dashboard1)

