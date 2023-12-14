# Causes of Death 2010-2019 Period Analysis
Analyzed by: Diana Postica
##

## Project Deliverables
+ Sourcing open data (Check the data source and data profile [here](https://github.com/dianndp/causes_of_death_2010-2019/raw/main/data_source_and_profile.docx))
+ Exploring Relationships
+ Geographical visualizations with
+ Supervised Machine Learning
+ Unsupervides Machine Learning
+ Sourcing and Analysing Time Series Data
+ Creating Final Report in Tableau Storyboard format

## Data Contents
Two different data sets were merged to form one final dataframe.

1. The 'Causes of death' data set is composed of 6120 rows and 33 columns and contains the death causes count by country and year (1990 to 2019).
- Columns: ‘Country/Territory’, ‘Code’, 'Year', 'Meningitis', 'Alzheimer's Disease and Other Dementias', 'Parkinson's Disease', 'Nutritional Deficiencies', 'Malaria', 'Drowning', 'Interpersonal Violence', 'Maternal Disorders', 'HIV/AIDS', 'Drug Use Disorders', 'Tuberculosis', 'Cardiovascular Diseases', 'Lower Respiratory Infections', 'Neonatal Disorders', 'Alcohol Use Disorders', 'Self-harm', 'Exposure to Forces of Nature', 'Diarrheal Diseases', 'Environmental Heat and Cold Exposure', 'Neoplasms', 'Conflict and Terrorism', 'Diabetes Mellitus', 'Chronic Kidney Disease', 'Poisonings', 'Protein-Energy Malnutrition',  'Road Injuries', 'Chronic Respiratory Diseases', 'Cirrhosis and Other Chronic Liver Diseases', 'Digestive Diseases',' Fire, Heat, and Hot Substances', 'Acute Hepatitis.

2. The 'Economic Data' is composed of some world statistics and has in total 55 columns. Only 'country code' and 'GDP per capita' columns were used in this analysis.

   
## Data Source
1. The 'Causes of death' data set was retrieved from Kaggle.
The web page provides the source citation in the following manner: ‘’This Dataset is created from Our World in Data. This Dataset falls under open access under the Creative Commons BY license. Special thanks to Max Roser, Hannah Ritchie, and Fiona Spooner (2021) - "Burden of disease". Published online at OurWorldInData.org. Retrieved from: https://ourworldindata.org/burden-of-disease [Online Resource].’’

2. The 'Economic Data' was sourced from Kaggle, which is publicly available for anyone to use under the following terms provided by the Dataset Source
https://www.worldbank.org/en/about/legal/terms-of-use-for-datasets

## Analysis Objective
This is an Exploratory Data Analysis whose purpose is to provide information about the top reasons for mortality. Raising public awareness to inform them about what to protect themselves from. The analysis will also serve as a valuable resource for doctors, researchers, government entities, and the pharmaceutical industry, guiding them in determining where to direct medical production efforts and exploring innovative approaches to healthcare.

## Research Questions
1.	What are the most common causes of death? What are the deadliest diseases? 
2.	Do the causes of death experience changes over the years?
3.	Is there a correlation between a country's level of development and the causes of death?
4.	What are the chances of dying from an external sudden cause versus an internal one?
5.	Do causes of death vary among different countries?

 ## Data Limitations
Potential bias during the collection stage may arise when some deaths have multiple contributing factors. For instance, a person might have died of old age but been recorded as having succumbed to a specific disease. This introduces a source of bias in the data, as the primary cause of death may not accurately reflect the complex circumstances surrounding the individual's death.
Potential human errors during manual data entry; including inputting 20 instead of 2, placing information in the incorrect column or row, or making other mistakes in the process of entering data into the system.
The summary of deaths for a given year and country may vary from the total mortality that occurred because the data does not encompass all potential fatalities.

# Final Report
[Tableau Storyboard](https://public.tableau.com/app/profile/diana.postica/viz/CausesofDeath_17011219322430/Story1?publish=yes)

