# Decentralization-of-Energy-Using-PV-Batteries
#  PV + Battery Optimization with Services & Load Shifting  

##  Problem Statement  
Solar (PV) installations often face challenges such as **curtailment (wasted energy)**, high dependency on the grid during peak demand, and poor economic returns. Batteries, demand shifting, and value-added services can address these — but **choosing the right strategy and battery size is complex**.  

This project builds a **data-driven optimization framework** to compare baseline, PV-only, and PV+Battery+Services+Load Shift scenarios.  

---

##  Concept Behind the Project  
We combine **solar PV generation, battery storage, demand-shift strategies, and service participation** into one framework:  

- **PV-only**: Store solar energy and reduce bills.  
- **PV + Grid + Services**: Use batteries for energy arbitrage, demand reduction, and grid services.  
- **Machine Learning Forecasting**: Anticipates next-day load, solar, and prices to guide charging/discharging.  
- **Optimization**: Minimizes total cost while maximizing savings and service revenues.  

---

##  Approach  
1. **Data Preparation**  
   - Baseline demand and billing structure.  
   - PV generation forecasts.  
   - Tariff & price curves.  

2. **Simulation**  
   - Run scenarios (baseline, PV, PV+Services+Shift).  
   - Vary battery size (50–300 kWh).  
   - Track energy throughput, degradation, curtailment avoided, and costs.  

3. **Decision Algorithm**  
   - Identify cheapest hours to **charge** (when solar surplus or low prices).  
   - Identify peak hours to **discharge** (when demand & price are high).  

4. **Evaluation**  
   - Compare strategies across cost, savings, revenues, and sustainability metrics.  

---

##  Challenges  
- Balancing between **higher battery degradation** and **service revenues**.  
- Accurate **forecasting** of PV, load, and prices.  
- Trade-offs between **battery size vs. curtailment vs. savings**.  
- Scalability to community microgrids.  

---

##  Results (Highlights)  
- **PV-only best case (300 kWh / 150 kW):**  
  - Total Cost: ₹83,186  
  - Savings: ₹43,797  
  - Curtailment avoided: ~2,230 kWh  

- **PV + Services + Load Shift (300 kWh / 150 kW):**  
  - Total Cost: ₹84,027  
  - Savings: ₹42,955  
  - Service Revenue: ₹54,201  
  - Higher degradation due to aggressive cycling.  

 **Insight:** While PV-only shows higher *direct savings*, PV+Services unlocks **extra revenue potential** but with increased battery wear.  

---

##  Scalability to Community Microgrids  
- Pooling multiple households → **shared battery bank**.  
- Coordinated services → **greater service revenue**.  
- Reduced curtailment at community scale.  
- Stronger case for **AI-driven optimization** at neighborhood level.  

---

##  Repository Structure  
