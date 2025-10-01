Clinical Trials Dataset EDA

This project performs Exploratory Data Analysis (EDA) on a clinical trials dataset. The goal is to understand the data, identify patterns, and visualize key insights.

Dataset Columns

Acronym: Short code for study/trial

Interventions: Type of intervention applied in the study

Outcome Measures: Results or endpoints measured

Phases: Clinical trial phase (Phase 1, 2, 3, etc.)

Enrollment: Number of participants

Study Designs: Type of study (Randomized, Observational, etc.)

Other IDs: Additional identifiers

Start Date: Date study began

Primary Completion Date: Expected study completion

Conditions: Medical conditions studied

EDA Steps Performed

Acronym

Counted unique acronyms

Frequency distribution

Bar chart visualization

Interventions

Counted interventions

Top interventions bar chart

Outcome Measures

Count of unique outcomes

Top 10 outcomes bar chart

Word cloud for text analysis

Phases

Frequency distribution

Pie and bar chart visualizations

Handling multi-phase studies

Enrollment

Converted to numeric

Summary statistics (mean, median, min, max)

Boxplot and histogram

Study Designs

Frequency count

Bar chart for top 10 study designs

Optional stacked bar chart vs phases

Other IDs

Checked uniqueness and duplicates

Start / Primary Completion Date

Converted to datetime

Calculated study duration

Histogram of durations

Line chart of studies per year

Conditions

Top 10 most frequent conditions

Bar chart visualization

Tools Used

Python (pandas, matplotlib, seaborn, wordcloud)

Jupyter Notebook

Insights

Most common acronyms, interventions, and outcome measures

Distribution of study phases and designs

Participant enrollment trends

Study duration analysis and trends over years
