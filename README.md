# 📊 Invoice & Payments Dashboard - Power BI

![Payment Dashboard](https://github.com/user-attachments/assets/3c52521e-5bf0-4a89-88b3-861c7d68ae4e)


## 📌 Project Summary

Businesses often struggle with reconciling **bulk customer payments** against **multiple invoices**. Typically, they do this manually in Excel, marking invoices as fully or partially paid — a process that is labor-intensive, error-prone, and time-consuming.

To solve this, I built a **Power BI Dashboard** that:

✅ Automatically allocates invoices against bulk payments  
✅ Tracks customer-level payment history and outstanding balances  
✅ Clearly shows whether a customer has fully paid or has pending invoices  

---

## 💡 Key Features & Design Highlights

This dashboard isn’t flashy — it’s clean, fast, and **optimized for clarity and usability**.

### 🔍 Functional Highlights

- **Auto-matching of invoices with payments**, including partial payments  
- **Real-time tracking** of invoice status (paid/unpaid/partially paid)  
- **Customer-wise breakdown** of invoices, receipts, and balances  
- Supports **month-end and time series comparisons**  

### 🎨 Design Decisions That Matter

1. **Dynamic slicer label**: Shows `"Data as on Sep-18 ending"` clearly at the top  
2. **Red alert dot 🔴**: Highlights customers with unpaid balances instantly  
3. **Title = Legend**: Billing in red, Receipts in green – no extra legend needed  
4. **Clear table headers**: Straight to the point (e.g., `27 Invoices | 0 unpaid`)  
5. **Subtle checkmark ✔**: Paid invoices marked neatly  
6. **Green pipe 🟩**: Clean visual indicator of receipts next to the column  
7. **Intentional whitespace**: Breathable layout, no unnecessary boxes or clutter  

---

## 🧱 Tech Stack

- **Tool**: Power BI  
- **Data Sources**: Simulated Excel files for invoices and payments  
- **Language**: DAX (for measures, logic, KPIs)  
- **Visualization Type**: Line charts, tables, card KPIs, conditional formatting  

---

## 🚀 Live Demo

🔗 **Live Dashboard**: [Click here to view the Power BI Dashboard](https://app.powerbi.com/view?r=eyJrIjoiNThhOWRkZTUtNzQzMi00NThlLWJmNGQtMzIyZGUyMTA3ZjRkIiwidCI6IjRjZmE2ZjViLTU5ZTYtNGJhOS04YmRkLTVhZjQ5ZTQ1OTI1NiJ9)

---

## 📁 Files Included

- `Dataset` – Dashboard Data  
- `Invoice and Payment Dashboard PowerBI.pbix` file 
- `README.md` – You're reading it ✅  

---

## 🚀 How to Use This Project

1. Clone or download this repo  
2. Open the `.pbix` file in Power BI Desktop  
3. Replace the data sources with your own invoice and payment data  
4. Refresh the dashboard and explore dynamic insights

---

## 📞 Contact

If you have questions, feedback, or want to collaborate:

**Name**: Deepak Dhanoliya  
**LinkedIn**: [Click here to view profile](https://www.linkedin.com/in/deepakdhanoliya/) 
**Email**: your.email@example.com

---

## 🙏 Acknowledgements

🧠 This dashboard was inspired by a tutorial by [Chandeep Chhabra (Goodly)](https://www.youtube.com/@GoodlyChandeep).  
Thanks for sharing valuable knowledge with the data community!

---

> ⚠️ Note: This dashboard is designed for learning and demonstration. Customize it to fit your company or client’s real billing structure.

