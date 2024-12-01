# Project Description: User Engagement Simulation
This repository contains a Python script for simulating user engagement metrics. The code generates realistic retention, churn, and premium conversion data, along with lessons completed by users of varying skill levels.

## Key Features:
- Lessons Completed Simulation:

## Generates the number of lessons completed by users based on their skill levels (Beginner, Intermediate, Advanced).
- Applies normal distributions with skill-level-specific means and standard deviations for variability.
- Identification of Power and Idle Users:

## Power Users: 
- Representing 1% of the user base, these users are assigned significantly higher lesson counts (randomly increased by 10–50 lessons).
## Idle Users: 
- Representing 15% of the user base, these users complete fewer lessons (0–3 randomly assigned lessons).
Reproducibility:

### The code ensures reproducibility by using a fixed random seed (np.random.seed), producing consistent outputs across iterations.
Customization:

- The script allows for easy customization of the simulation parameters, such as skill-level distributions, power user proportions, and idle user thresholds.
### Example Use Case:
- The generated dataset can be used for:

  - Training machine learning models for engagement prediction.
  - Conducting exploratory data analysis (EDA) to identify user behavior patterns.
  - Simulating A/B testing scenarios to evaluate retention and conversion strategies.
