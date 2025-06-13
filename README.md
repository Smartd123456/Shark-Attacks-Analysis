# Shark-Attacks-Analysis
This project explores global shark attack data from 1900 to the present using **Power BI**. The dashboard provides key insights into where, when, and how shark attacks occur, identifying high-risk areas, vulnerable body parts, and the species most commonly involved. 

# Project Overview
This project is about analyzing shark attacks that happened around the world from 1900 to recent years. The goal is to understand where, when, and how these attacks happen the most.
I cleaned the data, fixed errors, and built an easy-to-read dashboard using Power BI. The dashboard helps users see:
- How shark attacks have changed over time
- The countries and places with the most attacks
- Which times of day attacks happen most
- The body parts that are usually injured
- The types of sharks involved most often
- This project shows how I used my data skills to turn messy information into helpful insights that anyone can understand and use.

## Project Goal
The goal of this project is to understand shark attacks by analyzing over 100 years of reported cases. I wanted to find useful patterns like:
- Where shark attacks happen most
- When they are most likely to happen
- Who is most affected
- What kind of sharks are involved
By doing this, I aimed to turn raw data into clear insights using Power BI, helping anyone understand the trends behind shark attacks.

## Tools Used
- Power BI- Used to clean, analyze, and visualize the data
- Power Query- Used inside Power BI to fix data errors and organize it properly
- Microsoft Excel-For reviewing and checking the raw data
- PowerPoint-Used to design and present the final dashboard layout
- GitHub-For sharing the project and documentation

## Key Features and Dax Formulas
#### Key Features
- Cleaned and transformed messy data using Power Query
- Extracted Year and Month from inconsistent date formats
- Grouped data by Country and Area to identify top danger zones
- Analyzed body parts most injured using keyword extraction
- Standardized Time of Day values (e.g. “Afternoon”, “Morning”, “Night”)
- Visualized trends in attacks across time, location, and shark species
- Designed a clean, easy-to-use dashboard in Power BI and PowerPoint
- Added slicers to filter data by year, country, and species.
  #### DAX Formulas Created
- Total Female = CALCULATE(COUNTROWS('Shark Attack'), 'Shark Attack'[Sex] = "F")
- Total Male = CALCULATE(COUNTROWS('Shark Attack'), 'Shark Attack'[Sex] = "M")
- Total Attacks = COUNTROWS('Shark Attack')
- Average Age = AVERAGE('Shark Attack'[Age])

## Project Workflow
- Data Collection:
 Imported shark attack data from Cvs file into Power BI.
- Data Cleaning (Power Query):
- Removed unnecessary columns and rows with errors.
- Cleaned and formatted inconsistent date, time, gender, and age fields.
- Extracted year, month, and time of day from raw date/time text.
- Data Modeling:
  Ensured proper data types and relationships were in place.
- Created a clean model to support analysis and visuals.
- DAX Calculations:
  Created key measures like Total Attacks, Total Female, Total Male, and Average Age.
- Data Visualization (Power BI & PowerPoint)
- Designed a simple dashboard with slicers and visuals.
  Used charts to show yearly trends, top countries, body parts injured, and shark species.
- Insights Generation:
  Identified patterns in attacks by location, gender, species, and time of day.
  Highlighted key findings with clear visuals.
- Dashboard Export & Documentation.

## Business Questions
- Question 1:
  Make a graph of the number of shark attacks annually over time since 1900. What trends do you see?
- Question 2:
  Which countries report the most shark attacks? Within those countries, which areas and locations seem
  to be the most dangerous?
- Question 3:
  The next questions will require you to practice your data cleaning skills. The data is pretty raw, and will
  need some work before you analyze it.
- Question 4:
  What body parts are most often injured? (hint: you'll need to perform text analysis on the Injury column)
- Question 5:
  Are shark attacks more common during certain parts of the day (again, the Time data isn't quite ready to
  go. You may need to transform it before analyzing)
- Question 6:
  Which species of shark are attacking most often? (you guessed it... this data is messy too!)

## Analysis and Insights
All insights in this analysis were drawn directly from the Shark Attack dataset using various charts and visuals. The key findings include:
- Shark Attacks Over the Years:
 The number of shark attacks has changed over time, with a rise in recent decades-especially from the 1900 onward.
- Top Countries Affected:
 Countries like the United States, Australia, and South Africa recorded the highest number of shark attacks. In these countries, specific  coastal regions were hotspots.
- Time of Day:
 Most attacks occurred in the afternoon, followed by morning and midday—common times for beach and water activity.
- Common Body Parts Injured:
  The legs, feet, and hands were the most commonly injured, showing that attacks often happen while victims are in the water.
- Shark Species Involved:
  Species like the Great White Shark, Tiger Shark, and Bull Shark were the most commonly identified in attacks.
 Each of these insights was supported with visual dashboards created in Power BI and summarized to help understand trends and patterns     clearly.

## Recommendations
- Teach People About Shark Safety:
  People who swim or surf in the ocean should be told when sharks are most active and how to stay safe.

- Use Warning Systems:
 Beaches in places with many shark attacks should have warning systems to alert people if sharks are nearby.

- Avoid Risky Times:
 People should avoid swimming in the late afternoon or evening when shark attacks are more likely.

- Keep Learning About Sharks:
  More studies should be done to understand where and why shark attacks happen so better plans can be made.

## Conclusion
This project has successfully explored shark attacks over the last 100+ years. Using Power BI, we cleaned and analyzed messy data, created interactive visuals, and drew clear insights about where, when, and how shark attacks happen. These insights can help guide public safety efforts and raise awareness.

## Author
Happiness Friday Bassey - Data Analyst

