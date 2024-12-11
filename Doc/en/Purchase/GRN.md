# Goods Receipt Note (GRN)

A GRN is a document used to confirm the receipt of goods from a supplier. It ensures that the delivered items match the purchase order and serves as a record for inventory updates.

---

## Accessing GRN

Navigate to **Purchase > GRN** to access the **GRN Dashboard**. This dashboard displays all GRNs, categorized as **Draft**, **Approved**, or **Withdrawn**.

<img src="../images/grn dashboard.png" alt="grn dashboard" style="border-radius: 10px; width: 70%; height: 70%; border: 0.5px solid #333;">

---

## GRN Dashboard Features

### **Filters**

Use the following filters to search for specific GRNs:

- **Search**: Search for specific documents.
- **Document Number**: Filter by document number.
- **Document Status**: Filter by Draft, Approved, or Withdrawn status.
- **Min-Max Book Date**: Set a date range.
- **Reference Number**: Search by reference number.
- **Supplier Name**: Filter by supplier.
- **Show Withdrawn Entry**: Toggle the checkbox to include withdrawn entries.

<img src="../images/filtering option in grn.png" alt="filtering option in grn" style="border-radius: 10px; width: 70%; height: 70%; border: 0.5px solid #333;">

---

### **Export to Excel**

Easily export GRN data (Draft, Approved, or Withdrawn) by clicking the **Export** button.

---

## Creating a New GRN

To create a new GRN, click **Create New** in the top-right corner of the dashboard.

<img src="../images/create new option in grn.png" alt="create new option in grn" style="border-radius: 10px; width: 70%; height: 70%; border: 0.5px solid #333;">

---

## Fill the GRN Form

### **1. Document Information**

| Field                   | Description                                                                 |
|-------------------------|-----------------------------------------------------------------------------|
| **Document Number Series** | Configure via [Document Series Settings](<../Purchase/direct_purchase.md>). |
| **Date**                | Specify the date of receipt.                                                |

### **2. Store Information**

| Field                   | Description                                                                 |
|-------------------------|-----------------------------------------------------------------------------|
| **Accepted Store**      | Select the store where accepted items will be moved. Configure via [Set Store](<direct%20purchase.md>). |
| **Rejected Store**      | Select the store for rejected or damaged items. Configure via [Set Store](<direct%20purchase.md>). |

### **3. Supplier Selection**

| Field                   | Description                                                                 |
|-------------------------|-----------------------------------------------------------------------------|
| **Supplier**            | Select from the dropdown. Add new suppliers via [Supplier Menu](<direct%20purchase.md>). |
| **Order Button**        | If linked to a Purchase Order, this button will auto-populate item details. |

<div style="display: flex; gap: 10px;">
  <img src="../images/field in grn.png" style="width: 100%; border-radius: 10px; border: 0.5px solid #333;">
  <img src="../images/get order in grn.png" style="width: 100%; border-radius: 10px; border: 0.5px solid #333;">
  <img src="../images/item in grn.png" style="width: 100%; border-radius: 10px; border: 0.5px solid #333;">
</div>

### **4. Supplier Tax Settings**

If the supplier is tax-registered, a **Tax** column will appear in the item table. Choose the appropriate tax type (e.g., UAE VAT or India GST). The **Total Amount** will adjust automatically based on the **Subtotal**.

### **5. Bill of Lading/Airway Billing**

Enter the relevant details in this section.

### **6. Additional Charges**

Specify any additional costs by entering amounts and descriptions. These can include charges for shipping, handling, etc. You can configure accounts for these charges via [Configure Accounts](<direct%20purchase.md>).

- **Distribution Based On**: Select either **Amount** or **Quantity**.
- **Reference Number**: Enter a unique reference for the GRN.
- **Container Number & Notes**: Optional fields for adding more details.

<img src="../images/additional charges in grn.png" alt="additional charges in grn" style="border-radius: 10px; width: 70%; height: 70%; border: 0.5px solid #333;">

---

### **Preview Changes with Additional Charges**

If additional charges are added, the **Total Price of Stock** will reflect these changes. The preview will also show how the additional charge is applied to each unit/quantity of the stock.

---

### **Save and Generate PDF**

Once all details are filled in, click **Save** to create the GRN. You can also generate a PDF of the GRN.

<img src="../images/print in grn.png" alt="print in grn" style="border-radius: 10px; width: 70%; height: 70%; border: 0.5px solid #333;">

---

## Post-Save Options

After saving, the following actions are available:

- **Back**: Return to the GRN Dashboard.
- **Preview Settings**: Customize the document preview.
- **New Create**: Start a new direct purchase.
- **Edit**: Modify the document (only available before approval).
- **Delete**: Remove the document.
- **Print**: Print the GRN.
- **Download**: Export the document.
- **Download Without Header and Footer**: Export a clean version of the GRN.

Additionally, you can go to:

- **Provisional Account Ledger**: View account details related to this GRN.

---

## Approval Process

To approve the GRN, click the **Approve** button. Once approved, the GRN cannot be edited, and its status updates to **Approved**. After approval, the button will change to **Withdraw**.

---

## Next Steps

After completing the GRN, proceed to:

- **Landed Cost Voucher**
- **Purchase Invoice**

🎉 **Congratulations!** You've successfully created and processed a Goods Receipt Note (GRN)!