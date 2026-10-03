# Steel-Properties-Data-Analysis
This project analyzes a dataset of 3,234 steel observations containing chemical composition, processing conditions, and mechanical properties.
The goal is to explore how steel composition and other measured properties relate to yield strength, while demonstrating a practical data-analysis workflow using Python, pandas, and SQL.
The analysis includes data cleaning, exploratory data analysis, visualization, correlation analysis, and SQL queries to examine patterns in the dataset.

Key Findings
Carbon content showed a very weak linear correlation with yield strength (r ≈ 0.055), indicating that carbon content alone does not explain much of the variation in yield strength in this dataset.
Yield strength and ductility showed a moderate negative correlation (r ≈ -0.605), with higher-strength steels generally showing lower ductility.
The yield strength distribution was concentrated below approximately 1,250 MPa, with a small number of observations above 2,000 MPa. These high-strength observations were retained because they appeared to represent legitimate steel grades rather than obvious data errors.
Among steel grades with at least 10 observations, 18Ni (250) and 18Ni (200) Maraging Steels had the highest average observed yield strengths.
390 observations, or 12.06% of the dataset, had yield strengths above 1,000 MPa.
The dataset contains substantially different numbers of observations for different steel grades, which was considered when comparing group averages.
