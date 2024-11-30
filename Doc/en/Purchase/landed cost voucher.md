# Landed Cost Voucher

A Landed Cost Voucher (LCV) is a document used to allocate additional costs incurred on goods purchased, such as freight, customs, and insurance, to accurately reflect the total cost of goods.

## Accessing Landed Cost Voucher

>     Navigate to Purchase > Landed Cost Voucher to access the LCV dashboard.

<img src="../images/lcv dashboard.png" alt="lcv dashboard" style="border-radius: 10px; width: 70%; height: 70%; border: 0.5px solid #333;">

## Dashboard Features

<h3>Filters</h3>

You can filter Landed Cost Vouchers using the Search option.

<h3>Export to Excel</h3>

Export all vouchers (Draft, Approved, or Withdrawn) to Excel using the Export option.

## Creating a New Landed Cost Voucher

Click Create New: Use the Create New button in the top-right corner of the dashboard.

<img src="../images/create new lcv.png" alt="create new lcv" style="border-radius: 10px; width: 70%; height: 70%; border: 0.5px solid #333;">

### Document Number Series

Configure the series through Document Series Settings. [Set Document Series](<../Purchase/direct_purchase.md>)

### Date

Select the voucher date.

### Receipt Type

Choose the receipt type

<div style="text-align:left;">
    <ul>
        <li><strong>Type:</strong> Need to select its GRN or Direct Purchase</li>
        <li><strong>Record No</strong> Select a Record No. from previously approved GRNs.</li>
        <li>Upon selection, fields like Supplier, Grand Total, Book Date, and Action will auto-populate.</li>
        <li>Use the Delete button in the Action column to remove any unwanted GRNs.</li>
        <li>Add multiple GRNs using the Add button in the Action column.</li>
    </ul>
</div>

<img src="../images/grn selection in lcv.png" alt="grn selection in lcv" style="border-radius: 10px; width: 70%; height: 70%; border: 0.5px solid #333;">

### Item List

Click Get Item to populate the Item List section with data from the selected GRN(s), including:

<div style="text-align:left;">
    <ul>
        <li>Catalog No.</li>
        <li>Item Name</li>
        <li>Price</li>
        <li>Quantity</li>
    </ul>
</div>

<img src="../images/item in lcv.png" alt="item in lcv" style="border-radius: 10px; width: 70%; height: 70%; border: 0.5px solid #333;">

### Add Additional Charges

Enter additional expenses incurred, such as shipping or handling charges:

<div style="text-align:left;">
    <ul>
        <li><strong>Expense Account:</strong> Select the account to allocate charges.</li>
        <li><strong>Amount:</strong> Enter the cost.</li>
        <li><strong>Description:</strong> Provide details for the expense.</li>
        <li>Use the Action button to delete or modify charges.</li>
    </ul>
</div>

The Cost Factor will be calculated based on Distribute Charges. That will be based on amount or quanitiy it will vary.

<img src="../images/aditional charges adding in lcv.png" alt="aditional charges adding in lcv" style="border-radius: 10px; width: 70%; height: 70%; border: 0.5px solid #333;">

### Addiotional Data

<div style="text-align:left;">
    <ul>
        <li>Reference Number</li>
        <li>Statement Reference</li>
    </ul>
</div>

### Save and Generate PDF

<img src="../images/print of lcv.png" alt="print of lcv" style="border-radius: 10px; width: 70%; height: 70%; border: 0.5px solid #333;">

Save the voucher to generate its PDF.

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
    </ul>
</div>

### Approval Workflow

Use the Action Button to Approve the Landed Cost Voucher. Once approved:

<div style="text-align:left;">
    <ul>
        <li>The status changes from Draft to Approved.</li>
        <li>The Approve button changes to Withdraw.</li>
    </ul>
</div>

### Next Steps

After approving the Landed Cost Voucher, the next step is Making an Invoice against this purchase. 👉 [Learn More About Payment](<direct purchase.md>).