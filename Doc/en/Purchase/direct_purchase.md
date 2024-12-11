# Direct Purchase

The **Direct Purchase** feature allows businesses to directly record procurement transactions without creating a purchase order. Here's a simple and detailed guide to using the **Direct Purchase** module.

---

## Accessing Direct Purchase

### Step 1: Navigate to **Purchase > Direct Purchase**

> This opens the **Direct Purchase Dashboard**, which displays:
> - All direct purchases categorized as Draft, Approved, and Withdrawn (if the checkbox is enabled).
> - Options to search or use advanced filters for refined results.

<img src="../images/direct purchase.png" alt="direct purchase" style="border-radius: 10px; width: 70%; height: 70%; border: 0.5px solid #333;">

---

## Exporting to Excel

You can export all direct purchase data by clicking the **Export to Excel** button for easy reporting and analysis.

---

## Filtering Direct Purchases

The Direct Purchase Dashboard includes advanced filtering options for easier management of records:

- **Search**: Find specific purchases quickly.
- **Document Number**: Search by document number.
- **Min-Max Book Date**: Filter by booking date range.
- **Min-Max Due Date**: Filter by due date range.
- **Reference Number**: Search by reference numbers.
- **Supplier Name**: Locate purchases by supplier.
- **Document Status**: Filter by status (e.g., Draft, Approved).
- **Tax**: Filter by tax type.
- **Show Withdrawn Entry**: Check this box to include withdrawn purchases.

<img src="../images/Filtering Direct Purchases.png" alt="Filtering Direct Purchases" style="border-radius: 10px; width: 70%; height: 70%; border: 0.5px solid #333;">

---

## Creating a New Direct Purchase

### Step 1: Click **Create New**

Click the **Create New** button in the top-right corner to open the Direct Purchase form.

<img src="../images/create new direct purchase.png" alt="create new direct purchase" style="border-radius: 10px; width: 70%; height: 70%; border: 0.5px solid #333;">

---

### **1. Document Information**

| Field                  | Description                                                       |
|------------------------|-------------------------------------------------------------------|
| **Document Number Series** | Auto-generated. Configure via the 👉 [Document Series Settings](<direct_purchase.md>). |
| **Date**               | Select the date of the purchase.                                  |

<div style="display: flex; gap: 10px;">
  <img src="../images/document series in direct purchase.png" style="width: 100%; border-radius: 10px; border: 0.5px solid #333;">
  <img src="../images/date in direct purchase.png" style="width: 100%; border-radius: 10px; border: 0.5px solid #333;">
</div>

---

### **2. Supplier and Price Details**

| Field                  | Description                                                       |
|------------------------|-------------------------------------------------------------------|
| **Supplier**           | Select the supplier. The due amount is auto-filled for that supplier. When selecting a supplier during Direct Purchase creation, the tax settings associated with the supplier will be applied automatically. Add suppliers via 👉 [Supplier Menu](<direct_purchase.md>). |
| **Price Type**         | Choose a price type (Wholesale, Retail, Regular). Configure via 👉 [Price Types](<direct_purchase.md>). |
| **Store**              | Choose the delivery store. Configure stores via 👉 [Store Settings](<direct_purchase.md>). |
| **Project**              | Link the purchase to a project. Configure projects via 👉 [Set Projects](<direct_purchase.md>). |

<div style="display: flex; gap: 10px;">
  <img src="../images/price type in direct purchase.png" style="width: 100%; border-radius: 10px; border: 0.5px solid #333;">
  <img src="../images/store in direct purchase.png" style="width: 100%; border-radius: 10px; border: 0.5px solid #333;">
  <img src="../images/supplier in direct purchase.png" style="width: 100%; border-radius: 10px; border: 0.5px solid #333;">
  <img src="../images/project in direct purchase.png" style="width: 100%; border-radius: 10px; border: 0.5px solid #333;">
</div>

---

### **3. Item Selection and Quantity**

| Field                  | Description                                                       |
|------------------------|-------------------------------------------------------------------|
| **Item**               | Select the item to purchase. Add/edit items via 👉 [Item Settings](<direct_purchase.md>). |
| **Quantity**           | Enter the quantity you wish to purchase. The unit and rate will auto-fill. |

