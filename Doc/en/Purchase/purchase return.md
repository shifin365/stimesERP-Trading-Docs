# Purchase Return

A Purchase Return is a process where goods purchased from a supplier are returned due to reasons like defects, incorrect items, or excess quantity.

## Accessing Purchase Return

>     Navigate to Purchase > Purchase Return to access the Purchase Return dashboard.

<div style="text-align:left;">
    <ul>
        <li><strong>Purchase Return Dashboard:</strong> The dashboard displays all purchase return records, categorized as Draft, Approved and if checkbox enabled Include WithDraw Data.</li>
    </ul>
</div>

<img src="../images/PR DASHBOARD.png" alt="PR DASHBOARD" style="border-radius: 10px; width: 70%; height: 70%; border: 0.5px solid #333;">

## Dashboard Features

<h3>Filters</h3>

Filter purchase return records using the Search option.

<h3>Export to Excel</h3>

Export all records (Draft, Approved, or Withdrawn) to Excel using the Export option.

## Creating a New Purchase Return

Click Create New: Use the Create New button in the top-right corner of the dashboard.

<img src="../images/PR CREATE NEW.png" alt="cPR CREATE NEW" style="border-radius: 10px; width: 70%; height: 70%; border: 0.5px solid #333;">

When you click Create New, a form opens for entering purchase details. Below are the required fields and their configurations:

### Document Number Series

Configure the series through Document Series Settings. [Set Document Series](<../Purchase/direct_purchase.md>)

### Date

Select the date of the return.

<img src="../images/PR FIELDS.png" alt="PR FIELDS" style="border-radius: 10px; width: 70%; height: 70%; border: 0.5px solid #333;">

### Supplier

Choose the supplier from whom the goods were purchased. Add suppliers through the Supplier Menu: [Add Suppliers](<direct purchase.md>)

<div style="text-align:left;">
    <ul>
        <li>Click the Get button to retrieve purchase data.</li>
        <li>Choose either Direct Purchase or GRN (Goods Receipt Note)</li>
        <li><strong>GRN: </strong>Select the Record No. from the GRN. This will populate the details of the goods purchased against the supplier.</li>
        <li><strong>Direct Purchase: </strong>Manually select and add items for return.</li>
    </ul>
</div>

<div style="display: flex; gap: 10px;">
  <img src="../images/PR DATA TAKING BASED ON DP OR GRN.png" style="width: 100%; border-radius: 10px; border: 0.5px solid #333;">
  <img src="../images/PR RECORD SELECTION USING GRN.png" style="width: 100%; border-radius: 10px; border: 0.5px solid #333;">
  <img src="../images/PR BASED ON ITEM UNDER RECORD NO.png" style="width: 100%; border-radius: 10px; border: 0.5px solid #333;">
</div>

### Items Section

Select the items to return by choosing them from the Record No. data. Enter the Quantity to return for each item. Specify the Store from which the stock is being returned.

<img src="../images/PR ITEM SECTION.png" alt="PR ITEM SECTION" style="border-radius: 10px; width: 70%; height: 70%; border: 0.5px solid #333;">

### Additional Fields for Reference

<div style="text-align:left;">
    <ul>
        <li>Add a Reference Number</li>
        <li>Provide a Statement Reference if applicable</li>
    </ul>
</div>

### Price Type

Choose a price type, such as Wholesale, Retail, or Regular. Price types can be configured here: [Set Price Types](<direct purchase.md>)

### Payment Details

Select the Payment Type. Available modes include: Cash, Bank, Cheque, Credit. Configure payment types here: [Set Payment Types](<direct purchase.md>).

<img src="../images/PR PAYMENT TYPE.png" alt="PR PAYMENT TYPE" style="border-radius: 10px; width: 70%; height: 70%; border: 0.5px solid #333;">

<h3>Credit</h3>

Select Payment Term & Due Date options:

<div style="text-align:left;">
    <ul>
        <li>Due at the end of the next month</li>
        <li>Due at the end of the month</li>
        <li>Due on receipt</li>
        <li>Custom dates</li>
    </ul>
</div>

<h3>Cash</h3>

Configure:

Cost Center: 👉 [Set Cost Centers](<direct purchase.md>).
Cash Account: 👉 [Set Cash Accounts](<direct purchase.md>).
Cash Repository: 👉 [Set Cash Repository](<direct purchase.md>).

<h3>Cheque</h3>

Configure:

Cost Center: 👉 [Set Cost Centers](<direct purchase.md>).
Bank: 👉 [Set Banks](<direct purchase.md>).

Enter:

<div style="text-align:left;">
    <ul>
        <li>Cheque Number</li>
        <li>Cheque Date</li>
    </ul>
</div>

<h3>Bank</h3>

Configure:

Cost Center: 👉 [Set Cost Centers](<direct purchase.md>).
Bank: 👉 [Set Banks](<direct purchase.md>).

Enter:

<div style="text-align:left;">
    <ul>
        <li>Bank Posted Date</li>
        <li>Instrument Code</li>
        <li>Bank Transaction Code</li>
    </ul>
</div>

### Saving and Exporting

Save the purchase return to generate its PDF. Available options in the Top Right Bar:

<div style="text-align:left;">
    <ul>
        <li><strong>Back:</strong> Return to the dashboard.</li>
        <li><strong>Preview Settings:</strong> Customize the document preview.</li>
        <li><strong>Previous Preview:</strong> View previous document versions.</li>
        <li><strong>New Create:</strong> Start a new purchase return.</li>
        <li><strong>Edit:</strong> Modify the document (before approval only).</li>
        <li><strong>Delete:</strong> Remove the document.</li>
        <li><strong>Print:</strong> Print the purchase record.</li>
        <li><strong>Download:</strong> Export the document.</li>
        <li><strong>Download Without Header and Footer:</strong> Export a clean version.</li>
    </ul>
</div>

<div style="text-align:left;">
    <ul>
        <li><strong>Go To > Stock Ledger:</strong> View the stock movement ledger.</li>
    </ul>
</div>

<div style="text-align:left;">
    <ul>
        <li><strong>Go To > Provisional Account Ledger:</strong> View account details.</li>
    </ul>
</div>

<div style="display: flex; gap: 10px;">
  <img src="../images/PR STOCK LEDGER.png" style="width: 100%; border-radius: 10px; border: 0.5px solid #333;">
  <img src="../images/PR PROVISIONAL.png" style="width: 100%; border-radius: 10px; border: 0.5px solid #333;">
</div>

### Approval Workflow

Use the Action Button to Approve the Purchase Return. Once approved:

<div style="text-align:left;">
    <ul>
        <li>The status changes from Draft to Approved.</li>
        <li>The Approve button changes to Withdraw.</li>
    </ul>
</div>

<img src="../images/PR PRINT.png" alt="PR PRINT" style="border-radius: 10px; width: 70%; height: 70%; border: 0.5px solid #333;">

### Next Step

After the Purchase Return is approved, proceed to update the stock or financial records accordingly.