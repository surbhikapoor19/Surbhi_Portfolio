# Surbhi Kapoor
## Overview 
Hi:) I am a Data Scientist currently pursuing my Masters in Data Science. I have worked in the industry for 6+ years - multitasking but mostly building out ML pipelines from ideation to deployment. I have worked with various libraries and suplement database related work with SQL. 

My work involes:
  - Fine tuning transformer
  - Setting up AI workflows using various state of the art APIs across various proiders
  - Building and tuning statistical and other machine learning models and their pipelines
  - Carrying out data analysis, reporting and inferences on variety of datasets
  - Building out visualizations, business intelligence dashboards and model performance dashboards
    
Currently I am thoroughly enjoying being in the academic space and learning, researching as well as experimenting to my hearts content. I enjoy challenges and am always looking to problem solve in creative and  efficent ways. 

- Data Science and Machine Learning Project contributed and/or built out by me.
- All projects are primarily built out in Python and SQL.


## Research Projects / Apps (Academic)
### [Mental Health Risk Prediction: NHIS Analysis](https://github.com/surbhikapoor19/nhis_mental_health_survey)
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

![mental_health_eda](/images/mental_health_eda.png)


### [Assessing Underserved Regions (using ML) - NYC Transit System](https://github.com/We-Gold/ds-501-cs4-public)
In this project, we identified areas in New York City (NYC) that are underrepresented in transit accessibility. We wanted to understand areas of opportunity (defined as currently underserved areas where we predict people would have high public transportation usage) where the MTA could create a transit station that we believe will receive a lot of foot traffic and ticket sales.

To solve this problem, we determined the average distance to a transit station from areas all over NYC. We then determined if the area is worth investing in (would a transit station here be profitable?) by looking at predicted ridership. Each subway ride in NYC earns $2.90 per ride per person (https://www.mta.info/fares-tolls/subway-bus), and since we can predict weekly ridership, we will predict weekly revenue based on that predicted ridership.

Our data science approach will not only enable us to identify underserved areas but also to predict ridership for these areas. The resulting decision-making platform will enable the MTA to more readily evaluate potential locations for transit stops/stations rather than having to manually sort through all options.


![](/images/nyc_project_areas_of_opportunity.png)
<!--
Source - https://stackoverflow.com/a
Posted by Tieme, modified by community. See post 'Timeline' for change history
Retrieved 2025-11-07, License - CC BY-SA 4.0
-->

### [WPI Greenboard - Carbon Emission Visibility](https://github.com/We-Gold/wpi-greenboard)
A full-stack carbon emissions tracking system for Worcester Polytechnic Institute that quantifies the environmental impact of campus package deliveries through multi-carrier API integration and intelligent emissions calculations.

**My Contributions**: Collaborated on database architecture design and implementation using PostgreSQL with SQLModel ORM. Built the complete emissions calculation stack with speed-based emission factors (0.062-0.82 kg CO2e per tonne-km) and integrated multiple shipping carrier APIs (UPS, FedEx, USPS, DHL) using modular adapter patterns to normalize disparate response formats. Optimized processing performance from 1 to 12-14 packages/second through concurrent processing with ThreadPoolExecutor and intelligent geocoding caching strategies. Developed SQLModel-based FastAPI endpoints powering frontend data queries and visualization.

Technologies: Python, FastAPI, PostgreSQL, SQLModel, Multi-Carrier APIs, Concurrent Processing
![](/images/package_details_greenboard.png)![](/images/leaderboard_greenboard.png)

## Work Expereince 
### [Quaxar — Data Scientist / ML Product Lead ](https://github.com/surbhikapoor19/quaxar_fraud_platform)
*May 2025 – Aug 2025*  
- Built and deployed an end-to-end fraud detection platform using LayoutLMv3, SentenceTransformers, and XGBoost ensembles.  
- Integrated OpenAI APIs for OCR assistance, document integrity scoring, and text-based fraud detection.  
- Developed containerized model services with FastAPI and Docker and deployed on AWS.  
- Owned architecture, experimentation, stakeholder communication, demos, and final delivery.

### Ottimate (formerly Plate IQ) — Senior Data Scientist  
*Aug 2018 – Apr 2024*  
- Fine tuned transformer-based NLP models for document processing and entity extraction across millions of invoice and grocery line item records.  
- Built classification and text normalization pipelines with BERT, spaCy, scikit-learn, pandas, and NumPy.  
- Performed extensive EDA, created dashboards and reports for finance and product teams, and communicated insights to technical and non-technical stakeholders.  
- Worked across modeling, data engineering, and BI in a fast-paced startup environment.

## Other Standalone Projects 
### 1. [Receipts OCR Segmentation - Customizable code for segmenting receipt like documents](https://github.com/surbhikapoor19/receipts_ocr_segmentation)
### 2. [Statistical Machine Learning for Insights on Supermarket Style Data](https://github.com/surbhikapoor19/ds502-project)

# Contact Details
#### surbhi.kapoor19@gmail.com |[Linkedin Profile](https://www.linkedin.com/in/surbhikapoor19/) | [@surbhikapoor19](https://github.com/surbhikapoor19) 
