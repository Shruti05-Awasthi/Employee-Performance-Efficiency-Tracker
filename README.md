# 📊 Employee Performance & Efficiency Tracker

This project showcases a **practical, CSV-based system** used for measuring, tracking, and analyzing employee productivity and task efficiency within a team setting. It is designed to move beyond simple task completion status and quantify performance using key analytical metrics.

---

## ✨ Key Features & Analytical Metrics

The tracker utilizes raw data to generate calculated metrics that drive performance insights:

### 1. Efficiency Percentage (Efficiency %)

This metric calculates how effectively an employee uses time by comparing the hours they were expected to take versus the hours they actually took.

* **Formula:** $$\text{Efficiency \%} = \left(\frac{\text{Total Estimated Hours}}{\text{Total Actual Hours}}\right) \times 100$$
* **Interpretation:**
    * **> 100%:** Tasks were completed **ahead** of schedule (Highly Efficient).
    * **< 100%:** Tasks took **longer** than estimated (Needs Improvement).

### 2. Performance Rating

The final rating (e.g., **EXCELLENT**, **GOOD**, **AVERAGE**, **POOR**) is derived by a defined set of business logic, often combining the Efficiency % and the overall Task Completion Rate.

---

## 📁 Repository Structure

The project uses two CSV files, each serving a distinct purpose in the workflow:

| File Name | Purpose | Data Contained |
| :--- | :--- | :--- |
| **Tracker.xlsx - Data Entry Sheet.csv** | **Raw Input Log:** The source file where daily/weekly task details are recorded. | Estimated Hours, Actual Hours, Assignment Details, Task Status. |
| **Tracker.xlsx - Tracker.csv** | **Calculated Output:** The aggregated, analyzed output based on the raw data. | Total Tasks, Total Hours, **Final Efficiency %**, and **Performance Rating**. |

---

## 🛠️ Future Scope

This repository provides a solid data foundation that can be utilized for advanced projects:

1.  **Data Visualization:** Integrate this CSV data into tools like **Power BI** or **Tableau** to create an interactive dashboard for management reporting.
