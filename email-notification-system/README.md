# 📧 Email Notification System using UiPath

This UiPath automation project reads task data from an Excel file and sends automated email reminders to team members based on upcoming due dates. It helps streamline communication and improve efficiency by eliminating manual email follow-ups.

---

## ✅ Features

- Reads project milestone data from an Excel file
- Sends personalized task reminder emails via SMTP
- Filters tasks based on due date and status
- Displays a confirmation message after all emails are sent
- Reduces manual communication effort by up to 75%

---

## 🛠 Technologies Used

- **UiPath Studio (RPA)**
- **Excel**
- **SMTP (Gmail/Outlook) Email Integration**

---

## 📂 Project Structure

Email-Notification-System/
│
├── Main.xaml # Main workflow
├── project.json # UiPath project metadata
├── ProjectMilestones.xlsx # Sample input Excel file
└── README.md # Project documentation

---

## 📊 Excel File Format

The Excel file (`ProjectMilestones.xlsx`) should contain the following columns:

| Task Name      | Due Date   | Assigned To   | Email ID                 | Status  |
|----------------|------------|---------------|------------------------- |---------|
| Design Mockups | 2025-05-15 | Alice Johnson | alice@example.com        | Pending |
| Code Backend   | 2025-05-16 | Bob Smith     | bob@example.com          | Pending |

---

## 🚀 How to Run

1. Open `Main.xaml` in **UiPath Studio**.
2. Update the file path in **Excel Application Scope** to match your system.
3. Configure the **SMTP connection** (e.g., Gmail or Outlook):
   - Server: `smtp.gmail.com`
   - Port: `587`
   - Email & App Password
4. Run the bot.
5. After processing, a pop-up window will confirm that emails were sent successfully.

---

## 🔐 Note on Email Setup

To use Gmail:
- Enable [2-Step Verification](https://myaccount.google.com/security)
- Create an [App Password](https://myaccount.google.com/apppasswords) and use it in SMTP connection

---

## 📌 Future Enhancements

- Add overdue reminders
- Log email delivery status to Excel or CSV
- Support attachments with email
- Add real-time alerts via Teams/Slack or SMS

---

## 🙌 Author

**Riddhi More**  
*Automating with love using UiPath 💙*

---

## 📃 License

This project is for educational and demonstration purposes.
