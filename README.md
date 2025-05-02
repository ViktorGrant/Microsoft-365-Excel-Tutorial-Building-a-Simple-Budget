# Microsoft-365-Excel-Tutorial-Building-a-Simple-Budget
This tutorial introduces key Microsoft 365 tools and provides a hands-on walkthrough of Excel by creating and managing a personal budget

# 💰 Microsoft 365 Excel Budget Tutorial

## ✅ Step 1: Open Microsoft 365
- Go to [www.microsoft365.com](https://www.microsoft365.com)
- Create a **free** account if needed

>  <img width="1263" alt="Home Page Image" src="https://github.com/user-attachments/assets/368c82cb-cf85-4d01-bf3d-e34bc31e78ca" />
 
> *The Home page should look like this*

---

## ✅ Step 2: Open Excel
- Click the **Excel** icon on the left side  
- Or click the 3 dots (**...**) → *View more apps*  
- Open a new Excel sheet

---

## ✅ Step 3: Create 3 Tables

### 📊 Income Table
- 2 Columns: `Date`, `Income`, `Amount`

### 📊 Expenses Table
- 3 Columns: `Date`, `Expense`, `Amount`

### 📊 Savings Table
- 4 Columns: `Month`, `Initial Saved`, `Withdraw Amount`, `End`

> 🖼️ **Tables Image**  
> *The tables should look something like this (Note: they have different sections)*

---

## ✅ Step 4: Fill Out the Tables

### Income Table

| Date       | Income       | Amount |
|------------|--------------|--------|
| 5/1/2025   | Job          | 3000   |
| 5/7/2025   | Side Hustle  | 500    |
| 5/12/2025  | Sold Clothes | 50     |

### Expenses Table

| Date       | Expense      | Amount |
|------------|--------------|--------|
| 5/1/2025   | Rent         | 1000   |
| 5/1/2025   | Utilities    | 200    |
| 5/3/2025   | Lunch        | 12     |

### Savings Table

| Month     | Initial Saved | Withdraw Amount | End   |
|-----------|----------------|------------------|--------|
| January   | 2338          | 0                | 2338   |
| February  | 0             | 0                | 0      |
| March     | 0             | 0                | 0      |
| April     | 0             | 0                | 0      |
| May       | 0             | 0                | 0      |
| June      | 0             | 0                | 0      |
| July      | 0             | 0                | 0      |
| August    | 0             | 0                | 0      |
| September | 0             | 0                | 0      |
| October   | 0             | 0                | 0      |
| November  | 0             | 0                | 0      |
| December  | 0             | 0                | 0      |

---

## ✅ Step 5: Totals

Make sure each section includes a **Totals row** at the bottom:
- Income → Total Income
- Expenses → Total Expenses
- Savings → Total Saved

---

## ✅ Step 6: Formulas

Add the **Income Amounts** column together into the totals cell with this formula:  
`=SUM(C2:C100)`  
*(Replace `C2:C100` with your actual range)*

Add the **Expenses Amounts** column together into the totals cell with this formula:  
`=SUM(F2:F100)`

Have the **“End”** cell from the savings block be the total of Initial saved minus withdrawn with this formula:  
`=H2 - I2`  
*(Assuming H = Initial and I = Withdraw)*

Add all the **“End”** column cells together to get the total yearly saved:  
`=SUM(J2:J13)`  
*(Assuming J holds the “End” values for each month)*