<div style="display: flex; gap: 10px;">
  <img src="../images/item dropdown in direct purchase.png" style="width: 100%; border-radius: 10px; border: 0.5px solid #333;">
  <img src="../images/auto calculation in direct purchase.png" style="width: 100%; border-radius: 10px; border: 0.5px solid #333;">
</div>

---

### **4. Additional Details**

<img src="../images/reference in direct purchase.png" alt="reference in direct purchase" style="border-radius: 10px; width: 70%; height: 70%; border: 0.5px solid #333;">

| Field                    | Description                                                       |
|--------------------------|-------------------------------------------------------------------|
| **Reference Number**      | Add a reference number if applicable.                             |
| **LPO No**                | Add the LPO number (if available).                                |
| **LPO Date**              | Specify the LPO date.                                             |

---

### **5. Payment Details**

Choose the payment type that matches your transaction.

<img src="../images/payment details in direct purchase.png" alt="payment details in direct purchase" style="border-radius: 10px; width: 70%; height: 70%; border: 0.5px solid #333;">

- **Credit**: Select payment terms (e.g., Due next month, Due on receipt).
- **Cash**: Specify Cash Account and Repository.

<div style="display: flex; gap: 10px;">
  <img src="../images/credit payment type in direct purchase.png" style="width: 100%; border-radius: 10px; border: 0.5px solid #333;">
  <img src="../images/cash payment type in direct purchase.png" style="width: 100%; border-radius: 10px; border: 0.5px solid #333;">
</div>

- **Cheque**: Add cheque number and date.
- **Bank**: Enter bank details (Bank, Instrument Code).

<div style="display: flex; gap: 10px;">
  <img src="../images/cheque payment type in direct purchase.png" style="width: 100%; border-radius: 10px; border: 0.5px solid #333;">
  <img src="../images/bank payment type in direct purchase.png" style="width: 100%; border-radius: 10px; border: 0.5px solid #333;">
</div>

---

### **6. Saving and Exporting Direct Purchase**

After entering all details:

- **Save**: Click **Save** to create the direct purchase.
- **Export**: You can print or download the purchase document, with options to customize the preview, print, or export as PDF.

<div style="text-align:left;">
    <ul>
        <li><strong>Back:</strong> Return to the dashboard.</li>
        <li><strong>Preview Settings:</strong> Customize the document preview.</li>
        <li><strong>Previous Preview:</strong> View previous document versions.</li>
        <li><strong>New Create:</strong> Start a new direct purchase.</li>
        <li><strong>Edit:</strong> Modify the document (before approval only).</li>
        <li><strong>Delete:</strong> Remove the document.</li>
        <li><strong>Print:</strong> Print the purchase record.</li>
        <li><strong>Download:</strong> Export the document.</li>
        <li><strong>Download Without Header and Footer:</strong> Export a clean version.</li>
        <li><strong>Go To > Provisional Account Ledger:</strong> View account details.</li>
    </ul>
</div>

<div style="display: flex; gap: 10px;">
  <img src="../images/top bar in direct purchase after create.png" style="width: 100%; border-radius: 10px; border: 0.5px solid #333;">
  <img src="../images/Provisional Account Ledger.png" style="width: 100%; border-radius: 10px; border: 0.5px solid #333;">
</div>

---

## Approval Workflow

Once you’ve completed the purchase details:

- **Approve**: After saving, use the **Approve** button to finalize the purchase.
- **Withdraw**: After approval, the status changes to **Approved**, and the **Withdraw** option becomes available.

<div style="display: flex; gap: 10px;">
  <img src="../images/draft and approve in direct purchase.png" style="width: 100%; border-radius: 10px; border: 0.5px solid #333;">
  <img src="../images/approved and withdraw in direct purchase.png" style="width: 100%; border-radius: 10px; border: 0.5px solid #333;">
</div>

---

## Next Steps

After approving the direct purchase:

> Proceed to Payments to complete the transaction. Learn more about 👉 [Payments](<direct_purchase.md>).

🎉 **Congratulations!** You’ve successfully managed a direct purchase! 🎉