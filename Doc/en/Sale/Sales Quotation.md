# Sales Quotation

The **Sales Quotation** module allows you to create, manage, and approve quotations for customers. It seamlessly integrates into the sales order workflow.

---

## Accessing Sales Quotation Dashboard

### Step 1: Navigate to **Sale > Sales Quotation**

> This opens the **Sales Quotation Dashboard**, which displays:
> - All sales quotations categorized as Draft or Approved.
> - Options to Search or use Advanced Filters for refined results.

<img src="../images/Sales Quotation dasboard.png" alt="Sales Quotation dasboard" style="border-radius: 10px; width: 70%; height: 70%; border: 0.5px solid #333;">

---

## Exporting to Excel

Export all sales quotations data by clicking the **Export to Excel** button for quick reporting and analysis.

---

## Creating a New Sales Quotation

<img src="../images/Sales Quotation create new.png" alt="Sales Quotation create new" style="border-radius: 10px; width: 70%; height: 70%; border: 0.5px solid #333;">

Follow these steps to create a new sales quotation:

### Step 1: Click **Create New**

This opens the Sales Quotation form to capture all relevant details.

---

### **1. Document Information**

| Field                   | Description                                                                 |
|-------------------------|-----------------------------------------------------------------------------|
| **Document Number Series** | Auto-generated. Configure via the 👉 [Document Series Settings](<direct%20purchase.md>). |
| **Date**                | Specify the quotation date.                                                   |

---

### **2. Price and Customer Details**

| Field              | Description                                                                 |
|--------------------|-----------------------------------------------------------------------------|
| **Price Type**     | Choose from Wholesale, Retail, or Regular. Configure via 👉 [Price Type Settings](<direct%20purchase.md>). |
| **Customer**       | Select the customer from the dropdown. Add new customers via 👉 [Customer Menu](<direct%20purchase.md>). |
| **Due Amount**     | Displays the outstanding amount for the selected customer.                 |
| **Tax**            | If applicable, tax will be displayed based on the customer's region (e.g., UAE VAT, India GST). |

---

### **3. Salesperson and Project Information**

| Field              | Description                                                                 |
|--------------------|-----------------------------------------------------------------------------|
| **Salesperson**    | Assign a salesperson. Create new ones via 👉 [Salesperson Settings](<direct%20purchase.md>). |
| **Project**        | Link the quotation to a project. Configure via 👉 [Project Settings](<direct%20purchase.md>). |

---

### **4. Item Selection**

| Field              | Description                                                                 |
|--------------------|-----------------------------------------------------------------------------|
| **Item**           | Select the item from the dropdown list. Displays Current Stock, Reorder Quantity, and Average Rate. Create new items via 👉 [Item Menu](<direct%20purchase.md>). |
| **Quantity**       | Enter the quantity to be quoted. The unit and rate will auto-fill based on the item configuration. |
| **Rate**           | The rate is auto-filled based on the item, but can be manually adjusted if needed. |
| **Add Line**       | Click this button to add additional items to the quotation.

<div style="display: flex; gap: 10px;">
  <img src="../images/Sales Quotation fields.png" style="width: 100%; border-radius: 10px; border: 0.5px solid #333;">
  <img src="../images/Sales Quotation item.png" style="width: 100%; border-radius: 10px; border: 0.5px solid #333;">
</div>

---

### **5. Financial Details**

| Field               | Description                                     |
|---------------------|-------------------------------------------------|
| **Subtotal**        | Automatically calculated.                       |
| **Discount**        | Apply any discounts if applicable.              |
| **Adjust Amount**   | Add or subtract adjustments as needed.          |
| **Reference Number**| Add any relevant reference number.             |
| **Cost Center**     | Optionally add a cost center for accounting purposes. |

---

### **6. Saving and Approving Sales Quotation**

- **Save**: After entering all details, click **Save** to create the sales quotation.
- **Approve**: Once saved, click **Approve** to finalize the quotation.

<img src="../images/approved sales quotation.png" alt="approved sales quotation" style="border-radius: 10px; width: 70%; height: 70%; border: 0.5px solid #333;">

---

## Next Steps

After approving the sales quotation:

> You can convert the approved quotation into a sales order. For more details, refer to 👉 [Sales Order](<direct%20purchase.md>).

🎉 **Congratulations!** You’ve successfully created and approved a sales quotation!