# Financial Planning (using API)
### Homework Assignment: Financial Planning By: Ebad Salehi

![logo](images/logo.jpg)

### Scenario:
- Via my new FinTech consultancy firm, I have acquired a project through a credit union as my first stakeholder.
- The project is to develop tools to help their customers enhance their financial health.

- The **1st tool** is a "personal finance planner" that will allow users to visualize their savings composed by investments in shares and cryptocurrencies to assess if they have enough money as an emergency fund.

- The **2nd tool** is a "retirement planning tool" that will use the Alpaca API to fetch historical closing prices for a retirement portfolio composed of stocks and bonds, then run Monte Carlo simulations to project the portfolio performance at 30 years. Then using the Monte Carlo data to calculate the expected portfolio returns given a specific initial investment amount.
- Generate a retirement planner including optional analysis for different investment timeframes.
- Bonus section: analysis for early retirement planner by changing bond and stock compositions.

---
### Example of Cahrt Outputs

![image_add](images/personal_Savings_composition.png)


![image_add](images/distribution_500.png)


![image_add](images/30_years.png)


![image_add](images/returns_plot.png)

---
## Challenge: Early Retirement

These results show that those with a high risk preference have the potential  to retire early with a higher stock to bond ratio and a more significant initial investment. 
![image_add](images/60K_10_Years.png)

---
### This Project Built Using:

* Python (Jupyter-lab: alpaca environment)
* pandas
* alpaca
* matplotlib
* MCForecastTools (Monte Carlo)
---

### Resources:

Two APIs utilized in this project:

* The **Alpaca Markets API** is used to pull historical stocks and bonds information.  
    
* The **Alternative Free Crypto API** is used to retrieve Bitcoin and Ethereum prices.

Documentation for these APIs:

* [Free Crypto API Documentation](https://alternative.me/crypto/api/)

* [AlpacaDOCS](https://alpaca.markets/docs/)


