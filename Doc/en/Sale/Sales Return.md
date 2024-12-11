# Sales Return

The Sales Return module allows you to handle returned items, adjust stock, and manage refunds or credits efficiently.

---

## Accessing Sales Return Dashboard

### Step 1: Navigate to **Sale > Sales Return**

> This will take you to the **Sales Return Dashboard**, displaying:
> - All sales returns categorized as Draft or Approved.
> - Options to Search or use Advanced Filters for refined results.

<img src="../images/sales return dashboard.png" alt="sales return dashboard" style="border-radius: 10px; width: 70%; height: 70%; border: 0.5px solid #333;">

---

## Export to Excel

Export all sales returns by clicking the **Export to Excel** button.

---

## Creating a New Sales Return

Quickly create a new sales return by following these steps.

### Step 1: Click **Create New**

> This opens the Sales Return form where you can enter details like customer selection, item return details, and payment information.

---

### **1. Document Information**

- **Document Number Series**: Automatically generated. Configure via 👉 [Document Series Settings](<direct_purchase.md>).  
- **Date**: Specify the return date.

---

### **2. Customer Selection**

- **Customer**: Choose the customer from the dropdown. Add new customers via 👉 [Customer Menu](<direct_purchase.md>).  
- Displays the **Due Amount** for the selected customer.  
- **Get Button**: Click **Get** to choose between Direct Sale or Sales Invoice.
  - If you select **Invoice**, all invoices associated with the customer will be listed.
  - Select the relevant invoice and choose the item(s) to return.
  - Click **Get** to automatically populate details like item, price, and total.

<div style="display: flex; gap: 10px;">
  <img src="../images/choose direct or invoice that need SR.png" style="width: 100%; border-radius: 10px; border: 0.5px solid #333;">
  <img src="../images/select invoice for SR.png" style="width: 100%; border-radius: 10px; border: 0.5px solid #333;">
  <img src="../images/select item that need to returned.png" style="width: 100%; border-radius: 10px; border: 0.5px solid #333;">
</div>

---

### **3. Item and Pricing Details**

- **Price Type**: Automatically fetched from the associated invoice.  
- **Store**: Automatically fetched from the associated invoice.

#### Item Return Details:

- Automatically fetched from the invoice or direct sale.  
- Specify the **Return Store** where the item will be returned.  
- Enter the **Quantity** for return. Fields such as Unit, Price, and Total will be fetched automatically.

<img src="../images/enter qty that need to be returned.png" alt="enter qty that need to be returned" style="border-radius: 10px; width: 70%; height: 70%; border: 0.5px solid #333;">

---

### **4. Salesperson and Project Information**

- **Salesperson**: Assign a salesperson. Create new salespersons via 👉 [Salesperson Settings](<direct_purchase.md>).  
- **Project**: Link the return to a specific project. Configure via 👉 [Project Settings](<direct_purchase.md>).

---

### **5. Additional Details**

- **Reference Number**: Add any relevant reference number.  
- **Statement Reference**: Provide additional reference details.

---

### **6. Payment Section**

Select the required payment type.

<img src="../images/select payment type for SR.png" alt="select payment type for SR" style="border-radius: 10px; width: 70%; height: 70%; border: 0.5px solid #333;">

---

### Saving and Approving Sales Return

- **Save**: After entering all details, click **Save** to create the sales return.  
- **Approve**: Click **Approve** to finalize the sales return.

<img src="../images/approved SR.png" alt="approved SR" style="border-radius: 10px; width: 70%; height: 70%; border: 0.5px solid #333;">

---

## Next Steps

After approving the sales return:  
Proceed to the **Receipt Module** for payment adjustments or refunds. Learn more about 👉 [Receipt](<direct_purchase.md>).