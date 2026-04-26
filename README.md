# Machine Learning Analysis of Child Malnutrition in Rural Uttar Pradesh

---

## Overview

This project analyzes the impact of environmental and socioeconomic factors on child malnutrition across rural districts of Uttar Pradesh using machine learning techniques.

The study demonstrates that socioeconomic variables such as women's education, electricity access, and clean fuel usage have a stronger influence on malnutrition outcomes than environmental factors.

---

## Objectives

* Compare environmental and socioeconomic predictors
* Build predictive machine learning models (Random Forest, XGBoost, LightGBM)
* Identify key drivers of malnutrition
* Perform feature importance and error analysis

---

## Dataset

* Source: National Family Health Survey (NFHS-5), 2019–2021
* Region: Rural Uttar Pradesh (75 districts)

### Features

* Sanitation
* Electricity
* Drinking Water
* Clean Fuel
* Women Education

---

## Models Used

* Random Forest Regressor
* XGBoost
* LightGBM

---

## Results

| Model               | R² Score | RMSE | Status   |
| ------------------- | -------- | ---- | -------- |
| Environmental Only  | -0.24    | 11.2 | Failed   |
| Socioeconomic Model | 0.457    | 3.7  | Improved |
| Optimized Model     | 0.489    | 3.59 | Best     |

---

## Key Insights

* Women’s education is the most significant predictor
* Infrastructure strongly influences nutrition outcomes
* Environmental data lacks district-level variability

---

## Project Structure

```
malnutrition-ml-up/
│
├── notebooks/
├── data/
├── outputs/
├── README.md
```

---

## How to Run

```
git clone https://github.com/yourusername/malnutrition-ml-up.git
cd malnutrition-ml-up
pip install -r requirements.txt
jupyter notebook
```

---

## Future Work

* Dashboard development (Streamlit)
* Geospatial visualization
* Risk classification system

---

## Author

Shimon Aalam
B.Tech Information Technology, Manipal University Jaipur
Research Intern, IIIT Allahabad
