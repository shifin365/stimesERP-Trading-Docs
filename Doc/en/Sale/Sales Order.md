# Sales Order

The **Sales Order** module allows businesses to create, manage, and process customer orders effortlessly. It integrates seamlessly with quotation and delivery workflows, ensuring smooth operations.

---

## Accessing Sales Order Dashboard

### Step 1: Navigate to **Sale > Sales Order**

> This opens the **Sales Order Dashboard**, where you can:
> - View all sales orders categorized as Draft or Approved.
> - Use the Search or Advanced Filters for refined results.

<img src="../images/sale order dashboard.png" alt="sale order dashboard" style="border-radius: 10px; width: 70%; height: 70%; border: 0.5px solid #333;">

---

## Exporting to Excel

You can export all sales order data by clicking the **Export to Excel** button for quick reporting and analysis.

---

## Creating a New Sales Order

Follow these steps to create a new sales order:

### Step 1: Click **Create New**

This will open the Sales Order form to capture all relevant details.

---

### **1. Document Information**

| Field                   | Description                                                                 |
|-------------------------|-----------------------------------------------------------------------------|
| **Document Number Series** | Auto-generated. Configure via 👉 [Document Series Settings](<direct%20purchase.md>). |
| **Date**                | Specify the order date.                                                   |

---

### **2. Price and Customer Details**

| Field                  | Description                                                                 |
|------------------------|-----------------------------------------------------------------------------|
| **Price Type**         | Choose from Wholesale, Retail, or Regular. Configure via 👉 [Price Type Settings](<direct%20purchase.md>). |
| **Customer**           | Select the customer from the dropdown. Add new customers via 👉 [Customer Menu](<direct%20purchase.md>). |
| **Due Amount**         | Displays the outstanding amount for the selected customer.                 |
| **Quotation Button**   | If the customer has prior quotations, click to view and select an existing one. |

<div style="display: flex; gap: 10px;">
  <img src="../images/customer in sale order.png" style="width: 100%; border-radius: 10px; border: 0.5px solid #333;">
  <img src="../images/quotation taking SO.png" style="width: 100%; border-radius: 10px; border: 0.5px solid #333;">
</div>

---

### **3. Item Selection and Pricing Details**

If a quotation is selected, the item details and pricing will auto-populate.

| Field              | Description                                                               |
|--------------------|---------------------------------------------------------------------------|
| **Item Details**    | Auto-populated from the selected quotation.                               |
| **Tax**             | If applicable, tax (e.g., UAE VAT, India GST) will be added based on the item details. |

<img src="../images/item coming from quotation so.png" alt="item coming from quotation so" style="border-radius: 10px; width: 70%; height: 70%; border: 0.5px solid #333;">

---

### **4. Additional Information**

| Field                   | Description                                                               |
|-------------------------|---------------------------------------------------------------------------|
| **Store**               | Select the store for the sales order. Configure via 👉 [Store Settings](<direct%20purchase.md>). |
| **Salesperson**         | Assign a salesperson. Create new ones via 👉 [Salesperson Settings](<direct%20purchase.md>). |
| **Expected Delivery Date** | Specify the expected delivery date for the order.                        |
| **Project**             | Link the sales order to a project if required. Configure via 👉 [Project Settings](<direct%20purchase.md>). |

---

### **5. Financial Details**

| Field                   | Description                                                               |
|-------------------------|---------------------------------------------------------------------------|
| **Customer Order Number** | Add the order number from the customer.                                  |
| **Reference Number**      | Enter any relevant reference number.                                      |
| **PO Number and Date**    | If applicable, enter the purchase order number and date.                   |
| **Serial Number**         | Add serial numbers for any machines or products.                          |
| **Cost Center**           | Link the order to a cost center if needed.                                |

<img src="../images/Financial Details in SO.png" alt="Financial Details in SO" style="border-radius: 10px; width: 70%; height: 70%; border: 0.5px solid #333;">

---

### **6. Saving and Approving Sales Order**

- **Save**: Once all details are entered, click **Save** to create the sales order.
- **Approve**: After saving, click **Approve** to finalize the order.

<img src="../images/approved so.png" alt="approved so" style="border-radius: 10px; width: 70%; height: 70%; border: 0.5px solid #333;">

---

## Next Step

Once the sales order is approved, the next step is to create a **Delivery Note**. Learn more in the 👉 [Delivery Note](<direct%20purchase.md>) guide.

🎉 **Congratulations!** You've successfully created and approved a sales order. Keep it up! 😊