# 🎓 Course Learning Calendar - Smart Excel Tracker

This project is an Excel-based tool designed to help you manage and track your progress across multiple online courses. It's perfect for self-paced learners who want a clean, automated view of their deadlines and course statuses.

## 📁 Features

- ✅ Auto-calculates **remaining days** until course deadlines  
- 🎯 Dynamically assigns a **Deadline Status**:  
  - `Overdue ❗`  
  - `Due Soon 🚧`  
  - `On Track 💪`  
  - `Congrats 🎉` for completed courses  
- 📅 Supports start/end dates and current progress updates  
- 🧠 Smart conditional logic with Excel formulas  
- 📊 Great example of using Excel for productivity and learning analytics

## 🔧 Technologies Used

- Microsoft Excel  
- IF/OR logic formulas  
- Conditional formatting  
- Date calculations

## 💡 Use Cases

- Learning plan tracking  
- Academic or upskilling calendar  
- Habit or goal management in Excel  
- Productivity dashboard sample for portfolios

## 📷 Screenshot

![image](https://github.com/user-attachments/assets/a7d74f48-9beb-40f9-a550-24c3430c0c95)


## 🧪 Sample Formula

```excel
=IF(D2="Done", "Congrats 🎉", IF(OR(E2="", ISBLANK(E2)), "", IF(E2<0, "Overdue ❗", IF(E2<=7, "Due Soon 🚧", "On Track 💪"))))

