🔋 Battery Remaining Useful Life (RUL) Prediction



📋 Project Overview
This project predicts the Remaining Useful Life (RUL) of lithium-ion batteries based on cycling features engineered from experimental data.
It uses machine learning models to understand battery degradation patterns and estimate how many cycles a battery can last.

📚 Dataset
Source: Battery RUL Prediction Dataset

Batteries: 14 x NMC-LCO 18650 cells (2.8 Ah nominal)

Conditions:

1000 cycles at 25°C

C/2 rate charging (CC-CV)

1.5C rate discharging

Features:

Feature	Description
Cycle Index	Number of charge/discharge cycles
F1	Discharge Time (s)
F2	Time at 4.15V (s)
F3	Time under Constant Current (s)
F4	Time for voltage drop from 3.6V to 3.4V (s)
F5	Max Voltage during Discharge (V)
F6	Min Voltage during Charge (V)
F7	Charging Time (s)
Total Time	Total operation time per cycle (s)
RUL	Remaining Useful Life (Target)

🎯 Goals
Predict RUL using engineered features

Analyze key drivers of battery aging

Develop a reproducible model pipeline
 
