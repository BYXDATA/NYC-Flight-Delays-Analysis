# NYC Flight Delay Analysis: Meteorological Impact Study (2013)

## 📊 Project Overview
This project explores the correlation between weather conditions and aviation efficiency at New York City's major airports (JFK, LGA, and EWR). Using the `nycflights13` dataset, I developed an interactive **Tableau** dashboard to analyze how **Visibility** and **Wind Speed** act as predictors for departure delays.

The objective was to identify critical weather thresholds that significantly impact airport throughput and operational punctuality.

---

## Dashboard Preview
<p align="center">
  <img src="https://github.com/user-attachments/assets/b3cc11a5-4d05-4d48-89c5-0a855e37893b" width="828" alt="Dashboard Preview">
  <br>
  <em>Figure 1: Final Interactive Tableau Dashboard.</em>
</p>
---

## 🚀 Key Insights

### 1. Visibility vs. Delay (Inverse Correlation)
* **Trend:** A clear inverse relationship was identified. As visibility decreases, the average departure delay increases.
* **The 5-Mile Threshold:** Data indicates a sharp spike in delays when visibility drops below **5 miles**.
* **Operational Insight:** Low visibility (fog, heavy rain/snow) necessitates increased spacing between aircraft, directly reducing the airport's hourly capacity.

### 2. Wind Speed vs. Delay (Direct Correlation)
* **Trend:** Departure delays show a positive correlation with wind velocity.
* **The 30 MPH Threshold:** Delays remain manageable until wind speeds exceed **30 MPH**, after which they escalate rapidly.
* **Operational Insight:** High winds affect runway selection and crosswind safety limits, leading to proactive ground stops or slowed operations.

---

## Statistical Significance
To ensure the reliability of the findings, the following metrics were analyzed:
* **$p\text{-value} < 0.05$:** The relationships between weather variables and delays are statistically significant, meaning they are not due to random chance.
* **Coefficient of Determination ($R^2 \approx 17\%$):** While weather is a primary factor, 17% of the variance in delays is explained by Visibility and Wind Speed. This highlights the complexity of aviation delays, which are also influenced by air traffic congestion and mechanical factors.

---

## Conclusions
1. **Strategic Planning:** Predicting visibility below 5 miles can serve as a "trigger" for airports to implement early-warning protocols for passengers.
2. **Resource Management:** Tactical staffing should be prioritized when wind forecasts exceed the 30 MPH mark to handle cumulative delays.
3. **Enhanced Modeling:** Future research could integrate "Airport Congestion" data to improve the model's explanatory power beyond 17%.

---

## Tools Used
* **Tableau:** Advanced visualization, trendline modeling, and dashboarding.
* **Dataset:** `nycflights13` (Comprehensive data on NYC flights and weather).

---

## 🔗 Live Interactive Dashboard
Experience the full interactivity, filters, and statistical models here:
👉 **[View Project on Tableau Public](https://public.tableau.com/views/Weather_Delay_Tableau/Dashboard1)**

