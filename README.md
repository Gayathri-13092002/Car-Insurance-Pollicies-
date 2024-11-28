# Car Insurance Policies Dashboard

This repository contains a Power BI dashboard project that analyzes car insurance policies, with a focus on identifying fraudulent claims and exploring key patterns in policy data. 
The dashboard provides actionable insights into customer demographics, claim characteristics, and fraud detection to aid decision-making for insurance providers.

---

## About the Dataset

The dataset consists of car insurance policy details, including customer demographics, policy features, claim history, and fraud indicators.

### **Key Columns in the Dataset**:
- `Policy_ID`: Unique identifier for each policy.
- `Customer_Age`: Age of the insured customer.
- `Gender`: Gender of the customer.
- `Policy_Type`: Type of car insurance policy.
- `Vehicle_Type`: Category of the insured vehicle.
- `Claim_Amount`: Total claim amount requested.
- `Fraud_Reported`: Indicator of whether the claim was fraudulent (Yes/No).
- `Incident_Type`: Type of incident (e.g., collision, theft).
- `Incident_Location`: Location of the reported incident.
- `Claim_Date`: Date of the claim.
- `Policy_Premium`: Premium amount for the policy.

---

## Objectives

1. **Fraud Analysis**:
   - Identify patterns associated with fraudulent claims.
   - Determine high-risk factors for fraud detection.

2. **Customer Insights**:
   - Analyze the demographics of policyholders.
   - Evaluate policy preferences across different customer segments.

3. **Policy Performance**:
   - Investigate the frequency and distribution of claims.
   - Explore relationships between policy attributes and claim likelihood.

4. **Visual Reporting**:
   - Provide interactive and intuitive visualizations for stakeholders.

---

## Tools and Technologies

- **Data Visualization**: Power BI
- **Data Preparation**: Microsoft Excel, SQL
- **Key Techniques**:
  - Heatmaps and histograms for data density and distribution analysis.
  - Filters and slicers for dynamic exploration.
  - KPIs for tracking metrics like total claims and fraud rates.

---

## Dashboard Features

1. **Fraud Detection Dashboard**:
   - Visualizes fraudulent claims by age, gender, and vehicle type.
   - Highlights high-risk zones based on incident location.

2. **Policy Analysis Dashboard**:
   - Displays policy count and premium distribution by type and region.
   - Analyzes average claim amounts across policy types.

3. **Customer Insights Dashboard**:
   - Shows age and gender distribution of customers.
   - Explores customer retention by policy renewal rates.

4. **Trend Analysis Dashboard**:
   - Examines claim trends over time.
   - Identifies peak periods for incidents and claims.

---

## Insights

- Younger customers (aged 18-25) exhibit a higher likelihood of filing fraudulent claims.
- Policies covering high-value vehicles are at greater risk of fraud.
- Theft-related incidents have the highest fraud rates.
- Premiums for urban areas are higher due to an increased risk of incidents.

---

## How to Use

1. Clone this repository:
   ```bash
   git clone https://github.com/Gayathri-13092002/car-insurance-dashboard.git

2. Open the Power BI file (Car_Insurance_Dashboard.pbix) in Power BI Desktop.

3. Ensure the dataset (car_insurance_data.csv) is loaded and correctly linked.

4. Explore the pre-built dashboards and customize them to fit your analysis needs.

## Future Enhancements

1. Integration with real-time data sources for dynamic dashboards.

2. Predictive modeling to forecast fraudulent claims using machine learning.

3. Enhanced geographic analysis using custom maps.

