# Purchase Invoice

A Purchase Invoice is a document that records the supplier's bill for goods or services purchased. It serves as the basis for payment processing and is critical for accounting and inventory management.

## Accessing Purchase Invoice

>     Navigate to Purchase > Purchase Invoice to access the Purchase Invoice dashboard.

<img src="../images/purchase invoice dashboard.png" alt="purchase invoice dashboard" style="border-radius: 10px; width: 70%; height: 70%; border: 0.5px solid #333;">

## Dashboard Features

<h3>Filters</h3>

You can filter Purchase Invoices using

<div style="text-align:left;">
    <ul>
        <li><strong>Search</strong></li>
        <li><strong>Document Number</strong></li>
        <li><strong>Min-Max Book Date</strong></li>
        <li><strong>Min-Max Due Date</strong></li>
        <li><strong>Reference Number</strong></li>
        <li><strong>Document Status</strong></li>
        <li><strong>Show Withdrawn Entry</strong></li>
    </ul>
</div>

<img src="../images/purchase invoice filter.png" alt="purchase invoice filter" style="border-radius: 10px; width: 70%; height: 70%; border: 0.5px solid #333;">

<h3>Export to Excel</h3>

Export all invoices (Draft, Approved, or Withdrawn) to Excel using the Export option.

## Creating a New Purchase Invoice

Click Create New: Use the Create New button in the top-right corner of the dashboard.

<img src="../images/create new purchase invoice.png" alt="create new purchase invoice" style="border-radius: 10px; width: 70%; height: 70%; border: 0.5px solid #333;">

### Document Number Series

Configure the series through Document Series Settings. [Set Document Series](<../Purchase/direct_purchase.md>)

### Date

Select the date of the purchase.

### Payment Term & Due Date

Set the payment term and select the due date.

### Price Type

Choose the pricing type (e.g., Wholesale, Retail).

<img src="../images/purchase invoice fields.png" alt="purchase invoice fields" style="border-radius: 10px; width: 70%; height: 70%; border: 0.5px solid #333;">

### Supplier

Choose the supplier from the dropdown. If the supplier has associated Purchase Orders, an Order button will appear. Clicking the button will display all orders linked to the supplier. Selecting an order auto-populates its items and details into the invoice. Add suppliers via the Supplier Menu. [Add Suppliers](<direct purchase.md>) 

#### Invoice Based on Previous Documents

You can create a Purchase Invoice based on:

<div style="text-align:left;">
    <ul>
        <li>Purchase Order</li>
        <li>Goods Receipt Note (GRN)</li>
        <li>Landed Cost Voucher</li>
    </ul>
</div>

<div style="display: flex; gap: 10px;">
  <img src="../images/purchase invoice based on order,grn,lcv.png" style="width: 100%; border-radius: 10px; border: 0.5px solid #333;">
  <img src="../images/purchase invoice based on grn.png" style="width: 100%; border-radius: 10px; border: 0.5px solid #333;">
  <img src="../images/purchase invoice based on grn items.png" style="width: 100%; border-radius: 10px; border: 0.5px solid #333;">
</div>

Selecting one of these will load all relevant data for that supplier.

#### Supplier Tax Settings

If the supplier has tax settings (e.g., UAE VAT, India GST), a Tax Column will appear on the item side. Select the tax type from the dropdown.The total amount will adjust based on the subtotal and tax automatically.

### Project

Link the purchase to a project. Configure projects here: [Set Projects](<direct purchase.md>)

### Additional Fields:

Reference Number: Add a unique identifier for the invoice.
Statement Reference: Add any relevant remarks or notes.

### Save and Generate PDF

<img src="../images/purchase invoice print.png" alt="purchase invoice print" style="border-radius: 10px; width: 70%; height: 70%; border: 0.5px solid #333;">

Save the invoice to generate its PDF.

### Post-Save Options

Once the Purchase Invoice is saved, you have the following options:

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
        <li><strong>Provisional Account Ledger: </strong> Accessible via the Go To button.</li>
    </ul>
</div>

### Approval Workflow

Action Button: Use the Approve option to finalize the purchase invoice. Once approved:

<div style="text-align:left;">
    <ul>
        <li>The status changes from Draft to Approved.</li>
        <li>The Approve button changes to Withdraw.</li>
    </ul>
</div>

### Next Steps

After approving the Purchase Invoice, the next step is Making Payment.. 👉 [Learn More About Payment](<direct purchase.md>).