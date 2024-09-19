# VerveBridge
Project Overview: NBA Draft Combine Data Analysis (2009-2017)
This project focuses on the analysis of NBA Draft Combine data from 2009 to 2017, with the aim of uncovering insights into the physical attributes of draft prospects and their influence on draft outcomes. The NBA Draft Combine is a critical event where prospective players are evaluated on various physical and athletic metrics, providing valuable data for teams and analysts.

Key Attributes
•	Height (No Shoes)         
•	Height (With Shoes)       
•	Wingspan                  
•	Standing reach            
•	Vertical (Max)            
•	Vertical (Max Reach)      
•	Vertical (No Step)        
•	Vertical (No Step Reach)  
•	Weight                    
•	Body Fat     

Workflow:
Data Collection:

Gather NBA Draft Combine data for the years 2009-2017.
Data Cleaning:

Handle missing values and inconsistencies.
Convert physical measurement columns to appropriate numeric formats.
Exploratory Data Analysis (EDA):

Perform year-wise comparisons of average physical metrics.
Generate a correlation matrix to understand relationships between attributes.
Visualization:

Create line plots to track trends in physical metrics over time.
Use regression and scatter plots to explore how physical attributes relate to draft pick positions.
Insight Generation:

Analyze and interpret the visualizations to identify key trends and relationships.
Determine how specific physical attributes influence draft outcomes.
Conclusion:

Summarize the findings, emphasizing the role of physical metrics in the draft process and their evolution over time.



---


Big Game Census Dashboard

Overview

The Big Game Census Dashboard is an interactive visualization that offers insights into player demographics and statistics from teams in major games. It visualizes data across various dimensions, including player age, weight, birthplace, and position, to provide a clear and concise view of player distribution and trends. This dashboard, built using Power BI, highlights player statistics and geographical information for teams such as the New England Patriots and the Philadelphia Eagles.

Key Features

Player Statistics by Team: Allows users to compare teams like New England and Philadelphia across metrics such as average player age and weight.

Player Birthplace Mapping: A geographic map highlighting where players were born, with visual markers for the number of players from each city and state.

Player Demographics: Interactive charts display the distribution of players by age, weight, and position across different teams.

State Population Insights: A line graph that correlates player birth states with population estimates to analyze any trends.

Customizable Filtering: Users can filter players by name, age range, and team to explore specific data points relevant to their analysis.

Key Metrics

Average Player Age: The average age of players across the selected team.

Average Player Weight (lbs): The average weight of players, compared between New England and Philadelphia.

Player Birthplace Analysis: Summarizes the number of players from different cities and states.

Player Team Representation: Visual representation of players' statistics by team and position.

Position Distribution: Pie chart of the distribution of players by position (e.g., QB, WR, DE, TE).

Years Played: Highlights the number of years each player has played, offering insights into experience levels.

Workflow

Data Collection: The dataset includes player statistics such as age, weight, years played, team, and birthplace.

Data Transformation: The data is cleaned and organized for use in Power BI. Relevant attributes (e.g., player age, weight, team, position) are extracted for visualization.

Visualization Design: Using Power BI, the data is mapped and displayed in a range of visual formats, such as pie charts, bar graphs, and geographical maps.

User Interaction: Filters are provided to enable dynamic changes to the dashboard, allowing users to explore different views and insights.

Deployment: The final dashboard is deployed and shared, with interactive features allowing for real-time exploration.

Technologies Used

Power BI: Used for creating the interactive dashboard and visualizations.

Microsoft Bing Maps: For geographic plotting of player birthplaces.

CSV/Excel Data: Player statistics imported and processed for analysis.


---

Football Scenario Data Analysis
This repository provides a comprehensive analysis of football scenarios using various metrics and visualization techniques to offer insights into key decisions made during football plays. The data is analyzed to observe trends, confidences, and judgments in different football scenarios, such as passing, running, and kicking.

Overview
The Football Scenario Data Analysis focuses on visualizing and interpreting different football actions (antecedents) to understand decision-making patterns and their outcomes. The analysis includes metrics like trusted judgments, unit states, and antecedent confidence scores to gain insights into key football actions like running, passing, punting, kicking a field goal, and more.

Workflow
Data Collection:
Data is gathered from football scenarios, capturing various antecedents such as pass, run, punt, kneel down, and kick a field goal.

Data Processing:
The raw data is processed to extract valuable insights like trusted judgments, unit state statuses, and confidence scores related to each action. The data is segmented based on antecedents and unit IDs.

Visualization:
The processed data is visualized through various charts and graphs. Key visualizations include:

Pie charts showing the distribution of trusted judgments by antecedents.
Line graphs depicting the confidence over time for different football actions.
Bar charts displaying the number of trusted judgments and original antecedents across multiple categories.
Analysis:
The analysis focuses on key football decisions, where the confidence and judgment of each scenario are evaluated. Trends are identified based on unit states and the confidence levels of each antecedent decision.

Key Metrics
1. Sum of Unit IDs by Antecedent:
Pass: 35.9%
Run: 30.9%
Kick a Field Goal: 11.02%
Punt: 11.02%
Kneel Down: 2.32%
Don’t Know / It Depends: 8.86%
This metric shows the proportion of unit IDs associated with different antecedent decisions in football scenarios.

2. Count of Trusted Judgments by Antecedent:
Pass: 35.9%
Run: 30.9%
Kick a Field Goal: 11.02%
Punt: 11.02%
Kneel Down: 2.32%
Don’t Know / It Depends: 8.86%
This metric reveals the count of trusted judgments in various antecedent actions, highlighting which plays are trusted the most.

3. Average of Trusted Judgments:
6.11
This metric represents the overall average of trusted judgments across all football actions and scenarios.
4. Average of Antecedent Confidence:
0.76
The average confidence associated with each antecedent is analyzed, representing how confident decisions are during different football scenarios.
5. Count of Trusted Judgments by Unit State:
Finalized: 3,730
Golden: 130
The count of trusted judgments is broken down by unit state to show finalized decisions and golden state judgments.
Visualizations
The analysis is complemented with various visualizations:

Pie Charts: Showing the distribution of antecedents and trusted judgments.
Line Graphs: Tracking the confidence of judgments over time.
Bar Charts: Highlighting the count of original antecedents and trusted judgments.
Conclusion
This analysis provides valuable insights into football scenario decisions, offering a breakdown of trusted judgments, confidence levels, and trends in decision-making. The goal is to improve understanding of key football actions, helping coaches and analysts make better-informed decisions based on data.
