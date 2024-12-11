# Purchase Invoice

A **Purchase Invoice** is a document that records the supplier's bill for goods or services purchased. It serves as the basis for payment processing and is essential for both accounting and inventory management. Let's make handling your purchase invoices simple and efficient!

---

## Accessing Purchase Invoice

### Step 1: Navigate to **Purchase > Purchase Invoice**

> This opens the **Purchase Invoice Dashboard**, where you can manage all invoices, from Draft to Approved.

<img src="../images/purchase invoice dashboard.png" alt="purchase invoice dashboard" style="border-radius: 10px; width: 70%; height: 70%; border: 0.5px solid #333;">

---

## Dashboard Features

### **Filters**

Use the following filters to search and narrow down purchase invoices:

- **Search**
- **Document Number**
- **Min-Max Book Date**
- **Min-Max Due Date**
- **Reference Number**
- **Document Status**
- **Show Withdrawn Entry**

<img src="../images/purchase invoice filter.png" alt="purchase invoice filter" style="border-radius: 10px; width: 70%; height: 70%; border: 0.5px solid #333;">

---

### **Export to Excel**

For quick reporting and analysis, click **Export to Excel** to download all purchase invoice data (Draft, Approved, or Withdrawn).

---

## Creating a New Purchase Invoice

### Step 1: Click **Create New**

This will open the Purchase Invoice form where you can input all the necessary details.

<img src="../images/create new purchase invoice.png" alt="create new purchase invoice" style="border-radius: 10px; width: 70%; height: 70%; border: 0.5px solid #333;">

---

### **1. Document Information**

| Field              | Description                                              |
|--------------------|----------------------------------------------------------|
| **Document Number Series** | Auto-generated. Configure via [Document Series Settings](<../Purchase/direct_purchase.md>). |
| **Date**           | Select the date of the purchase invoice.                 |
| **Payment Term & Due Date**   | Choose the payment term for this invoice also select the payment due date               |
| **Price Type**       | Choose the pricing type (e.g., Wholesale, Retail).                             |

<img src="../images/purchase invoice fields.png" alt="purchase invoice fields" style="border-radius: 10px; width: 70%; height: 70%; border: 0.5px solid #333;">

---

### **2. Supplier Information**

| Field              | Description                                               |
|--------------------|-----------------------------------------------------------|
| **Supplier**       | Select the supplier from the dropdown. If the supplier has associated Purchase Orders, an Order button will appear. Clicking the button will display all orders linked to the supplier. Selecting an order auto-populates its items and details into the invoice. Add new suppliers via [Supplier Menu](<direct%20purchase.md>). |
| **Order Button**   | If the supplier has associated Purchase Orders, click **Order** to auto-populate items into the invoice. |

#### **Invoice Based on Previous Documents**

You can create a purchase invoice based on:

- Purchase Order
- Goods Receipt Note (GRN)
- Landed Cost Voucher

<div style="display: flex; gap: 10px;">
  <img src="../images/purchase invoice based on order,grn,lcv.png" style="width: 100%; border-radius: 10px; border: 0.5px solid #333;">
  <img src="../images/purchase invoice based on grn.png" style="width: 100%; border-radius: 10px; border: 0.5px solid #333;">
  <img src="../images/purchase invoice based on grn items.png" style="width: 100%; border-radius: 10px; border: 0.5px solid #333;">
</div>

---

### **3. Item and Pricing Details**

| Field               | Description                                                    |
|---------------------|---------------------------------------------------------------|
| **Price Type**      | Choose the pricing type (e.g., Wholesale, Retail).            |
| **Quantity**        | Enter the number of items purchased.                          |
| **Unit Price**      | Specify the price per unit.                                    |
| **Tax Settings**    | Select tax settings for the supplier (e.g., UAE VAT, India GST). |

---

### **4. Project Information**

| Field              | Description                                               |
|--------------------|-----------------------------------------------------------|
| **Project**        | Link the purchase to a project (if applicable). Configure projects via [Project Settings](<direct%20purchase.md>). |

---

### **5. Additional Details**

| Field               | Description                                        |
|---------------------|----------------------------------------------------|
| **Reference Number**| Add a unique identifier for the invoice.           |
| **Statement Reference** | Provide any additional notes or references.   |

---

### **6. Save and Generate PDF**

After entering all the details, click **Save** to create the purchase invoice. You can then generate a PDF version of the invoice.

<img src="../images/purchase invoice print.png" alt="purchase invoice print" style="border-radius: 10px; width: 70%; height: 70%; border: 0.5px solid #333;">

---

## Post-Save Options

Once saved, you have the following options:

- **Back**: Return to the dashboard.
- **Preview Settings**: Customize how the invoice will appear.
- **New Create**: Start a new purchase invoice.
- **Edit**: Modify the document (before approval).
- **Delete**: Remove the document.
- **Print**: Print the invoice.
- **Download**: Export the invoice as a file.
- **Download Without Header and Footer**: Export a clean version of the invoice.
- **Provisional Account Ledger**: Access via the **Go To** button.

---

## Approval Workflow

Once the invoice is ready:

- **Approve**: Click **Approve** to finalize the invoice. After approval:
  - The invoice status changes from **Draft** to **Approved**.
  - The **Approve** button becomes a **Withdraw** button, allowing you to reverse the invoice if needed.

---

## Next Steps

After the purchase invoice is approved, the next step is **Making Payment**. Learn more about making payments in the [Payment Guide](<direct%20purchase.md>).

🎉 **Great job!** You've just created and processed a purchase invoice like a pro!

---