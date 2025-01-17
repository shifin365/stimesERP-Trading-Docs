# Direct Sale Module

The **Direct Sale** feature is used to manage immediate product sales. It allows users to create, manage, and approve sales transactions efficiently.

---

## Accessing Direct Sale Dashboard

### Step 1: Navigate to **Sale > Direct Sale**

> This opens the **Direct Sale Dashboard**, displaying all direct sales categorized as **Draft** or **Approved**. Use the **Search Bar** for filtering specific records.

<img src="../images/direct sale dashboard.png" alt="direct sale dashboard" style="border-radius: 10px; width: 70%; height: 70%; border: 0.5px solid #333;">

---

## Exporting Data in Direct Sale

You can export sales data by clicking the **Export** button. Customize the export options:

<div style="text-align:left;">
    <ul>
        <li><strong>Select Size:</strong> Choose from A0, A1, A2, etc.</li>
        <li><strong>Select Shape:</strong> Landscape or Portrait.</li>
        <li><strong>Exclude Header and Footer:</strong> Enable this checkbox for a simplified report.</li>
        <li><strong>Export Format:</strong> Choose between PDF or Excel.</li>
    </ul>
</div>

<img src="../images/export data in direct sale.png" alt="export data in direct sale" style="border-radius: 10px; width: 70%; height: 70%; border: 0.5px solid #333;">

---

## Creating a New Direct Sale

Follow these steps to create a new direct sale:

### Step 1: Click **Create New** in the top-right bar

This opens the Direct Sale form to capture all relevant details.

<img src="../images/ceate new direct sale.png" alt="ceate new direct sale" style="border-radius: 10px; width: 70%; height: 70%; border: 0.5px solid #333;">

---

### **1. Document Information**

| Field                   | Description                                                                 |
|-------------------------|-----------------------------------------------------------------------------|
| **Document Number Series** | Auto-generated by the system. Configure via the 👉 [Document Series Settings](<direct%20purchase.md>). |
| **Date**                | Specify the sale date.                                                   |

---

### **2. Price and Store Details**

| Field                   | Description                                                                 |
|-------------------------|-----------------------------------------------------------------------------|
| **Price Type**          | Choose from **Wholesale**, **Retail**, or **Regular**. Configure via 👉 [Price Type Settings](<direct%20purchase.md>). |
| **Store**               | Select the store for the sale. Configure via 👉 [Store Settings](<direct%20purchase.md>). |

---

### **3. Customer Information**

| Field                   | Description                                                                 |
|-------------------------|-----------------------------------------------------------------------------|
| **Customer**            | Select the customer. Add customers via 👉 [Customer Menu](<direct%20purchase.md>). |
| **Due Amount**          | Displays the outstanding amount for the selected customer.                  |
| **Tax Column**          | If applicable, shows tax (e.g., UAE VAT, India GST).                       |

---

### **4. Salesperson and Project Information**

| Field                   | Description                                                                 |
|-------------------------|-----------------------------------------------------------------------------|
| **Salesperson**         | Assign a salesperson. Create new ones via 👉 [Salesperson Settings](<direct%20purchase.md>). |
| **Project**             | Link the sale to a project. Configure via 👉 [Project Settings](<direct%20purchase.md>). |

<img src="../images/fields in direct sale.png" alt="fields in direct sale" style="border-radius: 10px; width: 70%; height: 70%; border: 0.5px solid #333;">

---

### **5. Item Selection**

| Field                   | Description                                                                 |
|-------------------------|-----------------------------------------------------------------------------|
| **Item**                | Select the item from the dropdown. Shows current stock, reorder quantity, and average rate. Create new items via 👉 [Item Menu](<direct%20purchase.md>). |
| **Quantity**            | Enter the quantity for the sale. The **Unit** and **Rate** will auto-fill. You can manually adjust the rate if needed. |
| **Add Line**            | Add more items if necessary.                                               |

<img src="../images/item in direct sale.png" alt="item in direct sale" style="border-radius: 10px; width: 70%; height: 70%; border: 0.5px solid #333;">

