# Addis Ababa Road Accident Report
This repository contains a report analyzing road accidents in Addis Ababa, focusing on prevalent causes and conditions contributing to accidents.

## Table of contents


### Introduction

This report offers a comprehensive analysis of road accidents that have occurred in the city of Addis Ababa. It delves into the primary causes of these accidents and the prevalent conditions under which they occur, as well as the demographics of the most commonly affected drivers.

The analysis presented herein provides valuable insights into the patterns of accident occurrence within Addis Ababa. These insights hold significance for governmental bodies such as the state police and relevant ministries, as they can inform the development of policies, measures, and interventions aimed at reducing the incidence of road accidents. Furthermore, such actions can contribute to the enhancement of safety measures, ultimately safeguarding lives and properties across the city.

### Dataset Description

The dataset utilized for this analysis was sourced from Kaggle and comprises two versions: the cleaned dataset and the raw, unprocessed dataset. The cleaned version was used for analysis after undergoing several transformations to ensure its compatibility and suitability. The link to the dataset can be found [here](https://www.kaggle.com/datasets/saurabhshahane/road-traffic-accidents).


### ETL(Extract, Transform and Load) Process

The extraction of the dataset was conducted using Power Query to facilitate data transformation and preparation. The dataset encompasses road accidents within the sub-city of Addis Ababa, comprising 20 columns and 10,000 rows. It includes details about drivers, victims, including incidents involving animals, as well as road and weather conditions at the time of the accidents, along with collision dimensions.

Transformation of the dataset was executed within Power Query. The process commenced with several steps aimed at profiling the data, leveraging features within Power Query. This included:

- Column Quality Analysis**: To assess the quality of data within each column, identifying the percentage of valid, empty, and erroneous data entries.
- Column Distribution Analysis**: Identifying the number of unique and distinct values present in each column.
- Column Profiling**: Combining the insights from column quality and distribution analyses to gain a comprehensive understanding of the data within each column. Additionally, this analysis provided graphical representations, such as bar charts, illustrating the distribution of values within each column.

These profiling procedures proved instrumental in identifying various cleaning tasks required for the dataset. For instance, an issue was discovered within the "Driving Experience" column, which contained two variations of the "Unknown" value due to differences in case. This discrepancy was rectified utilizing Power Query's replace function, ensuring data consistency and integrity.

### (EDA) Exploratory Data Analysis

To gain a comprehensive understanding of the dataset, an initial exploratory analysis was conducted using Power BI. This analysis aimed to comprehend the data structure and identify pertinent facts and dimensions for inclusion in the report.

The dataset primarily consists of categorical variables. Therefore, a count approach was employed extensively to summarize the occurrences of different categories within these variables across the dataset. This facilitated the identification of patterns, trends, and distributions within the data, laying the groundwork for further analysis and insights.

### Data Analysis and Visualization

This section delves into the data to address three primary questions, with visualization and presentation of the findings accomplished through Power BI to enhance audience comprehension. The main questions explored are as follows:

1. What category of drivers are more involved in road accidents?
2. Under what road and weather conditions are road accidents prevalent?
3. How does the collision frequently occur?

### Analysis Findings

#### __1. Driver Characteristics__
-  Male drivers exhibited the highest involvement in road accidents, surpassing all other genders combined.
-  Drivers with 5 years of driving experience were most frequently involved, followed by those with 2-5 years of experience.
-  Age groups 18-30 and 31-50 accounted for the majority of accidents.
-  Drivers with junior high school educational qualifications were disproportionately involved in accidents.
-  Employed drivers constituted the highest proportion of accidents, surpassing both owners and other employment statuses combined.

#### __2. Road and Weather Conditions__
-  Normal weather conditions were predominant, with incidents occurring more frequently than during rainy, cloudy, or windy conditions.
- Daylight conditions witnessed the highest frequency of accidents, followed by situations where light was present in darkness.
- Y-shaped junctions and junctions without markings recorded the highest occurrence of accidents.
- Two-way divided lanes with a broken line marked the most common location for accidents, closely followed by undivided two-way lanes.

#### __3. Collision Details__
-  Among the top five causes of accidents, instances of "no distancing," "changing lane to the right," and "changing lane to the left" were prevalent.
-  Vehicle-to-vehicle collisions were the most frequent collision type, followed by collisions with roadside objects, albeit with a notable difference in frequency.
-  __"Going straight"__ emerged as the primary action leading to accidents, with minimal involvement from actions such as moving backward or reversing.
-  __"Not a pedestrian"__ was the most common pedestrian involvement type, indicating a predominance of accidents involving non-pedestrian entities.

### Recommendations

#### **1. Targeted Driver Education and Training**
   - Implement targeted educational programs focusing on male drivers, particularly those aged 18-50, to raise awareness about safe driving practices and the risks associated with reckless behavior.
   - Develop driver training initiatives tailored to individuals with 2-5 years and 5 years of driving experience, emphasizing defensive driving techniques and hazard perception skills.
   - Enhance educational campaigns aimed at drivers with junior high school qualifications, providing accessible resources to improve their understanding of road safety principles.

#### **2. Road and Weather Condition Awareness**
   - Improve signage and communication strategies to alert drivers to hazardous road and weather conditions, particularly during adverse weather events such as rain or darkness.
   - Enhance road maintenance efforts to minimize risks associated with poorly lit areas and poorly marked junctions, prioritizing safety measures at high-accident-prone locations.

#### **3. Collision Prevention Strategies**
   - Implement measures to encourage safer driving behaviors, such as maintaining safe distances and using turn signals when changing lanes, to reduce the incidence of common collision causes identified in the analysis.
   - Invest in infrastructure improvements, such as road barriers and clear lane markings, to mitigate the impact of vehicle-to-vehicle and vehicle-to-object collisions, especially in high-traffic areas.
   - Develop pedestrian safety initiatives focusing on areas with a high frequency of accidents involving non-pedestrian entities, emphasizing the importance of pedestrian awareness and adherence to traffic regulations.

#### **4. Continuous Monitoring and Evaluation**
   - Establish a system for ongoing monitoring and evaluation of road safety initiatives, utilizing data-driven insights to assess the effectiveness of implemented measures and identify areas for further improvement.
   - Foster collaboration between relevant stakeholders, including government agencies, law enforcement, and community organizations, to facilitate coordinated efforts in implementing road safety interventions and addressing identified challenges.

