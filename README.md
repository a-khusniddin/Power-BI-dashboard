# Data Jobs Dashboard using Power BI

<img width="800" height="449" alt="overview" src="https://github.com/user-attachments/assets/7ee3009e-1406-4696-b4c5-5d195037c789" />


## Introduction

This dashboard simplifies the job hunt for career switchers and data professionals by bringing scattered market data into one place. Powered by a real-world dataset of 2023–2025 data science job postings, the intuitive platform allows users to effortlessly explore salary ranges, roles, and location trends.

### Dashboard File
Here is the dashboard file: [`Data_Jobs_Dashboard.pbix`](Data_Jobs_Dashboard.pbix).  

## Tools Utilized


* **⚙️ Data Transformation (ETL):** Utilized Power Query to clean, shape, and prepare raw data—expertly handling missing values, correcting data types, and engineering custom columns for deeper analysis.
* **🧮 DAX & KPI Modeling:** Formulated explicit measures to calculate essential performance metrics, including `Median Yearly Salary` and total `Job Count`.
* **📈 Advanced Visualizations:** Deployed line, area, column, and bar charts to track hiring trends over time, alongside interactive map charts for global geographic distribution.
* **🎨 UI/UX & Dashboard Design:** Structured a cohesive, intuitive layout blending standard and specialized visuals to maximize readability and tell a compelling data story.
* **🖱️ Interactive Reporting Features:**
* **🔍 Dynamic Filtering:** Implemented slicers for seamless, on-the-fly exploration by job title.
* **🗺️ Custom Navigation:** Configured buttons and bookmarks to create an app-like user experience.
* **🔍 Contextual Drill-Throughs:** Enabled users to dive effortlessly from high-level summaries into granular, detailed data tables.
## Dashboard Overview

### 🔍 Page 1: Market View

<img width="800" height="447" alt="page1" src="https://github.com/user-attachments/assets/29f9df4e-f636-40d3-a484-f9710ccd54e8" />


This main page serves as your starting point, turning millions of complicated data points into a single, easy-to-read screen. It gives you a quick look at the entire data job market so you don't have to guess what's happening.

**Key Features:**

* **Quick Stats:** Instantly see total open positions (`Job Count`), overall satisfaction (`Job Rating`), and middle-of-the-road pay rates.
* **Hiring Trends:** Watch how hiring goes up and down over time using the interactive timeline chart.
* **Job Comparison:** Easily compare salaries for different data roles using a simple scatter plot and a detailed breakdown table.

___

### 🎯 Page 2: Job Title Drill-Through

<img width="800" height="445" alt="page2" src="https://github.com/user-attachments/assets/2f2a6256-d080-4bc2-bec2-f3024cfbe42e" />


This is the deep-dive page of the project! By right-clicking a specific job title on the first page, you can "drill through" to this view to unlock detailed facts and figures tailored to just that role.

**Key Features:**

* **Salary Ranges:** See the lowest, highest, and average pay scales for your specific role.
* **Remote Work Stats:** Find out how many positions offer work-from-home options versus in-office requirements.
* **Top Job Boards:** Learn which hiring platforms list the most openings for that exact title.
* **Global Job Map:** Use an interactive map to see exactly where in the world these jobs are located.

## Conclusion

This dashboard shows how Power BI can take millions of messy job listings and turn them into a clear career map. Instead of guessing or endlessly searching through job boards, users can click around the data to find real salary ranges, remote work options, and hiring hotspots. It changes career planning from a guessing game into a smart, data-backed strategy.
