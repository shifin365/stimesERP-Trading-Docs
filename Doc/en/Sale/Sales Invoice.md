# Sales Invoice

The **Sales Invoice** module allows you to create invoices for goods or services delivered to customers. It integrates smoothly with delivery notes and other sales processes to ensure accurate billing.

## Accessing Sales Invoice Dashboard

### Step 1: Navigate to **Sale > Sales Invoice**

> This will open the **Sales Invoice Dashboard**, where you can view:
> - All sales invoices categorized as Draft or Approved.
> - Options to search or use advanced filters for better results.

<img src="../images/sales invoice dashboard.png" alt="sales invoice dashboard" style="border-radius: 10px; width: 70%; height: 70%; border: 0.5px solid #333;">

---

## Exporting to Excel

Click the **Export to Excel** button to export all sales invoice data for reporting and analysis.

---

## Creating a New Sales Invoice

<img src="../images/create new sales invoice.png" alt="create new sales invoice" style="border-radius: 10px; width: 70%; height: 70%; border: 0.5px solid #333;">

Follow these steps to create a new sales invoice:

### Step 1: Click **Create New**

This will open the Sales Invoice form to input all relevant details.

---

### **1. Document Information**

| Field                  | Description                                                                |
|------------------------|----------------------------------------------------------------------------|
| **Document Number Series** | Auto-generated. Configure via 👉 [Document Series Settings](<direct%20purchase.md>). |
| **Date**                | Enter the invoice date.                                                    |

---

### **2. Payment Terms**

| Field               | Description                                                                   |
|---------------------|-------------------------------------------------------------------------------|
| **Payment Term**     | Select the applicable payment term from the dropdown.                         |
| **Due Date**         | Specify the due date for payment.                                             |

---

### **3. Pricing and Customer Details**

| Field              | Description                                                                 |
|--------------------|-----------------------------------------------------------------------------|
| **Price Type**     | Choose the applicable pricing type (e.g., wholesale, retail). Configure via 👉 [Price Type Settings](<direct%20purchase.md>). |
| **Customer**       | Select a customer from the dropdown. Add new customers via 👉 [Customer Menu](<direct%20purchase.md>). |
| **Due Amount**     | Displays any outstanding amount for the selected customer.                   |
| **Get Deliveries** | Click **Get Deliveries** to select the relevant delivery note if available.  |

<div style="display: flex; gap: 10px;">
  <img src="../images/customer selecting in sales invoice.png" style="width: 100%; border-radius: 10px; border: 0.5px solid #333;">
  <img src="../images/select dn from sales invoice.png" style="width: 100%; border-radius: 10px; border: 0.5px solid #333;">
  <img src="../images/auto item added in sales invoice.png" style="width: 100%; border-radius: 10px; border: 0.5px solid #333;">
</div>

The system will automatically fetch:
- Items
- Quantity
- Unit
- Price
- Total Price

---

### **4. Additional Information**

| Field                    | Description                                  |
|--------------------------|----------------------------------------------|
| **Salesperson**           | Assign a salesperson. Create via 👉 [Salesperson Settings](<direct%20purchase.md>). |
| **Project**               | Link the invoice to a project. Configure via 👉 [Project Settings](<direct%20purchase.md>). |
| **Reference Number**      | Add a reference number (optional).          |
| **Statement Reference**   | Provide additional reference details (optional). |
| **Cost Center**           | Select the appropriate cost center (optional). |
| **Terms and Conditions**  | Select the applicable terms and conditions. |

---

### **5. Saving and Approving Sales Invoice**

- **Save**: After entering all details, click **Save** to create the sales invoice.
- **Approve**: Click **Approve** to finalize the invoice and mark it as ready for payment.

<img src="../images/sales invoice generated.png" alt="sales invoice generated" style="border-radius: 10px; width: 70%; height: 70%; border: 0.5px solid #333;">

---

## Next Steps

After approving the sales invoice:

> If payment has been received, proceed to generate a Receipt 👉 [Receipt](<direct%20purchase.md>).
>  
> If a return is needed, initiate a **Sales Return** before creating a receipt 👉 [Sales Return](<direct%20purchase.md>).

🎉 **Congratulations!** You've successfully created a sales invoice!