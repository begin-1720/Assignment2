Assignment 2

This project was completed as part of a data science assignment focused on real-world insurance data processing. The tasks were implemented using **pure Python**, without relying on libraries like pandas, numpy, or csv.
 Assignment Tasks Completed:

 Task 1: Data Cleaning

* Processed a raw CSV file using basic Python file operations.
* Handled missing, null, and invalid values manually.
* Converted numerical values to appropriate types (int, float).
* Cleaned data was stored as a list of dictionaries for further analysis.

Task 2: City-wise Claim Analysis

* Analyzed April 2025 claim data for four cities: Pune, Kolkata, Ranchi, and Guwahati.
* Aggregated total claims, premiums collected, and paid amounts.
* Calculated settlement ratios.
* Based on financial and operational metrics, **Ranchi** was recommended for closure.

 Task 3: Rejection Remark Classification

* Debugged and corrected a faulty `complex_rejection_classifier` function.
* Applied the function to classify textual rejection reasons.
* Added a new column `REJECTION_CLASS` using only pure Python (no pandas `.apply()`).

 Tech Stack

* Python 3.x
* No external libraries (compliant with assignment constraints)

 Files Included

* `Assignment_2.ipynb` – Final notebook containing all tasks
* `rejection_reason.py` – Original classifier script (corrected inline)
* `Insurance_auto_data.csv` – Dataset provided for analysis


