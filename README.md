📊 Stack Overflow Developer Survey 2024 – Data Analysis

* Author: Haidar Dagham
* Date: 2025
* Tools & Technologies Used:
  - Python Libraries: `pandas`, `numpy`, `seaborn`, `matplotlib`, `plotly`, `sqlite3`
  - Notebook Environments: Jupyter Notebook
  - SQL & Querying: SQL syntax for data querying and filtering
  - Cloud Platforms: IBM Cloud
  - BI & Visualization Tools: IBM Cognos Analytics, PowerPoint
  - Version Control: Git & GitHub

---

📌 Introduction

Stack Overflow, the go-to platform for developers, conducted a global survey to capture insights into the developer community. This survey includes various questions related to professional experience, coding activities, tools, technologies, and preferences. The dataset offers important information about the current state of software development worldwide.

In this lab, we will work with a subset of the original dataset to explore, analyze, and visualize various trends. The survey data consists of responses from developers with different professional backgrounds, educational levels and geographic locations.

---

📌 Dataset Source

The dataset is available as part of the Stack Overflow Developer Survey under an Open Database License (ODbL).
To access the full data set at this link:  
https://stackoverflow.blog/2024/08/06/2024-developer-survey/

📌 Column Description for Survey Data

| Column Name              | Question Text                                                                 |
|------------------------|-------------------------------------------------------------------------------|
| ResponseId             | Randomized respondent ID number.                                              |
| MainBranch             | Which of the following options best describes you today?                      |
| Age                    | What is your age?                                                             |
| Employment             | What is your current employment status?                                       |
| RemoteWork             | How often do you work remotely?                                               |
| Check                  | Various verification or check questions related to survey consistency.        |
| CodingActivities       | What coding activities do you engage in (hobby, professional, and open-source contributions)? |
| EdLevel                | What is the highest level of formal education you have completed?             |
| LearnCode              | How did you learn to code?                                                    |
| LearnCodeOnline        | Have you used online resources to learn coding?                               |
| TechDoc                | How do you use technical documentation?                                       |
| YearsCode              | How many years have you been coding?                                          |
| YearsCodePro           | How many years have you coded professionally?                                 |
| DevType                | What is your role or type of development work you do?                         |
| OrgSize                | What is the size of the organization you work for?                            |
| PurchaseInfluence      | How much influence do you have on purchasing technology at your company?      |
| BuyNewTool             | How does your company decide whether to buy new tools or technology?          |
| BuildvsBuy             | Does your company prefer to build or buy software?                            |
| TechEndorse            | Do you endorse any specific technologies at your company?                     |
| Country                | In which country do you reside?                                               |
| Currency               | Which currency do you use day-to-day?                                         |
| CompTotal              | What is your current total compensation (salary, bonuses, and so on)?         |
| LanguageHaveWorkedWith | Which programming languages have you worked with in the past year?            |
| LanguageWantToWorkWith | Which programming languages do you want to work with in the future?           |
| LanguageAdmired        | Which programming languages do you admire most?                               |
| DatabaseHaveWorkedWith | Which database technologies have you worked with in the past year?            |
| DatabaseWantToWorkWith | Which database technologies do you want to work with in the future?           |
| DatabaseAdmired        | Which database technologies do you admire most?                               |
| PlatformHaveWorkedWith | Which platforms have you worked with in the past year?                        |
| PlatformWantToWorkWith | Which platforms do you want to work with in the future?                       |
| PlatformAdmired        | Which platforms do you admire most?                                           |
| WebframeHaveWorkedWith | Which web frameworks have you worked with in the past year?                   |
| WebframeWantToWorkWith | Which web frameworks do you want to work with in the future?                  |
| WebframeAdmired        | Which web frameworks do you admire most?                                      |
| EmbeddedHaveWorkedWith | Which embedded systems have you worked with in the past year?                 |
| EmbeddedWantToWorkWith | Which embedded systems do you want to work with in the future?                |
| EmbeddedAdmired        | Which embedded systems do you admire most?                                    |
| MiscTechHaveWorkedWith | Which miscellaneous technologies have you worked with in the past year?       |
| MiscTechWantToWorkWith | Which miscellaneous technologies do you want to work with in the future?      |
| MiscTechAdmired        | Which miscellaneous technologies do you admire most?                          |
| OpSysPersonal          | What operating systems do you use for personal tasks?                         |
| OpSysProfessional      | What operating systems do you use for professional tasks?                     |
| SOVisitFreq            | How frequently do you visit Stack Overflow?                                   |
| SOAccount              | Do you have a Stack Overflow account?                                         |
| SOPartFreq             | How often do you participate in Q&A on Stack Overflow?                        |
| AISelect               | How do you feel about artificial intelligence tools for development?          |
| AIBen                  | What benefits have you experienced from using AI tools?                       |
| AIChallenges           | What challenges have you faced while using AI tools?                          |
| JobSat                 | How satisfied are you with your current job?                                  |
________________________________________



---

📌 Project Overview

This project analyzes the Stack Overflow Developer Survey 2024. It explores trends in:
- Programming languages
- Databases
- Platforms
- Developer demographics

The insights serve as a valuable resource for developers, educators, recruiters, and tech strategists.

---

📁 Folder Structure

📂 data/ → Raw & cleaned datasets

📂 notebooks/ → Jupyter Notebook for analysis & visualizations

📂 presentations/ → Executive summary presentation (PPTX)

📂 dashboards/ → Cognos dashboard exports (images or PDFs)

📄 README.md → Project summary


---

🧠 Methodology

- Data Cleaning: Removed null values, renamed columns, and standardized formats.
- Exploration: Visualized developer trends using bar charts, pie charts, and heatmaps.
- Dashboarding: Used IBM Cognos to create three main dashboards:
  - Current Tech Usage
  - Future Tech Trends
  - Developer Demographics

---

📈 Key Findings

- Languages: JavaScript and HTML/CSS lead in usage today; Python is gaining future interest rapidly.
- Databases: PostgreSQL is the dominant technology both now and for future plans.
- Cloud Platforms: AWS and Azure are widely adopted and still growing.
- Demographics: Most respondents are aged 25–34 with a bachelor's or master's degree.

---

💼 Applications

- Supports hiring strategies and developer training programs
- Supports curriculum planning for coding education
- Helps devs align with future market demands

---

📊 Presentation & Dashboard

- 📁 presentations/StackOverflow-Developer-Survey-2024_Presentation.pptx
- 📂 dashboards/ — contains 3 dashboard views exported from IBM Cognos.

---

📝 How to Run the Code

1. Clone the repository
2. Open StackOverflow-Developer-Survey-2024_Notebook.ipynb in Jupyter NoteBook
3. Ensure you have required libraries installed.
4. Run all cells for complete analysis and charts

---

📬 Contact

For questions or feedback, feel free to connect with me:  
📧 DaghamHaidar@gmail.com  
🔗 [GitHub – HaidarDagham
(https://github.com/haidardagham)


