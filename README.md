# YouTube Channel Performance Analysis & Reporting Automation

A Python script designed to automate the process of analyzing YouTube video performance. It generates anonymized data, automatically categorizes videos, calculates key performance metrics, and exports the results into a new Google Sheet for easy reporting and visualization.

This project demonstrates skills in data manipulation, text processing, automation, and cloud platform integration.

---

### 📊 Final Dashboard

The data processed by this script is used to power an interactive dashboard in Looker Studio, allowing for easy monitoring of content performance.
<img width="1066" height="798" alt="{59CE9A1D-9712-4910-9A26-44E8718D7788}" src="https://github.com/user-attachments/assets/5ba16b47-f6fa-49cb-a527-466c76cc4ce0" />


---

### ✨ Key Features

-   **Dummy Data Generation**: Creates realistic, portfolio-safe data that mimics real-world YouTube metrics, ensuring client confidentiality.
-   **Text-Based Categorization**: Automatically classifies videos into predefined categories using keyword matching (`regex`) in video titles.
-   **Data Aggregation**: Utilizes `pandas` to efficiently calculate key metrics per category, such as total views, total watch time, and average click-through rate.
-   **Cloud Integration & Automation**: Securely authenticates with the Google Cloud Platform and automates the creation of a new Google Sheet, delivering a ready-to-use report.

---

### 🛠️ Technologies Used

-   **Language**: `Python`
-   **Data Manipulation**: `pandas`, `NumPy`
-   **Cloud Integration**: `gspread`, `google-auth`
-   **Environment**: `Google Colab`

---

### 🚀 How to Run

1.  **Prerequisites**: Ensure you have a Google Cloud Platform project set up with the necessary API permissions (Google Drive API, Google Sheets API).
2.  **Environment**: Open the `.ipynb` file in Google Colab.
3.  **Authentication**: Run the authentication cell to grant access to your Google account.
4.  **Execute**: Run all cells in the notebook.
5.  **Output**: A link to the newly created Google Sheet will be printed in the output upon successful completion.