---

### **6. Financial Details**

| Field                   | Description                                                                 |
|-------------------------|-----------------------------------------------------------------------------|
| **Subtotal**            | Automatically calculated.                                                   |
| **Discount**            | Apply a discount if applicable.                                             |
| **Adjust Amount**       | Add or subtract adjustments.                                               |
| **Additional Details**  | Reference Number, PO Number, SL Number (for Machines), Customer Branch, etc. |

---

### **7. Payment Options**

Select the payment type from the following options:

#### Credit
| Field                   | Description                                                                 |
|-------------------------|-----------------------------------------------------------------------------|
| **Payment Term**        | Choose from: **Due End of the Month**, **Due End of Next Month**, **Due on Receipt**, or **Custom**. |
| **Due Date**            | Auto-updates based on selected term.                                        |

#### Cash
| Field                   | Description                                                                 |
|-------------------------|-----------------------------------------------------------------------------|
| **Cost Center**         | Configure via 👉 [Cost Center Settings](<direct%20purchase.md>).             |
| **Cash Account**        | Configure via 👉 [Cash Account Settings](<direct%20purchase.md>).            |
| **Cash Repository**     | Configure via 👉 [Cash Repository Settings](<direct%20purchase.md>).         |

#### Cheque
| Field                   | Description                                                                 |
|-------------------------|-----------------------------------------------------------------------------|
| **Cheque Number**       | Enter the cheque number.                                                    |
| **Cheque Date**         | Select the cheque date.                                                     |

#### Bank
| Field                   | Description                                                                 |
|-------------------------|-----------------------------------------------------------------------------|
| **Bank**                | Configure via 👉 [Bank Settings](<direct%20purchase.md>).                    |
| **Bank Transaction Code** | Add Bank Posted Date, Instrument Code, and Transaction Code.              |

<div style="display: flex; gap: 10px;">
  <img src="../images/payment optionin direct sale.png" style="width: 100%; border-radius: 10px; border: 0.5px solid #333;">
  <img src="../images/payment add in direct sale.png" style="width: 100%; border-radius: 10px; border: 0.5px solid #333;">
  <img src="../images/multiple payment mode in direct sale.png" style="width: 100%; border-radius: 10px; border: 0.5px solid #333;">
</div>

---

### **8. Saving and Exporting Direct Sale**

Once all details are entered, click **Save**.

> A **PDF** of the direct sale will be generated.

---

### **9. Post-Save Options**

After saving, the top-right bar provides the following options:

<div style="text-align:left;">
    <ul>
        <li><strong>Back:</strong> Return to the dashboard.</li>
        <li><strong>Preview Settings:</strong> Customize the document preview.</li>
        <li><strong>Previous Preview:</strong> View previous document versions.</li>
        <li><strong>New Create:</strong> Start a new direct sale.</li>
        <li><strong>Edit:</strong> Modify the document (before approval only).</li>
        <li><strong>Delete:</strong> Remove the document.</li>
        <li><strong>Print:</strong> Print the sale record.</li>
        <li><strong>Download:</strong> Export the document.</li>
        <li><strong>Download Without Header and Footer:</strong> Export a clean version.</li>
        <li><strong>Go To > Stock Ledger:</strong> View the stock movement ledger.</li>
        <li><strong>Go To > Provisional Account Ledger:</strong> View account details.</li>
    </ul>
</div>

---

### **10. Approval Workflow**

> Approve the sale by clicking **Action > Approve**.

Once approved:
- The status changes from **Draft** to **Approved**.
- The **Approve** button becomes **Withdraw**.
- Editing is disabled after approval.

<img src="../images/approved direct sale.png" alt="approved direct sale" style="border-radius: 10px; width: 70%; height: 70%; border: 0.5px solid #333;">

---

## Next Step: Receipt Confirmation

Proceed to the **Receipt module** to confirm the receipt for the approved sale. For more details, refer to 👉 [Receipt](<direct%20purchase.md>).

🎉 **Congratulations!** You've successfully managed a direct sale with ease!