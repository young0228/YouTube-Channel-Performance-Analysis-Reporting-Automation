# YouTube Channel Performance Analysis & Reporting Automation

[한국어 버전 (Korean Version)](README_KO.md)

### From Data Cleaning to Business Intelligence: A YouTube Channel Growth Strategy

This project began as a simple request for data cleaning but evolved into a full data consulting initiative. I designed and built a system that transforms scattered YouTube data into a powerful BI dashboard, laying the groundwork for a data-driven channel growth strategy.

---

### 📊 Final Dashboard

The processed data powers an interactive 2-page Looker Studio dashboard, featuring a KPI summary and a deep-dive page for individual video analysis.
<img width="1061" height="805" alt="{7A91AF1C-32EF-4CB1-8262-6E1CC1128C08}" src="https://github.com/user-attachments/assets/d9d1bb3f-dc9a-45d5-b186-1aa684693472" />


---

### 🎯 Project Goal

The primary goal was to systematically categorize a backlog of ~250 videos, analyze performance by category, and derive actionable insights to inform future content strategy.

### ✨ My Role & Key Achievements

As the sole data consultant and developer on this project, my contributions included:

1.  **Data Consulting & Category System Design:**
    * Analyzed the entire video library to propose and define 4 new core content categories (e.g., 'Google Trends & News').
    * Solved complex keyword matching issues (e.g., plurals, compound words) by implementing a `regex`-based word-boundary matching logic, significantly improving classification accuracy.

2.  **Data Processing & Automation Scripting:**
    * Developed a Python script using `pandas` to clean the raw data and automatically tag every video according to the newly designed category system.

3.  **Interactive BI Dashboard Development:**
    * Built a 2-page interactive dashboard in `Looker Studio` with dynamic filters for date ranges and categories, allowing the client to easily explore their data.

4.  **Client Communication & Final Delivery:**
    * Maintained continuous communication to identify and address the client's underlying needs.
    * Packaged and delivered a comprehensive solution including the cleaned Google Sheets, the Looker Studio dashboard, and a summary of the keyword system.

---

### 🛠️ Technologies Used

-   **Language**: `Python`
-   **Data Manipulation**: `pandas`, `NumPy`
-   **Cloud Integration**: `gspread`, `google-auth`
-   **BI Tool**: `Looker Studio`
-   **Environment**: `Google Colab`
