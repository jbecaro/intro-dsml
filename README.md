<< Passenger Demand Forecasting for Winnipeg Transit using LSTM >>

This project explores Winnipeg Transit passenger demand and aims to develop an LSTM-based forecasting model to predict future passenger demand. The goal is to support transit planning by helping identify when and where bus capacity may be needed based on historical passenger patterns.

The project begins with exploratory data analysis and will progress toward data preparation, Python-based analysis, and LSTM model development.

I. Project Objectives

- Explore historical Winnipeg Transit passenger activity.
- Identify patterns in passenger boardings and alighting.
- Examine how passenger demand relates to location, day type, time period, and schedule period.
- Prepare transit data for time-series forecasting.
- Develop an LSTM model for passenger-demand forecasting.
- Provide information that could support future transit planning and resource allocation.

*The AI predicts. The manager decides.*

The forecasting model is intended as a decision-support tool. Its predictions do not automatically determine bus allocation or service changes.

II. Data Source

The project uses passenger activity data from the City of Winnipeg Open Data Portal, including Winnipeg Transit's Estimated Boarding data.

The data is used under the Open Government Licence – Winnipeg.

Contains information licensed under the Open Government Licence – Winnipeg.

III. Data Notes

Hi, this is your author, Jovan Becaro.

The last account in the Estimated Data Boarding data is June 20, 2026.

Important Notes

For `x` and `y`: SELECT "x", "y" FROM stop_locations.csv WHERE "Stop Number" = stop_number;
For `schedule_period`: SELECT "Schedule Period" FROM schedule_periods.csv WHERE "Schedule Period Name" = schedule_period_name;
For `time_code`: SELECT "Time Code" FROM time_codes.csv WHERE "Time Period" = time_period;

These supporting datasets are used to connect the original transit data with the corresponding location, schedule period, and time-code information.

IV. Tools and Technologies

Current and planned tools include:

- Python
- pandas
- DuckDB
- Orange Data Mining
- LSTM / Deep Learning
- Git & GitHub

Additional Python libraries and technologies will be documented as the project progresses.

V. Author

Jovan Kashmir "Jovski" Palma Becaro

Applied Data Science and Artificial Intelligence student.
