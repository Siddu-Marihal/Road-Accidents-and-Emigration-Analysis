# Overview 
This repository contains datasets and analyses related to two important issues in India: road accidents and migrant worker emigration. The data has been compiled from official government reports and structured into standardized datasets to facilitate further research and insights. Additionally, Excel files containing metadata—including information about the datasets and the links to data sources used for collection—are provided for transparency and reference.

## Task 1: Road Accidents in India
### Road accidents cause a significant loss of lives in India every year. Using data from the latest Road Accidents in India report, this dataset provides:

- Year-wise and State-wise total number of road accidents in India since 2011.
- Year-wise and State-wise number of road accidents per thousand vehicles in India since 2011.
- Validation with NCRB’s ‘Accidental Deaths and Suicides in India’ report to ensure consistency.
- Trend analysis to determine whether road accidents have increased or declined over time.

## Task 2: Emigration of Indian Migrant Workers
### Migrant worker emigration is a crucial socio-economic phenomenon in India. This dataset is compiled from secondary research and government sources to answer:

- Total number of Indians who received Emigration Clearances in the last decade.
- Number of employers registered on the e-Migrate portal and the major sectors they belong to.
- Major destination countries for Indian migrant workers.
- Complaints received and prosecution sanctions against illegal recruitment agents, given the risks of fake agents and human trafficking.

## Additional Resources
Files containing metadata provide details about the datasets, including data descriptions and links to official sources.
Visualizations and trend analyses are included for better interpretation of the data.
This repository aims to provide a structured foundation for policymakers, researchers, and analysts to derive meaningful insights into these critical issues.

# The Analysis

## Task 1:

### Analysis of Accidents Per 1000 Vehicles (NCRB vs. MoRTH)

