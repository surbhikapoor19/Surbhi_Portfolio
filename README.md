# Surbhi Kapoor's Portfolio
- Data Science and Machine Learning Project contributed and/or built out by me.
- All projects are primarily built out in Python and SQL. 

## Project 1: [Assessing Underserved Regions (using ML) - NYC Transit System](https://github.com/We-Gold/ds-501-cs4-public)
In this project, we identified areas in New York City (NYC) that are underrepresented in transit accessibility. We wanted to understand areas of opportunity (defined as currently underserved areas where we predict people would have high public transportation usage) where the MTA could create a transit station that we believe will receive a lot of foot traffic and ticket sales.

To solve this problem, we determined the average distance to a transit station from areas all over NYC. We then determined if the area is worth investing in (would a transit station here be profitable?) by looking at predicted ridership. Each subway ride in NYC earns $2.90 per ride per person (https://www.mta.info/fares-tolls/subway-bus), and since we can predict weekly ridership, we will predict weekly revenue based on that predicted ridership.

Our data science approach will not only enable us to identify underserved areas but also to predict ridership for these areas. The resulting decision-making platform will enable the MTA to more readily evaluate potential locations for transit stops/stations rather than having to manually sort through all options.


<img src="https://github.com/surbhikapoor19/Surbhi_Portfolio/blob/main/images/nyc_project_areas_of_opportunity.png" width="80%"></img> 
<!--
Source - https://stackoverflow.com/a
Posted by Tieme, modified by community. See post 'Timeline' for change history
Retrieved 2025-11-07, License - CC BY-SA 4.0
-->



## Project 2: [WPI Greenboard - Carbon Emission Visibility](https://github.com/We-Gold/wpi-greenboard)
A full-stack carbon emissions tracking system for Worcester Polytechnic Institute that quantifies the environmental impact of campus package deliveries through multi-carrier API integration and intelligent emissions calculations.

**My Contributions**: Collaborated on database architecture design and implementation using PostgreSQL with SQLModel ORM. Built the complete emissions calculation stack with speed-based emission factors (0.062-0.82 kg CO2e per tonne-km) and integrated multiple shipping carrier APIs (UPS, FedEx, USPS, DHL) using modular adapter patterns to normalize disparate response formats. Optimized processing performance from 1 to 12-14 packages/second through concurrent processing with ThreadPoolExecutor and intelligent geocoding caching strategies. Developed SQLModel-based FastAPI endpoints powering frontend data queries and visualization.

Technologies: Python, FastAPI, PostgreSQL, SQLModel, Multi-Carrier APIs, Concurrent Processing
<img src="https://github.com/surbhikapoor19/Surbhi_Portfolio/blob/main/images/package_details_greenboard.png" width="45%"></img> <img src="https://github.com/surbhikapoor19/Surbhi_Portfolio/blob/main/images/leaderboard_greenboard.png" width="45%"></img> 
