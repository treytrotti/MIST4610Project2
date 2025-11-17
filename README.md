# MIST 4610 Project 2 Group 7

## Group Members: 
1. [Justus Nour](https://github.com/justusnour)

2. [Jackson Boyer](https://github.com/Jackson9812)
   
3. [Rong Xin Hu](https://github.com/RongX02)

4. [Trey Trotti](https://github.com/treytrotti)

5. [Sophie Yoo](https://github.com/sophieyoo)


## Dataset Description

Data Set: Hate Crimes by County and Bias Type Beginning 2010


https://catalog.data.gov/dataset/hate-crimes-by-county-and-bias-type-beginning-2010


Canva Link: 


https://www.canva.com/design/DAG4suJcqb0/mXVWzznl7W_f_z9J15qjTg/edit 

## Describing the Dataset and What It Contains
The dataset used for this project is titled “Hate Crimes by County and Bias Type, Beginning 2010.” It was obtained from the U.S. Data.gov open data portal and published by the New York State Division of Criminal Justice Services.
This dataset provides annual counts of reported hate crime incidents, victims, and offenders in New York State, organized by county, year, and bias motivation. The bias categories include race, ethnicity, religion, sexual orientation, gender identity, disability, and other demographic characteristics. The data begins in 2010 and extends through recent years, allowing for meaningful trend and comparison analysis.
At the time of analysis, the dataset contained 822 rows (observations) and 44 columns (variables). Each row represents the number of hate crimes recorded in a specific county and year, separated into “Crimes Against Persons” and “Property Crimes.”
The key columns and their data types are summarized below:
County: The name of the New York county where the hate crime occurred (String).


- Year: The reporting year of the incident (Integer).


- Crime Type: Categorizes the offense as “Crimes Against Persons” or “Property Crimes” (String).


- Anti-Male / Anti-Female / Anti-Transgender / Anti-Gender Non-Conforming: Number of reported crimes motivated by gender or gender identity bias (Integer).


- Anti-White / Anti-Black / Anti-Asian / Anti-American Indian, etc.: Counts of hate crimes motivated by racial bias (Integer).


- Anti-Jewish / Anti-Catholic / Anti-Islamic (Muslim) / Anti-Other Religion, etc.: Counts of crimes motivated by religious bias (Integer).


- Anti-Hispanic / Anti-Arab / Anti-Other Ethnicity: Counts of crimes motivated by ethnicity or national origin (Integer).


- Anti-Gay Male / Anti-Gay Female / Anti-Bisexual / Anti-Heterosexual: Counts of crimes motivated by sexual orientation bias (Integer).


- Anti-Physical Disability / Anti-Mental Disability: Counts of hate crimes targeting individuals with disabilities (Integer).


- Total Incidents: Total number of hate crime incidents recorded for that county, year, and crime type (Integer).


- Total Victims: Total number of victims involved in those incidents (Integer).


- Total Offenders: Total number of known offenders (Integer).


This dataset provides a clear overview of hate crime activity across New York State counties beginning in 2010. Because it includes multiple bias categories, it allows for the exploration of questions such as:


- How the frequency of hate crimes has changed over time.

- Which bias types are most prevalent in certain regions.

- How different counties compare in total incidents and types of bias.

  
Its moderate size (822 rows × 44 columns) makes it ideal for Tableau analysis and visual exploration, while still being detailed enough to produce meaningful and socially relevant insights.

## Our Questions

Descriptive Question:
- How have the total number of hate crime incidents in New York State changed each year since 2010, and which counties have reported the highest or lowest totals?


The objective of this descriptive question is to summarize the patterns and trends in hate crimes across New York. This allows viewers to identify which incidents have increased or decreased in numbers over the years and which demographics experience higher levels of hate crime activity. We create a visualization of the total hate crimes by year and county, providing an analysis of how the hate crimes are distributed across the different demographics and years. Through a high-level overview of the crimes, we can dissect the hate crime distributions more in depth, potentially identifying reasons for drastic hate crime changes within neighborhoods.

Explanatory Question: 
- What types of bias—such as race, religion, sexual orientation, or gender identity—account for the largest share of hate crime incidents, and how have these patterns shifted over time?


The explanatory question analyzes the causes and motivations behind neighborhood hate crimes. The objective of this question is to reveal why certain harmful biases exist and how societal influences(e.g. Social justice movements, protests, legislation changes, etc.) can alter these totals. By exploring the biases, it can help analysts to explain why there are fluctuations in hate crime levels and identify the different groups that may have been increasingly targeted over time.

## Dataset Manipulations

Before performing analysis, several minor data manipulations and calculations were applied to prepare the Hate Crimes by County and Bias Type, Beginning 2010 dataset for visualization and interpretation.
- Filtering the Data by Year and County: The dataset contains data from multiple years and all counties in New York State. To simplify visualization and identify trends, the data was filtered to include only the years 2010 through the most recent available year. This made it possible to analyze time-based changes while maintaining focus on a consistent timeframe.
  
- Some counties reported zero incidents or had missing values for certain bias types. These were treated as zeros to maintain accuracy when calculating totals, ensuring that counties with no reported hate crimes were still represented in the analysis.

## Analysis and Results

### Descriptive Analysis

The time-series visualization of total hate crime incidents from 2010 through 2022 shows that incident levels vary meaningfully across years rather than staying stable. There are noticeable spikes around 2012, 2018, and 2021–2022, with declines in the years between those peaks. This pattern suggests that statewide hate-crime activity is influenced by broader social and political events, public visibility of bias-motivated incidents, and fluctuations in reporting behavior. The most recent increase after 2019 indicates that hate crimes remain a persistent and possibly growing issue in New York State.

The geographic analysis provides further insight by mapping total incidents by county. The filled county map reveals that hate crimes are not evenly distributed across the state. The highest totals occur in densely populated urban counties such as New York (Manhattan), Kings (Brooklyn), Queens, Bronx, and Erie, which collectively account for a significant portion of statewide incidents. Many smaller or rural counties in upstate New York report relatively few incidents. This pattern is consistent with differences in population size, diversity, and reporting infrastructure. Together, these descriptive findings create a clear picture of where and when hate crimes occur most frequently and help identify which regions may require greater prevention and outreach efforts.

### Explanatory Analysis

The explanatory analysis groups all individual bias-type fields into five major categories: Race, Religion, Sexual Orientation, Gender/Gender Identity, and Disability. When charted over time, race-related hate crimes appear consistently as the largest category in every year from 2010 to 2022. These incidents show noticeable increases in recent years, especially between 2020 and 2022. Religion-based hate crimes form the second-largest category and display similar peaks, suggesting that both race and religion remain the dominant motivators behind reported hate crimes in New York.

Sexual-orientation hate crimes make up a smaller share but still show important periodic fluctuations, including declines around 2017 and increases after 2020. Gender and gender-identity bias represents the smallest category overall, but the line chart reveals specific spikes—particularly in years when national attention on transgender rights and related policies was high. This indicates that although less frequent, these crimes may be strongly influenced by social discourse and political climate.

The stacked bar chart further clarifies how these bias categories relate to crime type. For the largest categories (race and religion), the majority of incidents are Crimes Against Persons, rather than property crimes, indicating direct interpersonal harm is more common than property damage in these contexts. Sexual-orientation and gender-identity categories also skew toward person-related crimes. This split underscores that hate crimes often involve direct confrontation or intimidation rather than indirect forms such as vandalism alone.

Collectively, the patterns suggest that race and religion remain the most significant drivers of hate-crime incidents in New York, both in total volume and in their tendency to involve person-targeted offenses. Sexual orientation and gender-identity categories, while smaller, exhibit meaningful shifts tied to broader cultural and political dynamics.

## Visualizations 
### Figure 1. Total Hate Crimes in New York by Year (2010–2022)

<img width="1138" height="637" alt="Screenshot 2025-11-16 at 6 36 26 PM" src="https://github.com/user-attachments/assets/012dd492-c505-4089-a194-9d0f7c4ba173" />

### Figure 2. Total Hate Crimes by County (Map)

<img width="1133" height="630" alt="Screenshot 2025-11-16 at 7 07 53 PM" src="https://github.com/user-attachments/assets/18163f8c-21fa-4ff5-a235-1a0359924eb8" />

### Figure 3. Bias Categories by Crime Type (Crimes Against Persons vs Property Crimes)

<img width="1133" height="613" alt="Screenshot 2025-11-16 at 6 38 22 PM" src="https://github.com/user-attachments/assets/d964c272-6527-4da2-b306-fe27ac87bd64" />

## Conclusion

This project provides a clear and data-driven view of how hate crimes have evolved across New York State from 2010 to 2022. The descriptive analysis shows that hate crime incidents fluctuate noticeably over time, with identifiable peaks connected to broader social and political moments. The geographic analysis further demonstrates that hate crime activity is concentrated in a handful of large, urban counties, while many rural counties report far fewer incidents. These findings highlight meaningful differences in population, reporting practices, and demographic composition across regions.

The explanatory analysis adds important context by examining the motivations behind these crimes. Race and religion consistently emerge as the primary drivers of hate crime incidents, both historically and in recent years. These categories also tend to involve a higher proportion of crimes against persons, signaling that many incidents involve direct confrontation rather than solely property damage. Sexual orientation and gender/gender-identity biases represent smaller but still significant portions of statewide incidents, with patterns that align closely with national discourse surrounding LGBTQ+ communities.

Collectively, the results suggest that hate crime activity in New York is shaped by demographic factors, social dynamics, and shifts in public visibility of bias-related issues. These findings can help guide policymakers, community organizations, and law enforcement agencies in allocating resources, developing targeted outreach programs, and continuing efforts to reduce bias-motivated harm across the state.

## Citations

New York State Division of Criminal Justice Services.
“Hate Crimes by County and Bias Type, Beginning 2010.”
Retrieved from Data.gov: https://catalog.data.gov/dataset/hate-crimes-by-county-and-bias-type-beginning-2010

Accessed: November 16, 2025.
