Malloy Project
This repository contains an analytical project using Malloy, a modern language for data modeling and querying. The project leverages Malloy's capabilities to analyze incidents and program-level event data, integrating multiple datasets with relationships across abuse allegations, medical/mental health issues, and agency notifications.

📂 Project Structure
Data Sources
The project includes various CSV and Parquet files, structured into Malloy sources:

Incident Reports (incident): Data on reported incidents, including notification dates and agencies.
Abuse Allegations (abuse_allegation): Linked with abuse types to categorize cases.
Medical/Mental Health Issues (mm_allegation): Tracks mental and medical allegations with corresponding issue categories.
Programs & Categories (cate, program_allegation, category_map_data): Contains metadata about programs, states, and incident categories.
SIR Event Data (sir_event_data): Includes events mapped to programs and their respective creation dates.
