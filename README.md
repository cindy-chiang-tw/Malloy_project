# Allegations in the UAC SIR Dataset
# Background
This project analyzes program-level events and allegations within the Unaccompanied Alien Children (UAC) Significant Incident Report (SIR) dataset. The dataset includes reports on various incidents, including allegations of abuse, medical and mental health concerns, and program-level events. Understanding these events is critical for identifying trends, evaluating reporting effectiveness, and informing policy decisions.

However, due to privacy and legal restrictions, some key data points are missing, limiting certain aspects of our analysis.


# Motivation
The goal of this project is to:

Identify trends in incident reports across different programs and categories.
Analyze reporting effectiveness, including internal investigations, state licensing reports, and law enforcement involvement.
Understand gaps in the data and highlight limitations in incident classification.
This analysis can provide insights for policymakers, program administrators, and researchers to improve incident tracking and response strategies.

# Visualization
## Count incidents by agency_Bar chart
![image](https://github.com/user-attachments/assets/1f9cb4dd-4d70-47dc-bb67-d6cd638ca3b1)
## Incidents by Notification List Subtype_Line chart
![image](https://github.com/user-attachments/assets/50b784fb-12a8-491a-aaa1-5a7557334119)
## Incidents by Notification Method_Bar chart
![image](https://github.com/user-attachments/assets/e0bcf378-b4b2-47d5-9940-a627b520b091)
## Abuse type allocation_Bar chart
![image](https://github.com/user-attachments/assets/e18f5a7f-b567-4a6c-b351-4f03e65bf307)
## Program level case allocation_ Bar chart
![image](https://github.com/user-attachments/assets/34e085f9-a823-4a55-8590-580ef906ee97)







# Summary of Findings
Key Insights:
High Number of Unclassified Cases:

A significant portion of incidents fall under "Other Abuse" due to vague classifications. This suggests potential underreporting or data limitations.
Lack of Identifiable SIR IDs:

SIR ID definitions are missing, making it difficult to track cases over time or across categories.
Investigation Outcomes Are Sparse:

Many incidents lack details on internal investigations, law enforcement actions, or state licensing reviews, raising questions about incident resolution.
Most Reported Incidents Relate to Medical and Mental Health Issues:

This suggests a high prevalence of medical concerns, emphasizing the need for better program support for mental health services.
Certain Programs Have Disproportionate Incident Reports:

Some programs consistently report higher numbers of incidents, which may indicate staffing, policy, or oversight issues.
# Data Cleaning and Processing
Due to the dataset's complexity, several preprocessing steps were necessary:

## Date Standardization:
Reformatted all date fields using try_strptime!date to ensure consistency.
## Data Joins:
Merged abuse allegations, medical issues, program-level events, and category mappings to create a more comprehensive dataset.
## Missing Values Handling:
Many fields had missing values, particularly in investigation outcomes and follow-ups.
## Classification of Incident Types:
Due to privacy limitations, many incidents are categorized as "Other Abuse", making deeper analysis difficult.

# Limitations and Challenges
While this dataset provides valuable insights, several challenges limit its full potential:

# Privacy and Legal Constraints:
Many fields are redacted or missing, limiting detailed case tracking.
Lack of SIR ID Definitions:
Without clear SIR ID mappings, cross-referencing cases over time is difficult.
Broad Categorization of Incidents:
Many cases fall under "Other Abuse", reducing specificity in the analysis.
Missing Investigation Data:
Follow-up actions from state licensing and law enforcement are frequently absent.
Future Directions
Despite these limitations, this work lays the foundation for further research. Future improvements could include:

# Advocating for Better Data Transparency:
Standardized reporting guidelines could improve data availability.
Machine Learning for Incident Classification:
Natural language processing (NLP) techniques could categorize incidents more effectively.
Expanding Data Sources:
Integrating external reports on program performance, staffing levels, and funding may enhance the analysis.
