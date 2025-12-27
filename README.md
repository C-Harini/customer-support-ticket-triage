# Customer Support Ticket Triage System
 Week-1 Internship Project
 Project Overview
Companies receive a large number of customer support tickets every day. Some issues are urgent while others are normal.  
This project implements a **rule-based Python system** to automatically analyze customer support tickets, classify the issue type, assign priority levels, calculate SLA response time, and generate management reports.

The goal of this project is to simulate how **real-world support ticket triage systems** work in industry.



 Tools & Technologies Used
- Python
- Google Colab
- GitHub
- Pandas (for data processing)



 Dataset
- Source: Kaggle (Customer Support Tickets Dataset)
- Format: CSV
- Main column used: `Ticket Description`



 Project Workflow

1. **Load & Explore Dataset**
   - Checked number of rows and columns
   - Verified missing values
   - Viewed sample customer tickets

2. **Text Cleaning**
   - Converted text to lowercase
   - Removed special characters and extra spaces
   - Created a new column `cleaned_text`

3. **Issue Classification (Rule-Based)**
   Tickets were classified into the following categories:
   - PAYMENT
   - LOGIN
   - DELIVERY
   - REFUND
   - BUG
   - GENERAL

4. **Priority Assignment**
   Assigned priority levels based on keywords:
   - P0 (Critical)
   - P1 (High)
   - P2 (Medium)
   - P3 (Low)

5. **SLA & Due Time Calculation**
   - SLA hours assigned based on priority
   - Due time calculated using current time + SLA hours

6. **Support Manager Report**
   - Issue category summary
   - Priority level summary
   - Urgent ticket snapshot (P0 & P1)
   - Reports exported as CSV files

7. **Final Output**
   - Full processed dataset exported as a final CSV file



 Output Files
- `final_ticket_output.csv` – Final processed ticket data
- `issue_summary_report.csv` – Issue category summary
- `priority_summary_report.csv` – Priority level summary

---

 How to Run the Project
1. Open the notebook `Week1_Customer_Support_Triage.ipynb` in Google Colab
2. Upload the dataset CSV when prompted
3. Run all cells sequentially
4. Download the generated output CSV files from the Files panel

---
 Learning Outcomes
- Hands-on experience with real-world data
- Understanding of rule-based decision systems
- Practical use of Python for data processing
- Experience using Google Colab and GitHub professionally

---

Note
This project focuses on **logic and workflow**, not machine learning.  
The priority and classification rules are intentionally simple to reflect a beginner-friendly, industry-style implementation.

---
Author
C Harini  


