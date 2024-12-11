# Purchase Order

The Purchase Order feature enables users to manage purchase requests systematically by specifying required items, delivery dates, and supplier details. Here's an overview of the module:

---

## Accessing Purchase Order

### Step 1: Navigate to **Purchase > Purchase Order**

> This opens the **Purchase Order Dashboard**, which displays all purchase orders categorized as Draft or Approved, and if enabled, with Withdrawn Data.

<img src="../images/purchase order dashboard.png" alt="purchase order dashboard" style="border-radius: 10px; width: 70%; height: 70%; border: 0.5px solid #333;">

---

## Exporting to Excel

You can export Purchase Orders from the dashboard into an Excel file for easy tracking and reporting.

---

## Filtering Options

The dashboard provides various filtering options for managing and locating purchase orders.

| Filter              | Description                                                              |
|---------------------|--------------------------------------------------------------------------|
| **Search**          | Locate orders using keywords.                                            |
| **Document Number** | Filter by document number.                                               |
| **Min-Max Book Date** | Filter purchases based on booking date range.                           |
| **Reference Number** | Search by reference number.                                             |
| **Supplier Name**   | Locate purchases by supplier name.                                       |
| **Verification Status** | Filter by status (e.g., Draft, Approved, All).                       |
| **Tax**             | Filter purchases by specific tax types.                                  |
| **Show Withdrawn Entry** | Include withdrawn purchases in results.     

<img src="../images/filtering in purchase order dashboard.png" alt="filtering in purchase order dashboard" style="border-radius: 10px; width: 70%; height: 70%; border: 0.5px solid #333;">

---

## Creating a New Purchase Order

### Step 1: Click **Create New**

This opens a new form for creating the purchase order. Fill in the following details:

<img src="../images/create new purchase order.png" alt="create new purchase order" style="border-radius: 10px; width: 70%; height: 70%; border: 0.5px solid #333;">

---

### **1. Document Information**

| Field                   | Description                                                                 |
|-------------------------|-----------------------------------------------------------------------------|
| **Document Number Series** | Auto-generated. Configure via the 👉 [Document Series Settings](<direct%20purchase.md>). |
| **Date**                | Select the date of the purchase.                                            |

---

### **2. Supplier Information**

| Field                  | Description                                                                 |
|------------------------|-----------------------------------------------------------------------------|
| **Supplier**           | Select the supplier from the dropdown. Add new suppliers via 👉 [Supplier Menu](<direct%20purchase.md>). |
| **Supplier Tax Settings** | If applicable, select the tax type (e.g., VAT, GST).                        |
| **Expected Delivery Date** | Specify the expected delivery date for the items.                        |
| **Project** | Link the purchase to a project. Configure projects here: [Set Projects](<direct purchase.md>)                        |

<img src="../images/field in purchase order.png" alt="field in purchase order" style="border-radius: 10px; width: 70%; height: 70%; border: 0.5px solid #333;">

### Item Selection

Choose the item from the dropdown. Items display current stock, reorder quantity, and average rate. Add or edit items here: [Add Items](<direct purchase.md>). After selecting an item:

<img src="../images/item dropdown in purchase order.png" alt="item dropdown in purchase order" style="border-radius: 10px; width: 70%; height: 70%; border: 0.5px solid #333;">

---

### **3. Item Selection**

| Field                 | Description                                                                 |
|-----------------------|-----------------------------------------------------------------------------|
| **Item**              | Select items from the dropdown. View stock, reorder quantity, and rate.     |
| **Quantity**          | Enter the quantity. The unit is auto-filled.                               |
| **Rate**              | The rate auto-fills based on item settings but can be edited.               |
| **Total**             | The total price will be calculated automatically.                           |

<img src="../images/auto calculation in purchase order.png" alt="auto calculation in purchase order" style="border-radius: 10px; width: 70%; height: 70%; border: 0.5px solid #333;">

---

### **4. Additional Details**

<img src="../images/reference in purchase order.png" alt="reference in purchase order" style="border-radius: 10px; width: 70%; height: 70%; border: 0.5px solid #333;">

| Field                   | Description                                                                 |
|-------------------------|-----------------------------------------------------------------------------|
| **Statement Reference** | Add any relevant notes or statements.                                       |
| **LPO No. and LPO Date** | Enter the Local Purchase Order number and date.                             |
| **Container No.**       | Add a container number if needed.                                           |
| **Message**             | Include any additional message.                                             |

Billing Address: Choose a billing address. 👉 [Set Billing Address](<direct%20purchase.md>)<br>
Shipping Address: Specify the shipping address. 👉 [Set Shipping Address](<direct%20purchase.md>)<br>
Terms and Conditions: Select pre-configured terms from the dropdown. 👉 [Set Terms and Conditions](<direct%20purchase.md>). Also enter custom terms if necessary.

<img src="../images/Terms and Conditions in purchase order.png" alt="Terms and Conditions in purchase order" style="border-radius: 10px; width: 70%; height: 70%; border: 0.5px solid #333;">

---

### **5. Saving and Exporting**

After filling out the details: Click **Save** to generate the purchase order. A PDF of the purchase order will be available for download or print.

---

### **6. Actions on a Saved Purchase Order**

| Action                  | Description                                                              |
|-------------------------|--------------------------------------------------------------------------|
| **Back**                | Return to the dashboard.                                                 |
| **Preview Settings**    | Customize the document preview.                                          |
| **New Create**          | Start a new direct purchase.                                             |
| **Edit**                | Modify the document (before approval only).                              |
| **Delete**              | Remove the document.                                                     |
| **Print**               | Print the purchase record.                                               |
| **Download**            | Export the document.                                                     |
| **Download Without Header and Footer** | Export a clean version of the document.                            |

<img src="../images/top bar in purchase order.png" alt="top bar in purchase order" style="border-radius: 10px; width: 70%; height: 70%; border: 0.5px solid #333;">

---

### **7. Approval Workflow**

- Use the **Approve** option to finalize the purchase order.
- Once approved:
  - The status changes from Draft to Approved.
  - The **Approve** button changes to **Withdraw**.

<div style="display: flex; gap: 10px;">
  <img src="../images/draft and approve in purchase order.png" style="width: 100%; border-radius: 10px; border: 0.5px solid #333;">
  <img src="../images/approved and withdraw in purchase order.png" style="width: 100%; border-radius: 10px; border: 0.5px solid #333;">
</div>

---

### **8. Editing Restrictions**

Once a purchase order is approved, it cannot be edited.

---

## Next Steps

After the purchase order is approved, proceed to the **Goods Received Note (GRN)**. 👉 [Learn More About GRN](<direct%20purchase.md>).

---

🎉 **Congratulations!** You’ve successfully created and managed a Purchase Order!