# Goods Receipt Note (GRN)

A GRN is a document used to confirm the receipt of goods from a supplier. It ensures that the delivered items match the purchase order and serves as a record for inventory updates.

## Accessing GRN

>     Navigate to Purchase > GRN to access the GRN dashboard. The dashboard displays all GRNs, categorized as Draft, Approved, or Withdrawn.

<img src="../images/grn dashboard.png" alt="grn dashboard" style="border-radius: 10px; width: 70%; height: 70%; border: 0.5px solid #333;">

## Dashboard Features

<h3>Filters</h3>

<div style="text-align:left;">
    <ul>
        <li>Search</li>
        <li>Document Number</li>
        <li>Document Status</li>
        <li>Min-Max Book Date</li>
        <li>Reference Number</li>
        <li>Supplier Name</li>
        <li>Show Withdrawn Entry (checkbox)</li>
    </ul>
</div>

<img src="../images/filtering option in grn.png" alt="filtering option in grn" style="border-radius: 10px; width: 70%; height: 70%; border: 0.5px solid #333;">

<h3>Export to Excel</h3>

Export GRNs (Draft, Approved, or Withdrawn) to Excel by clicking the Export button.

## Creating a New GRN

Click Create New: Use the Create New button in the top-right corner of the dashboard.

<img src="../images/create new option in grn.png" alt="create new option in grn" style="border-radius: 10px; width: 70%; height: 70%; border: 0.5px solid #333;">

## Fill the GRN Form:

### Document Number Series

Configure the series through Document Series Settings. [Set Document Series](<../Purchase/direct_purchase.md>)

### Date

Select the date of the GRN.

### Accepted Store

This is the store where items of proper quality will be moved. Store can be configured here: [Set store](<direct purchase.md>)

### Rejected Store

Damaged or defective items will be moved to this store for further adjustment. Store can be configured here: [Set store](<direct purchase.md>)

### Supplier

Choose the supplier from the dropdown. If linked to a Purchase Order, the Order button will appear. Selecting the order auto-populates item details. Add suppliers through the Supplier Menu: [Add Suppliers](<direct purchase.md>)

<div style="display: flex; gap: 10px;">
  <img src="../images/field in grn.png" style="width: 100%; border-radius: 10px; border: 0.5px solid #333;">
  <img src="../images/get order in grn.png" style="width: 100%; border-radius: 10px; border: 0.5px solid #333;">
  <img src="../images/item in grn.png" style="width: 100%; border-radius: 10px; border: 0.5px solid #333;">
</div>

#### Supplier Tax Settings

If the supplier is tax-registered, a Tax column will appear in the item table. Choose the appropriate tax type (e.g., UAE VAT or India GST). The Total Amount adjusts automatically based on the Subtotal.

### Bill of Lading/Airway Billing

Enter the relevant details.

### Additional Charges

Specify accounts for additional costs [Configure Accounts](<direct purchase.md>).<br>
Enter amounts and descriptions. Add multiple charges, which update the Total Additional Charges.

<img src="../images/additional charges in grn.png" alt="additional charges in grn" style="border-radius: 10px; width: 70%; height: 70%; border: 0.5px solid #333;">

<div style="text-align:left;">
    <ul>
        <li>Distribution Based On: Select either Amount or Quantity.</li>
        <li>Reference Number: Enter a unique reference for the GRN.</li>
        <li>Container Number & Notes: Add optional details.</li>
    </ul>
</div>

### Preview Changes with Additional Charges

<div style="text-align:left;">
    <ul>
        <li>If additional charges are added, the Total Price of Stock will reflect these changes.</li>
        <li>The preview also displays how much additional charge is applied to each unit/quantity of the stock.</li>
    </ul>
</div>

### Save and Generate PDF

Save the GRN to generate its PDF.

<img src="../images/print in grn.png" alt="print in grn" style="border-radius: 10px; width: 70%; height: 70%; border: 0.5px solid #333;">

### Post-Save Options

Once saved, the GRN form provides the following actions:

<div style="text-align:left;">
    <ul>
        <li><strong>Back:</strong> Return to the dashboard.</li>
        <li><strong>Preview Settings:</strong> Customize the document preview.</li>
        <li><strong>New Create:</strong> Start a new direct purchase.</li>
        <li><strong>Edit:</strong> Modify the document (before approval only).</li>
        <li><strong>Delete:</strong> Remove the document.</li>
        <li><strong>Print:</strong> Print the purchase record.</li>
        <li><strong>Download:</strong> Export the document.</li>
        <li><strong>Download Without Header and Footer:</strong> Export a clean version.</li>
    </ul>
</div>

<div style="text-align:left;">
    <ul>
        <li><strong>Go To > Provisional Account Ledger:</strong> View account details.</li>
    </ul>
</div>

### Approval Process

Use the Action Button to Approve the GRN. Once approved, the GRN cannot be edited, and its status updates to Approved. The Approve button changes to Withdraw after approval.

### Next Steps

After completing the GRN, proceed to:

<div style="text-align:left;">
    <ul>
        <li><strong>Landed Cost Voucher</strong></li>
        <li><strong>Purchase Invoice</strong></li>
    </ul>
</div>