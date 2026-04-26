\# Machine Learning Analysis of Child Malnutrition in Rural Uttar Pradesh



\## Overview



This project analyzes the impact of environmental and socioeconomic factors on child malnutrition across rural districts of Uttar Pradesh using machine learning techniques.



The study demonstrates that socioeconomic variables such as women's education, electricity access, and clean fuel usage have a stronger influence on malnutrition outcomes than environmental factors.



\---



\## Objectives



\* Compare environmental vs socioeconomic predictors

\* Build predictive ML models (Random Forest, XGBoost, LightGBM)

\* Identify key drivers of malnutrition

\* Perform feature importance and error analysis



\---



\## Dataset



\* Source: NFHS-5 (2019–2021)

\* Region: Rural Uttar Pradesh (75 districts)

\* Features:



&#x20; \* Sanitation

&#x20; \* Electricity

&#x20; \* Drinking Water

&#x20; \* Clean Fuel

&#x20; \* Women Education



\---



\## Models Used



\* Random Forest Regressor

\* XGBoost

\* LightGBM



\---



\## Results



\* Baseline Model (Environmental): R² ≈ -0.24

\* Improved Model (Socioeconomic): R² ≈ 0.457

\* Optimized Model: R² ≈ 0.489



\---



\## Key Insights



\* Women's education is the most significant predictor

\* Infrastructure strongly influences nutrition outcomes

\* Environmental data lacks district-level variability



\---



\## Project Structure



```

data/

notebooks/

outputs/

README.md

```



\---



\## How to Run



1\. Clone the repo:



```

git clone https://github.com/yourusername/malnutrition-ml-up.git

```



2\. Install dependencies:



```

pip install -r requirements.txt

```



3\. Run the notebook:



```

jupyter notebook

```



\---



\## Future Work



\* Dashboard (Streamlit)

\* Geospatial visualization

\* Village-level analysis



\---



\## Author



Shimon Aalam

B.Tech IT, Manipal University Jaipur

Research Intern, IIIT Allahabad



