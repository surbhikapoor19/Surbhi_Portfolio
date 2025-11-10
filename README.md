# Surbhi Kapoor's Portfolio
- Data Science and Machine Learning Project contributed and/or built out by me.
- All projects are primarily built out in Python and SQL.



## [Mental Health Risk Prediction: NHIS Analysis](https://github.com/surbhikapoor19/nhis_mental_health_survey)
**Research Question:** Can a machine learning model using baseline demographic, behavioral, and social factors predict future psychological distress (K6 ≥ 5) with ≥70% accuracy, and identify the most important modifiable risk factors for early intervention?
Dataset: 2024 National Health Interview Survey (NHIS) from the CDC's National Center for Health Statistics

32,629 adult participants
630 variables covering demographics, health behaviors, chronic conditions, and mental health indicators
Target: K6 psychological distress score (Kessler-6 scale)

**Approach:**

- _Data Engineering:_ Built a custom parser to convert 630 cryptic variable codes from the NHIS codebook into human-readable features for interpretability
- _Feature Engineering:_ Created binary at-risk classification (K6 ≥ 5) and conducted comprehensive exploratory analysis to identify patterns in demographic, behavioral, and social factors
- _Modeling:_ Developed two Random Forest classifiers:
  - Binary model predicting at-risk vs. not at-risk status;
  - Multi-class model predicting exact K6 scores (0-24) for severity profiling

**Results:**

Achieved 85-90% accuracy, exceeding the 70% target
Successfully identified at-risk individuals using only accessible survey data (no medical tests required)
Extracted interpretable feature importance rankings to guide early intervention strategies
Demonstrated that psychological distress can be predicted from readily available demographic and behavioral information

**Impact:** This work provides a practical framework for mental health screening programs using accessible data points, enabling early identification and personalized preventative care without requiring invasive testing or extensive medical history.

<img src=/images/mental_health_eda.png width="75%"></img> 
------------

## [Assessing Underserved Regions (using ML) - NYC Transit System](https://github.com/We-Gold/ds-501-cs4-public)
In this project, we identified areas in New York City (NYC) that are underrepresented in transit accessibility. We wanted to understand areas of opportunity (defined as currently underserved areas where we predict people would have high public transportation usage) where the MTA could create a transit station that we believe will receive a lot of foot traffic and ticket sales.

To solve this problem, we determined the average distance to a transit station from areas all over NYC. We then determined if the area is worth investing in (would a transit station here be profitable?) by looking at predicted ridership. Each subway ride in NYC earns $2.90 per ride per person (https://www.mta.info/fares-tolls/subway-bus), and since we can predict weekly ridership, we will predict weekly revenue based on that predicted ridership.

Our data science approach will not only enable us to identify underserved areas but also to predict ridership for these areas. The resulting decision-making platform will enable the MTA to more readily evaluate potential locations for transit stops/stations rather than having to manually sort through all options.


<img src=/images/nyc_project_areas_of_opportunity.png width="75%"></img> 
<!--
Source - https://stackoverflow.com/a
Posted by Tieme, modified by community. See post 'Timeline' for change history
Retrieved 2025-11-07, License - CC BY-SA 4.0
-->
-------

## [WPI Greenboard - Carbon Emission Visibility](https://github.com/We-Gold/wpi-greenboard)
A full-stack carbon emissions tracking system for Worcester Polytechnic Institute that quantifies the environmental impact of campus package deliveries through multi-carrier API integration and intelligent emissions calculations.

**My Contributions**: Collaborated on database architecture design and implementation using PostgreSQL with SQLModel ORM. Built the complete emissions calculation stack with speed-based emission factors (0.062-0.82 kg CO2e per tonne-km) and integrated multiple shipping carrier APIs (UPS, FedEx, USPS, DHL) using modular adapter patterns to normalize disparate response formats. Optimized processing performance from 1 to 12-14 packages/second through concurrent processing with ThreadPoolExecutor and intelligent geocoding caching strategies. Developed SQLModel-based FastAPI endpoints powering frontend data queries and visualization.

Technologies: Python, FastAPI, PostgreSQL, SQLModel, Multi-Carrier APIs, Concurrent Processing
<img src=/images/package_details_greenboard.png width="45%"></img> <img src=/images/leaderboard_greenboard.png width="45%"></img> 

