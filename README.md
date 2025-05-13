# 📊 Automated Financial Report Generation using Python & Pandas

This project automates the processing of financial data from CSV/Excel files. It generates a tax summary report, detects data inconsistencies (like missing or invalid values), and emails the reports to stakeholders — all using Python.

 
---


## 🚀 Features

- ✅ Load and clean financial transaction data
- 📈 Generate a summary report by category (e.g., Income vs Expense)
- ⚠️ Detect and list data inconsistencies (e.g., missing amounts or descriptions)
- 📤 Automatically email reports to specified recipients with attachments
- 🔒 Gmail SMTP support using secure App Passwords

---



## Output Files

- tax_summary_report.csv: Total amounts grouped by category (Income/Expense)
- data_issues.csv: List of rows with missing or invalid entries 



## 🧰 Technologies Used

- Python 3.8+
- Pandas
- Regex (for data validation, if extended)
- smtplib & email.message (for sending emails)



## 📬 Email Integration (Gmail Setup)

To enable automated email sending via Gmail:

- Enable 2-Step Verification on your Google account.
- Create a Gmail App Password from your Google Account Security Settings.
- Replace the SMTP credentials in send_email_report():
  
  ```bash
    server.login("your_email@gmail.com", "your_app_password") 




## 🧪 How to Run

1. **Clone the repository:**
   
   ```bash
   git clone https://github.com/yourusername/financial-report-automation.git
   cd financial-report-automation

2. **Install dependencies:**
   
   ```bash
   pip install pandas

3. **Run the Jupyter notebook:**
   
   ```bash
   jupyter notebook automated_financial_report.ipynb



## 🙋‍♀️ Author

Mariya Khan
📧 mariyak9122@gmail.com
💼 Aspiring Data Scientist | Python & Automation Enthusiast