![Accidents Per 1000 Vehicles](https://github.com/Siddu-Marihal/Road-Accidents-and-Emigration-Analysis/blob/c852fb37ec489cc5843ea9772c06ecc8082e5a50/images/Accidents.png)

#### 1. Overall Trend:
- Both datasets show a declining trend in accidents per 1,000 vehicles from 2011 to 2020, indicating improved road safety.
#### 2. NCRB vs. MoRTH Data:
- 2011: NCRB reports a higher accident rate than MoRTH.
- 2013–2015: MoRTH data is higher than NCRB, suggesting variations in reporting methods.
- 2016–2020: Both datasets align closely, showing a consistent downward trend.
#### 3. Key Observations:
- 2011–2013: Sharp decline in accident rates.
- 2013–2015: Fluctuations, with MoRTH reporting higher values.
- 2016–2020: Steady decline, reaching around 1 accident per 1,000 vehicles in 2020.
#### 4. Possible Reasons for Variations:
- Different data sources: NCRB relies on police reports, while MoRTH may use transport department data.
Improved reporting accuracy in later years.
#### 5. COVID-19 Effect in 2020:
- The sharp decline in 2020 can be attributed to reduced vehicular movement during lockdowns, leading to fewer accidents.
### Conclusion:
- Despite minor variations, both datasets confirm a significant reduction in road accidents per 1,000 vehicles over time, with COVID-19 further accelerating the decline in 2020.

## Task 2:

### Analysis of Emigration Data

![Emigration](https://github.com/Siddu-Marihal/Road-Accidents-and-Emigration-Analysis/blob/25bcf7620bb688b4d419dd307b804cca53252f91/images/Screenshot%202025-03-15%20193658.png)

#### 1. Emigration Clearances (MEA vs. E-Migrate) – First Graph
- 2014 - Large Discrepancy
MEA: 805K clearances
E-Migrate: Only 210K clearances
Comment: MEA likely included manual records, while E-Migrate accounted for digitally processed applications.

- 2019 - Noticeable Difference
MEA: 368K clearances
E-Migrate: 82K clearances
Comment: Possible data reporting differences or missing entries in E-Migrate.

- 2020 - COVID Impact
Both datasets show a sharp decline to 94K, reflecting global travel restrictions.
Post-2020 Recovery
Emigration numbers gradually increased, with MEA and E-Migrate showing similar trends (~398K in 2023).
Comment: Better data synchronization and integration of digital records over time.

#### 2. Number of Employers Registered – Second Graph
- Peak in 2016 (64K registrations), followed by a steady decline.
- Sharp drop in 2020 (6K registrations) due to COVID-related disruptions.
- Recovery in 2022 (44K registrations), but numbers dropped again in 2023 (9K) and 2024 (10K).
Comment: The decline post-2022 suggests persistent challenges such as stricter regulations, economic slowdowns, or reduced foreign hiring demand.

#### 3. Sector-Wise Distribution of Employers – Third Graph
- Top sectors for foreign employment:
Activities of households as employers (50K) – Likely includes domestic workers.
Construction (40K) – A key sector for Indian migrant workers.
Manufacturing (11K), Accommodation & Food Services (9K), Retail Trade (7.7K).
- Least Represented Sectors:
Education (545), Agriculture & Forestry (2.1K).
Comment: Most jobs are in low-skilled or semi-skilled sectors, while highly skilled sectors like Education remain limited.

#### Key Takeaways
Data Discrepancies (2014, 2019): MEA data was higher than E-Migrate, suggesting manual record inclusion.
COVID-19 Impact (2020): Emigration and employer registrations dropped significantly.
Post-2020 Recovery: Numbers improved, but employer registrations dropped again after 2022.
Sector Trends: Household work and construction dominate, while skilled sectors remain low.

### Analysis of Emigration Destinations (2014-2022)

![Destinations](https://github.com/Siddu-Marihal/Road-Accidents-and-Emigration-Analysis/blob/25bcf7620bb688b4d419dd307b804cca53252f91/images/Screenshot%202025-03-15%20194648.png)

#### 1. Dominant Destinations
Saudi Arabia (1.21M emigrants) – The largest destination, reflecting strong demand for Indian migrant workers, especially in construction and household sectors.
UAE (0.99M emigrants) – A close second, driven by job opportunities in construction, hospitality, and retail.
#### 2. Mid-Tier Destinations
Kuwait (0.43M), Oman (0.36M), Qatar (0.32M) – These countries attract a significant number of workers, primarily in construction, oil & gas, and service sectors.
#### 3. Lower-Tier Destinations
Malaysia (0.10M), Bahrain (0.08M) – These nations have a relatively smaller share of Indian emigrants, possibly due to stricter visa regulations or limited employment opportunities.
Jordan (0.02M), Lebanon (0.02M), Thailand, Indonesia (~0M) – Minimal emigration, indicating limited demand for Indian workers in these regions.
#### Key Takeaways
Gulf countries dominate emigration trends due to high demand for labor-intensive jobs.
Saudi Arabia and UAE together account for ~2.2M emigrants (~60% of total).
Minimal emigration to Southeast Asia, likely due to better job prospects in the Middle East.

### Complaints Received And Prosecution Sanctions Against Illegal Recruitment Agents Analysis

![Complaints and Actions](https://github.com/Siddu-Marihal/Road-Accidents-and-Emigration-Analysis/blob/25bcf7620bb688b4d419dd307b804cca53252f91/images/Screenshot%202025-03-15%20200430.png)

#### Analysis of Complaints and Emigration Cases Referred to State (First Graph)
- The number of complaints and emigration cases referred to the state has fluctuated over the years, with peaks in 2017, 2019, and 2023.
- 2019 saw a high volume of both complaints (0.77K) and cases referred (0.77K).
- 2023 had the highest number of complaints (1.01K), but only 0.15K cases were referred, indicating that a much smaller proportion of complaints resulted in state intervention.
- In 2024, complaints (0.58K) are higher than in 2017 (0.45K) but lower than in 2019 (0.77K) and 2023 (1.01K). However, cases referred in 2024 (0.07K) are significantly lower than in 2017 (0.45K) and 2019 (0.77K).
- The decline in 2024 compared to 2023 is evident, but the complaint numbers remain relatively high, while cases referred continue to drop.

#### Analysis of Prosecution Sanctions Sought and Issued (Graph 2)

- The number of prosecution sanctions sought and issued peaked in 2016 (42), indicating a major crackdown that year.
- 2019 saw another high (35), though lower than 2016. This suggests periodic surges in legal action against violators.
- Between 2020 and 2021, the number of sanctions remained consistently low (7 each year), showing a significant drop compared to previous years.
- A gradual increase is observed from 2022 onwards, with 2022 (11), 2023 (15), and 2024 (14), indicating a steady rise in legal enforcement but not reaching previous peak levels.
- Throughout the years, the number of sanctions sought and issued has remained equal, suggesting that most requests for prosecution were approved.

  
# Challenges Faced 

## 1. Road Accidents Data Collection Challenges
- Difficulty in obtaining state-wise and year-wise accident data: Extracting the number of road accidents per state for each year since 2011 was challenging as the data was not readily available in a structured format.
- Lack of direct access to vehicle registration data: To calculate accidents per 1,000 vehicles, I had to find the number of registered vehicles year-wise, which required searching for separate datasets.
- Cumbersome process of retrieving data from government sources: Extracting data from the Ministry of Road Transport and Highways (MoRTH) and the National Crime Records Bureau (NCRB) was time-consuming. Old reports from 2011 to 2014 were particularly difficult to locate.
- Data stored in PDF format: Most reports were in PDF format rather than structured datasets, requiring me to manually download and extract information from hundreds of files.

## 2. Emigration Data Collection Challenges
- Complexity in retrieving data from multiple sources: Getting emigration data from the e-Migrate portal and the Ministry of External Affairs (MEA) was extremely difficult due to fragmented and inconsistent reporting.
- Manual extraction of data from PDFs: Similar to road accident data, emigration-related statistics were scattered across multiple PDF reports, requiring extensive manual effort.
- Difficulty in obtaining complaints, cases referred, and prosecution sanctions data: Information on complaints against illegal recruitment agents, cases referred to state governments, and prosecution sanctions sought/issued was not centrally available and required extensive searching across various reports.
- Data validation and accuracy checking: After gathering data from multiple sources, verifying its correctness and ensuring consistency was another tedious and time-consuming process.
- Extracting data from images and scanned documents: Some reports had key data embedded in images, making it difficult to extract and requiring additional tools for text extraction.

## Overall Challenges
Collecting, validating, and structuring the data for both road accidents and emigration was a highly challenging task. The reliance on unstructured data sources, the need to extract information from images, and the manual verification process made the entire data compilation effort time-consuming and demanding.




