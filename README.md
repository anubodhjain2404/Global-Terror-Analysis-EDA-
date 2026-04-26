# UN Global-Terrorism-Analysis (EDA)

# 📌Project Overview
The United Nations Global Terrorism Analysis (UNGTA) dataset provides a comprehensive record of over 180,000 terrorist incidents worldwide from 1970 to 2017. This project aims to perform an in-depth Exploratory Data Analysis (EDA) to understand global terrorism trends, regional patterns, major attack types, casualties, and the behavior of terrorist groups over nearly five decades.

Through systematic data cleaning, preprocessing, descriptive analytics, and meaningful visualizations, the project uncovers important insights such as the rise of terrorism after 2000, the concentration of attacks in regions like the Middle East and South Asia, the dominance of bombing/explosion attacks, and the disproportionate involvement of a few highly active terror groups.

The analysis utilizes Python libraries such as Pandas for data handling, NumPy for numerical operations, and Matplotlib/Seaborn for producing powerful visualizations. The outcome of this project provides policymakers, security agencies, and research analysts with valuable insights that can support better threat assessment, risk mitigation, and strategic planning.

<img width="800" height="400" alt="image" src="https://github.com/user-attachments/assets/c8accd55-4a53-4c17-a0ce-d0a282a10684" />

# 🎯 Problem Statement
Terrorism remains a major global threat, affecting public safety, international stability, and socioeconomic development. The United Nations Global Terrorism Analysis (UNGTA) dataset provides detailed records of terrorist incidents from 1970 to 2017. However, due to the dataset’s size and complexity, meaningful insights are not immediately visible.

The problem is to analyze this large dataset using Exploratory Data Analysis (EDA) techniques to identify patterns, trends, hotspots, major attack methods, and key terrorist groups. The objective is to uncover actionable insights that can help policymakers, researchers, and security agencies understand the historical behavior of terrorism and support better strategic planning.

# 💼 Business Objective
The objective of this project is to analyze the UNGTA terrorism dataset to uncover meaningful patterns and trends that can help governments, researchers, and security agencies understand the global landscape of terrorism. By identifying high-risk regions, common attack methods, major terrorist groups, and casualty patterns, the analysis aims to support better decision-making and more effective counter-terrorism strategies.

# 📂 Dataset Information
The Global Terrorism Dataset includes the following key variables:

* iyear – Year of incident
* country_txt – Country where attack occurred
* region_txt – Region of the world
* attacktype1_txt – Type of attack
* gname – Terrorist group name
* nkill – Number of people killed
* nwound – Number of people wounded

# 🧹 Data Preprocessing
The dataset was cleaned and prepared using the following steps:
* Removed duplicates to ensure each terrorist incident is counted only once.
* Handled missing values:
  * Filled numerical columns with 0.
  * Filled categorical columns with "Unknown".
* Dropped irrelevant or highly null columns that don’t contribute to analysis.
* Converted data types where necessary (e.g., year to integer).
* Verified dataset shape and readiness for analysis.

# 🔍 Exploratory Data Analysis
EDA was performed to understand terrorism patterns and global trends.

**Analysis Performed**

* Terrorist attacks per year
* Country wise attack analysis
* Region wise distribution
* Attack type analysis
* Terrorist group analysis
* Casualty distribution
* Total casualties over time
* Region wise casualties
* Country wise casualties

# 📊 Visualizations Included
The project includes multiple meaningful charts:
* Attacks Over the Years
* Most Affected Regions
* Top 10 Countries with Highest Attacks
* Type of attacks
* Type of weapons used
* Top Terrorist Groups
* Heatmap: Country vs Attack Count
* Correlation Heatmap (casualities and wounded)
* Pair Plot (Year, casualities and wounded)

# 📈 Key Insights
* Terrorist attacks increased significantly after 2000
* Middle East & North Africa region has highest attacks
* Terrorism is concentrated in specific countries
* Bombing and armed assault are most common attack types
* Few terrorist groups dominate attack frequency
* Casualties fluctuate with peaks in certain years
* Some countries experience significantly higher casualties
* High severity incidents are limited but impactful

# 🛠️ Technologies Used
* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Google Colab

# 📌 Solution to Business Objective
* Resource Allocation:
  * Focus security resources on the most affected countries and regions identified from the analysis.
* Targeted Counter-Terrorism Strategies:
  * Prioritize monitoring of top terrorist groups and common attack/weapon types to prevent high-risk incidents.
* Predictive Planning:
  * Use trends over the years to forecast potential spikes in attacks, enabling proactive measures.
* Infrastructure & Public Safety Measures:
  * Strengthen security in areas with historically high casualties and common attack types.
* International Collaboration:
  * Share insights with global agencies to coordinate responses in regions with repeated attacks.
* Continuous Monitoring & Analysis:
  * Regularly update and analyze incident data to adapt strategies to changing patterns of terrorism.
  
**Overall:**
By combining data-driven insights with proactive planning, the client can minimize casualties, protect assets, and improve regional stability, directly supporting their business objective.

# 📌 Conclusion
* The exploratory analysis of the United Nations Global Terrorism Dataset (1970–2017) revealed key patterns in global terrorist activities.
* Trends over time show a rise in attacks post-2000, with notable spikes in specific regions like the Middle East, South Asia, and Western Europe.
* Bombings and armed assaults are the most common attack types, and explosives and firearms are the weapons most frequently used.
* A small number of terrorist groups are responsible for a large proportion of attacks, highlighting where counter-terrorism efforts should be concentrated.
* Insights from casualties, attack types, and regions provide actionable information for governments, security agencies, and organizations to allocate resources, plan   preventive measures, and improve public safety.
* Overall, this analysis demonstrates that data-driven insights can guide strategic decisions, helping reduce the impact of terrorism and improve regional security planning.
