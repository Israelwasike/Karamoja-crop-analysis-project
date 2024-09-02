# KARAMOJA CROP ANALYSIS PROJECT
## Overview
In the Karamoja region, NGOs face challenges in assessing agricultural productivity due to limited visibility into crop yields across various districts and sub-counties. Despite providing technical support and farm inputs to farmers, there is a significant gap in understanding the spatial distribution and variation of crop yields, particularly for sorghum and maize. This lack of comprehensive data impedes the effective prioritization of interventions and resource allocation. To address this issue, the goal of this project is to develop an interactive visualization tool that leverages data from the 2017 crop season to offer clear insights into crop yield patterns. This tool will help NGOs make informed decisions, optimize their support strategies, and ultimately improve food security in the region.
### Project structure
**data/** - Contains all the datasets used in the project. <br>
**notebooks/** - Jupyter notebooks used for data analysis and cleaning. <br>
**Presentation/** - Contains the non-technical presentation.
### Installation
To set up the project locally, follow these steps: <br>
* Clone the repository. <br>
* Install the required Python packages: pip install -r requirements.txt. <br>
* Ensure you have Tableau installed for dashboard visualization. <br>
### Usage
Guide on how to use the project, including running analyses, generating visualizations, or using the dashboard.<br>
* To analyze crop yields, open the relevant Jupyter notebook in the `notebooks/` directory and run the cells. To view the interactive dashboard, open [Tableau public](https://public.tableau.com/app/profile/israel.wasike/viz/Karamojacropyieldinsights/CropYieldInsightsSorghumandMaizeinKaramoja?publish=yes) 
* **District Crop Yield Population Data:** Contains information on crop yields and population by district.
* **Subcounty Crop Yield Population Data:** Contains information on crop yields and population by sub-county. 
### Data
Information about the datasets used, including their sources and any preprocessing steps.<br>
The project uses crop yield data from the Uganda Karamoja District region for the year 2017. Data was cleaned using Python, and spatial files were loaded and viewd in Tableau Desktop
### Objectives
The goal of this analysis is to develop an interactive visualization tool that provides insights into crop yields across different districts and sub-counties in Karamoja for the 2017 crop season. By analyzing and visualizing the data, we aim to:<br>
1. **Identify Patterns:** Understand the distribution of crop yields across various regions.<br>
2. **Highlight Trends:** Detect any significant trends or anomalies in crop yields.<br>
3. **Support Decision-Making:** Provide actionable insights that can help NGOs prioritize their activities and allocate resources more effectively.<br>
### Research questions
1. What are the spatial patterns of population across different districts and in Karamoja during the 2017 crop season?<br>
2. Which districts in Karamoja are experiencing the lowest crop yields, and how do these areas compare with regions of higher productivity?<br>
3. How does the population size of a district or sub-county correlate with the crop yield in Karamoja?<br>
4. What is the proportion of land dedicated to Sorghum and Maize in different districts?<br>
5. What trends can be observed in crop production relative to changes in crop area over the specified period?<br>
### Results
Kaabong and Nakapiripirit should get a boost to improve maize production, and Kotido needs to focus on enhancing sorghum yields. For areas with weaker agriculture, exploring alternatives like pastoralism or trade could help. It’s also important to address why some districts aren't seeing better yields with more land and keep population differences in mind when planning resource support.
### Contributing
Contributions are welcome! Please fork the repository and submit a pull request with any changes or additions! 
