# Combined Cycle Power Plant Energy Output Prediction

## Dataset Overview

The dataset contains 9568 data points collected from a Combined Cycle Power Plant over 6 years (2006-2011) when the plant was set to work at full load. The features include hourly average ambient variables such as Temperature (T), Ambient Pressure (AP), Relative Humidity (RH), and Exhaust Vacuum (V), which are used to predict the net hourly electrical energy output (EP) of the plant.

## Combined Cycle Power Plant (CCPP) Background

A CCPP consists of gas turbines (GT), steam turbines (ST), and heat recovery steam generators. Electricity is generated through combined gas and steam turbines operating in a cycle. The Vacuum primarily impacts the Steam Turbine, while the other ambient variables influence GT performance.

## Model Overview

I built an artificial neural network to predict the electrical energy output using the provided dataset. The model's performance metrics are as follows:

- Mean Squared Error (MSE): 29.707884933882323
- R2 Score: 0.8984303573416723

## Relevant Papers

- Pınar Tüfekci, "Prediction of full load electrical power output of a base load operated combined cycle power plant using machine learning methods", International Journal of Electrical Power & Energy Systems, Volume 60, September 2014.
- Heysem Kaya, Pınar Tüfekci, Sadık Fikret Gürgen: "Local and Global Learning Methods for Predicting Power of a Combined Gas & Steam Turbine", Proceedings of the International Conference on Emerging Trends in Computer and Electronics Engineering ICETCEE 2012.

## Conclusion

Through this project, I aimed to predict the electrical energy output of a Combined Cycle Power Plant using machine learning techniques. The results achieved demonstrate the model's ability to accurately predict energy output, which can contribute to optimizing power plant operations and energy efficiency.

[Dataset Source](https://archive.ics.uci.edu/ml/datasets/Combined+Cycle+Power+Plant)
