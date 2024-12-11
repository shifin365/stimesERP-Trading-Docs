# Purchase Return

A Purchase Return is a process where goods purchased from a supplier are returned due to reasons like defects, incorrect items, or excess quantity.

## Accessing Purchase Return

> Navigate to **Purchase > Purchase Return** to access the Purchase Return dashboard.

- **Purchase Return Dashboard**: The dashboard displays all purchase return records, categorized as Draft, Approved, and optionally with Withdrawn Data if the checkbox is enabled.

<img src="../images/PR DASHBOARD.png" alt="PR DASHBOARD" style="border-radius: 10px; width: 70%; height: 70%; border: 0.5px solid #333;">

---

## Dashboard Features

### Filters
Filter purchase return records using the **Search** option.

### Export to Excel
Export all records (Draft, Approved, or Withdrawn) to Excel using the **Export** option for quick reporting.

---

## Creating a New Purchase Return

Click **Create New**: Use the **Create New** button in the top-right corner of the dashboard to open the purchase return form.

<img src="../images/PR CREATE NEW.png" alt="cPR CREATE NEW" style="border-radius: 10px; width: 70%; height: 70%; border: 0.5px solid #333;">

---

### **Document Information**

| Field                | Description                                                                 |
|----------------------|-----------------------------------------------------------------------------|
| **Document Number Series** | Configure through [Document Series Settings](<../Purchase/direct_purchase.md>)  |
| **Date**             | Select the date of the return.                                               |

<img src="../images/PR FIELDS.png" alt="PR FIELDS" style="border-radius: 10px; width: 70%; height: 70%; border: 0.5px solid #333;">

---

### **Supplier Selection**

| Field            | Description                                                                 |
|------------------|-----------------------------------------------------------------------------|
| **Supplier**     | Select the supplier from the dropdown. Add new suppliers via [Supplier Menu](<direct%20purchase.md>). |
| **Get Button**   | Retrieve purchase data by selecting **Direct Purchase** or **GRN (Goods Receipt Note)**. |

- **GRN**: Select the record number from the GRN. This will auto-populate the details.
- **Direct Purchase**: Manually select and add items for return.

<div style="display: flex; gap: 10px;">
  <img src="../images/PR DATA TAKING BASED ON DP OR GRN.png" style="width: 100%; border-radius: 10px; border: 0.5px solid #333;">
  <img src="../images/PR RECORD SELECTION USING GRN.png" style="width: 100%; border-radius: 10px; border: 0.5px solid #333;">
  <img src="../images/PR BASED ON ITEM UNDER RECORD NO.png" style="width: 100%; border-radius: 10px; border: 0.5px solid #333;">
</div>

---

### **Item Details**

Select the items to return and enter the quantity for each item. Specify the store from which the stock is being returned.

<img src="../images/PR ITEM SECTION.png" alt="PR ITEM SECTION" style="border-radius: 10px; width: 70%; height: 70%; border: 0.5px solid #333;">

---

### **Additional Fields for Reference**

| Field                | Description                                        |
|----------------------|----------------------------------------------------|
| **Reference Number** | Optional reference number.                        |
| **Statement Reference** | Provide additional reference details, if needed. |

---

### **Price Type**

Choose the price type (Wholesale, Retail, or Regular). Price types can be configured through [Price Types Settings](<direct purchase.md>).

---

### **Payment Details**

Select the **Payment Type**:

- **Cash**
- **Bank**
- **Cheque**
- **Credit**

Payment types can be configured via [Payment Types Settings](<direct purchase.md>).

<img src="../images/PR PAYMENT TYPE.png" alt="PR PAYMENT TYPE" style="border-radius: 10px; width: 70%; height: 70%; border: 0.5px solid #333;">

---

### **Credit Payment Term**

Choose a payment term and due date option:

- Due at the end of next month
- Due at the end of the month
- Due on receipt
- Custom due date

---

### **Cash Payment Configuration**

Set up **Cost Centers**, **Cash Accounts**, and **Cash Repositories** via the [Cost Centers](<direct purchase.md>), [Cash Accounts](<direct purchase.md>), and [Cash Repository](<direct purchase.md>) settings.

---

### **Cheque Payment Configuration**

Set up **Cost Centers** and **Bank** details. Enter the **Cheque Number** and **Cheque Date**.

---

### **Bank Payment Configuration**

Set up **Cost Centers** and **Bank** details. Enter the **Bank Posted Date**, **Instrument Code**, and **Bank Transaction Code**.

---

### Saving and Exporting

After entering the purchase return details, you can save the document and export it:

- **Back**: Return to the dashboard.
- **Preview Settings**: Customize the document preview.
- **Previous Preview**: View previous document versions.
- **New Create**: Start a new purchase return.
- **Edit**: Modify the document (before approval only).
- **Delete**: Remove the document.
- **Print**: Print the purchase record.
- **Download**: Export the document in various formats (with or without headers).
- **Stock Ledger**: View the stock movement ledger.
- **Provisional Account Ledger**: View account details.

<div style="display: flex; gap: 10px;">
  <img src="../images/PR STOCK LEDGER.png" style="width: 100%; border-radius: 10px; border: 0.5px solid #333;">
  <img src="../images/PR PROVISIONAL.png" style="width: 100%; border-radius: 10px; border: 0.5px solid #333;">
</div>

---

### **Approval Workflow**

After completing the purchase return, click the **Approve** button to finalize the return.

- The status changes from **Draft** to **Approved**.
- Once approved, you can withdraw or edit the return.

<img src="../images/PR PRINT.png" alt="PR PRINT" style="border-radius: 10px; width: 70%; height: 70%; border: 0.5px solid #333;">

---

### Next Step

After the Purchase Return is approved, proceed to update the stock or financial records accordingly.

---

🎉 **Congratulations!** You’ve successfully managed a Purchase Return with ease!