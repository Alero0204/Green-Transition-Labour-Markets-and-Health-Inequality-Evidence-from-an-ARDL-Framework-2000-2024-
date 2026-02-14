# Green-Transition-Labour-Markets-and-Health-Inequality-Evidence-from-an-ARDL-Framework-2000-2024-
Green Transition, Labour Markets and Health Inequality: Evidence from an ARDL Framework (2000–2024)

📌 Project Overview
This project investigates the long-run relationship between renewable energy transition and social inequality using an Autoregressive Distributed Lag (ARDL) modelling framework.
Using annual time-series data from 2000 to 2024, the study evaluates whether expansion in renewable energy contributes to improvements in social inequality outcomes, while accounting for economic growth, unemployment, and air pollution.
The analysis was conducted using EViews econometric software, applying bounds testing and error-correction modelling techniques.
________________________________________
🎯 Research Question
Does renewable energy expansion reduce social inequality in the long run, or are labour market and economic growth factors more structurally important?
________________________________________
📊 Variables Used
Variable	Description
LNSII	Log of Social Inequality Index (dependent variable)
LNREN_SHARES	Log of Renewable Energy Share
LNGDP_PER_CAPITA	Log of GDP per Capita
UNEMP	Unemployment Rate
PM25	Fine particulate air pollution exposure
All variables were transformed where appropriate to ensure econometric consistency.
________________________________________
⚙️ Methodology
The study follows a structured time-series econometric approach:
1️⃣ Stationarity Testing
•	Augmented Dickey-Fuller (ADF) tests
•	Confirmed mixture of I(0) and I(1) variables
2️⃣ ARDL Bounds Testing
•	Selected model: ARDL(2, 3, 3, 3, 3)
•	Cointegration confirmed via statistically significant error correction term
3️⃣ Long-Run Estimation
Estimated long-run elasticities between renewable transition and inequality.
4️⃣ Error Correction Model (ECM)
Assessed short-run adjustments toward equilibrium.
5️⃣ Pairwise Granger Causality Tests
Evaluated short-run directional relationships.
All estimations were conducted using EViews (2026 version).
________________________________________
Key Empirical Findings
✅ Cointegration Confirmed
The error correction term is negative and statistically significant:
CointEq(-1) = -1.257 (p = 0.012)
This indicates:
•	A stable long-run equilibrium relationship
•	Approximately 126% adjustment within one year
•	Temporary overshooting but rapid system stabilisation
________________________________________
Renewable Energy Transition
•	Positive long-run coefficient (0.11)
•	Statistically insignificant
Interpretation:
Renewable energy expansion alone does not automatically reduce inequality within the sample period.
________________________________________
📈 Economic Growth (GDP per Capita)
•	Negative and economically meaningful coefficient
•	Moderately strong statistical evidence
Interpretation:
Economic growth significantly reduces inequality-related outcomes in the long run.
________________________________________
👥 Unemployment
•	Negative and statistically significant
Interpretation:
Higher unemployment structurally worsens inequality outcomes. Labour market instability is a key driver of social disparities.
________________________________________
PM2.5 (Air Pollution)
•	Negative but statistically insignificant
Interpretation:
Pollution effects may operate through short-run health shocks rather than persistent structural inequality.
________________________________________
🔁 Granger Causality Results
No short-run causal relationships were detected among renewable energy, GDP per capita, unemployment, pollution, and inequality.
This suggests that green transition impacts on inequality operate through long-term structural mechanisms rather than immediate short-run dynamics.
________________________________________
🏛 Policy Implications
The findings suggest that:
•	Green transition alone is insufficient to reduce inequality.
•	Economic growth remains a critical driver of improved social outcomes.
•	Labour market stability plays a decisive role.
•	Just transition policies are essential to prevent inequality deepening.
For the green transition to be socially inclusive, it must be accompanied by:
•	Active labour market policies
•	Skills retraining programmes
•	Social protection mechanisms
•	Inclusive economic planning
________________________________________
📁 Repository Structure
green-transition-inequality-ardl/
│
├── data/
│   ├── raw_data.csv
│   ├── cleaned_data.csv
│
├── eviews_output/
│   ├── ardl_results.txt
│   ├── granger_results.txt
│
├── figures/
│   ├── time_series_trends.png
│   ├── coefficient_plot.png
│
├── report/
│   ├── Green_Transition_Inequality_Report.pdf
│
└── README.md
________________________________________
Skills Demonstrated
•	Time-Series Econometrics
•	ARDL Modelling
•	Cointegration Analysis
•	Error Correction Modelling
•	Granger Causality Testing
•	Policy Interpretation
•	Applied Health & Inequality Economics
•	EViews Econometric Software
________________________________________
Contribution
This project contributes to the growing debate on whether environmental sustainability policies automatically generate inclusive social outcomes.
The results suggest that without labour market and redistributive policies, the green transition may not significantly reduce inequality.
________________________________________
📚 Future Extensions
•	Structural break analysis
•	Sectoral employment decomposition
•	Regional inequality comparisons
•	Health outcome interaction models
•	Comparative UK vs international analysis
________________________________________
👤 Author
Michael Eji
Econometrics | Health Research | Public Policy Analytics
Interested in quantitative roles within:
•	Public Health Analytics
•	NHS Data & Intelligence
•	Health Economics
•	Sustainability Policy Analysis


