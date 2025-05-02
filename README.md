# Microsoft 365 Tutorial: Excel Budget
This tutorial introduces key Microsoft 365 tools and provides a hands-on walkthrough of Excel by creating and managing a personal budget

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

<img width="1018" alt="Budget Tables Empty" src="https://github.com/user-attachments/assets/1dca103c-6d41-47da-911d-c9b2870944ce" />

> - The tables should look something like this (Note: they have different sections)
> - Feel free to use whatever colors you like :)

---

## ✅ Step 4: Fill Out the Tables


- Take the tables you have and fill them out to look like the ones below. Add Expenses, Income streams, Months for the savings sections, Etc



<img width="1015" alt="Budget Tables Complete" src="https://github.com/user-attachments/assets/9c147dc7-a8ab-42ff-b36b-6c68d4a8774a" />
- The Budget Tables complete with details (Expenses, income, etc)

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

