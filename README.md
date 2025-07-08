# 🏥 Health Risk Prediction Dashboard (Power BI + Python Visuals)

This interactive Health Risk Dashboard analyzes patient-level health data to identify individuals at higher risk based on key health indicators such as BMI, blood pressure, glucose levels, age, and diabetes status.

## 📊 Key Features

- ✅ Total Patients Tracked
- ✅ Average BMI and Glucose
- ✅ High-Risk Patient Percentage
- ✅ Diabetes Prevalence Rate
- ✅ Risk Level Breakdown by Blood Pressure
- ✅ Gender Distribution of Risk Levels
- ✅ Python Visual: BMI Density Plot by Risk Category

## 🐍 Python Integration

This report includes a Python-based visual using the `seaborn` library to plot a **BMI density curve**, grouped by risk level. This statistical visualization adds insight beyond standard bar or pie charts and demonstrates advanced analytical capabilities.

```python
import seaborn as sns
import matplotlib.pyplot as plt

sns.kdeplot(data=dataset, x="BMI", hue="Risk_Level", fill=True)
