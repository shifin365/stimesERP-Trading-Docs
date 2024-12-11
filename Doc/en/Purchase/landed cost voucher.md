# Landed Cost Voucher

A **Landed Cost Voucher (LCV)** is a document used to allocate additional costs incurred on goods purchased, such as freight, customs, and insurance, to accurately reflect the total cost of goods. 

---

## Accessing Landed Cost Voucher

> Navigate to **Purchase > Landed Cost Voucher** to access the LCV dashboard.

<img src="../images/lcv dashboard.png" alt="lcv dashboard" style="border-radius: 10px; width: 70%; height: 70%; border: 0.5px solid #333;">

---

## Dashboard Features

### **Filters**
You can filter Landed Cost Vouchers using the Search option.

### **Export to Excel**
Easily export all vouchers (Draft, Approved, or Withdrawn) to Excel for analysis and reporting.

---

## Creating a New Landed Cost Voucher

To create a new Landed Cost Voucher, click the **Create New** button in the top-right corner of the dashboard.

<img src="../images/create new lcv.png" alt="create new lcv" style="border-radius: 10px; width: 70%; height: 70%; border: 0.5px solid #333;">

---

### **Document Number Series**
Configure the document number series through the [Document Series Settings](<../Purchase/direct_purchase.md>).

### **Date**
Select the **Voucher Date**.

### **Receipt Type**
Choose the receipt type:
- **Type**: Select either **GRN** (Goods Receipt Note) or **Direct Purchase**.
- **Record No**: Select a Record No. from previously approved GRNs.

Once a GRN is selected, fields like **Supplier**, **Grand Total**, **Book Date**, and **Action** will auto-populate. You can:
- **Delete** any unwanted GRNs using the Action column.
- **Add** additional GRNs by clicking the **Add** button in the Action column.

<img src="../images/grn selection in lcv.png" alt="grn selection in lcv" style="border-radius: 10px; width: 70%; height: 70%; border: 0.5px solid #333;">

---

### **Item List**
Click the **Get Item** button to populate the item list section with data from the selected GRN(s). The following details will be auto-fetched:
- **Catalog No.**
- **Item Name**
- **Price**
- **Quantity**

<img src="../images/item in lcv.png" alt="item in lcv" style="border-radius: 10px; width: 70%; height: 70%; border: 0.5px solid #333;">

---

### **Add Additional Charges**
Enter any additional expenses, such as shipping or handling charges, by filling in the following fields:
- **Expense Account**: Select the account to allocate the charge.
- **Amount**: Enter the cost.
- **Description**: Provide a brief explanation of the expense.

You can modify or delete charges using the **Action** button.

The **Cost Factor** will be automatically calculated based on how charges are distributed—by amount or quantity.

<img src="../images/aditional charges adding in lcv.png" alt="aditional charges adding in lcv" style="border-radius: 10px; width: 70%; height: 70%; border: 0.5px solid #333;">

---

### **Additional Data**
Fill in any additional reference details:
- **Reference Number**
- **Statement Reference**

---

### **Save and Generate PDF**
After filling in the details, click **Save** to create the Landed Cost Voucher and generate its PDF.

<img src="../images/print of lcv.png" alt="print of lcv" style="border-radius: 10px; width: 70%; height: 70%; border: 0.5px solid #333;">

---

## Post-Save Options

Once the voucher is saved, you can perform the following actions:
- **Back**: Return to the dashboard.
- **Preview Settings**: Customize the document preview.
- **New Create**: Start a new direct purchase.
- **Edit**: Modify the document (before approval).
- **Delete**: Remove the document.
- **Print**: Print the purchase record.
- **Download**: Export the document in Excel format.
- **Download Without Header and Footer**: Export a clean version without the header/footer.

---

### **Approval Workflow**
After saving, use the **Action** button to **Approve** the Landed Cost Voucher. Once approved:
- The status will change from **Draft** to **Approved**.
- The **Approve** button will change to **Withdraw**.

---

## Next Steps

After approving the Landed Cost Voucher, proceed to create an **Invoice** against this purchase. For further details, 👉 [Learn More About Payment](<direct%20purchase.md>).

---

🎉 **Congratulations!** You’ve successfully handled a Landed Cost Voucher and are ready to move to the next step! 😊