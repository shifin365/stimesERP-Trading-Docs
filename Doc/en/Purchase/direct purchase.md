# Direct Purchase

The Direct Purchase feature allows businesses to directly record procurement transactions without creating a purchase order. Here's a detailed guide to using the Direct Purchase module.

## Accessing Direct Purchase

>     To access Direct Purchase, click: Purchase > Direct Purchase.

<div style="text-align:left;">
    <ul>
        <li><strong>Direct Purchase Dashboard:</strong> This dashboard displays all direct purchases categorized as Draft, Approved and if checkbox enabled Include WithDraw Data.</li>
    </ul>
</div>

<img src="../images/direct purchase.png" alt="direct purchase" style="border-radius: 10px; width: 70%; height: 70%; border: 0.5px solid #333;">

## Filtering Direct Purchases

The Direct Purchase Dashboard includes advanced filtering options for easier management of records. These filters are:

<div style="text-align:left;">
    <ul>
        <li><strong>Search:</strong> Enter keywords to locate specific purchases quickly.</li>
        <li><strong>Document Number:</strong> Search for a purchase by its document number.</li>
        <li><strong>Min-Max Book Date:</strong> Filter purchases based on the booking date range.</li>
        <li><strong>Min-Max Due Date:</strong> Filter purchases by their due date range.</li>
        <li><strong>Reference Number:</strong> Search for purchases using their reference numbers.</li>
        <li><strong>Supplier Name:</strong> Locate purchases by the supplier's name.</li>
        <li><strong>Document Status:</strong> Filter records by their status (e.g., Draft, Approved, All).</li>
        <li><strong>Tax:</strong> Filter purchases that involve specific tax types.</li>
        <li><strong>Show Withdrawn Entry:</strong> Check this box to include withdrawn purchases in the results.</li>
    </ul>
</div>

<img src="../images/Filtering Direct Purchases.png" alt="Filtering Direct Purchases" style="border-radius: 10px; width: 70%; height: 70%; border: 0.5px solid #333;">

## Creating a New Direct Purchase

<div style="text-align:left;">
    <ul>
        <li><strong>Create New Direct Purchase:</strong> To create a new direct purchase, click the Create New button in the top-right corner.</li>
    </ul>
</div>

<img src="../images/create new direct purchase.png" alt="create new direct purchase" style="border-radius: 10px; width: 70%; height: 70%; border: 0.5px solid #333;">

When you click Create New, a form opens for entering purchase details. Below are the required fields and their configurations:

### Document Number Series

Configure the series through Document Series Settings. [Set Document Series](direct purchase.md)

<img src="../images/document series in direct purchase.png" alt="document series in direct purchase" style="border-radius: 10px; width: 50%; height: 50%; border: 0.5px solid #333;">

### Date

Select the date of the purchase.

<img src="../images/date in direct purchase.png" alt="date in direct purchase" style="border-radius: 10px; width: 50%; height: 50%; border: 0.5px solid #333;">

### Price Type

Choose a price type, such as Wholesale, Retail, or Regular. Price types can be configured here: [Set Price Types](<direct purchase.md>)

<img src="../images/price type in direct purchase.png" alt="price type in direct purchase" style="border-radius: 10px; width: 50%; height: 50%; border: 0.5px solid #333;">

### Store

Select the store to which the product will be delivered. Configure stores here: [Set Stores](<direct purchase.md>)

<img src="../images/store in direct purchase.png" alt="store in direct purchase" style="border-radius: 10px; width: 50%; height: 50%; border: 0.5px solid #333;">

### Supplier

Select the supplier from whom you are purchasing the product. If you select the supplier you can see the due amount against that supplier. Add suppliers through the Supplier Menu: [Add Suppliers](<direct purchase.md>)

<img src="../images/supplier in direct purchase.png" alt="supplier in direct purchase" style="border-radius: 10px; width: 50%; height: 50%; border: 0.5px solid #333;">

#### Supplier Tax Settings

When selecting a supplier during Direct Purchase creation, the tax settings associated with the supplier will be applied automatically.

<div style="text-align:left;">
    <ul>
        <li>If the supplier has tax configured (e.g., UAE VAT, India GST), an additional Tax column appears on the item side.</li>
        <li>The Tax Column allows you to: Choose the applicable tax type via a dropdown menu. Options will match the supplier's region (e.g., UAE VAT or India GST).</li>
    </ul>
</div>

### Project

Link the purchase to a project. Configure projects here: [Set Projects](<direct purchase.md>)

<img src="../images/project in direct purchase.png" alt="project in direct purchase" style="border-radius: 10px; width: 50%; height: 50%; border: 0.5px solid #333;">

### Item Selection

Choose the item from the dropdown. Items display current stock, reorder quantity, and average rate. Add or edit items here: [Add Items](<direct purchase.md>). After selecting an item:

<img src="../images/item dropdown in direct purchase.png" alt="item dropdown in direct purchase" style="border-radius: 10px; width: 70%; height: 70%; border: 0.5px solid #333;">

<div style="text-align:left;">
    <ul>
        <li>Enter the quantity. The unit is pre-configured when the item is created.</li>
        <li>The rate is auto-filled based on configurations but can be edited.</li>
        <li>The total price is calculated automatically.</li>
        <li>Add multiple products by clicking Add.</li>
    </ul>
</div>

<img src="../images/auto calculation in direct purchase.png" alt="auto calculation in direct purchase" style="border-radius: 10px; width: 70%; height: 70%; border: 0.5px solid #333;">

### Additional Fields for Reference

<img src="../images/reference in direct purchase.png" alt="reference in direct purchase" style="border-radius: 10px; width: 70%; height: 70%; border: 0.5px solid #333;">

<div style="text-align:left;">
    <ul>
        <li>Reference Number</li>
        <li>Statement Reference</li>
        <li>LPO No</li>
        <li>LPO Date</li>
    </ul>
</div>

### Payment Details

Select the Payment Type. Available modes include: Cash, Bank, Cheque, Credit. Configure payment types here: [Set Payment Types](<direct purchase.md>).

<img src="../images/payment details in direct purchase.png" alt="payment details in direct purchase" style="border-radius: 10px; width: 70%; height: 70%; border: 0.5px solid #333;">

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

<div style="display: flex; gap: 10px;">
  <img src="../images/credit payment type in direct purchase.png" style="width: 100%; border-radius: 10px; border: 0.5px solid #333;">
  <img src="../images/cash payment type in direct purchase.png" style="width: 100%; border-radius: 10px; border: 0.5px solid #333;">
</div>

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

<div style="display: flex; gap: 10px;">
  <img src="../images/cheque payment type in direct purchase.png" style="width: 100%; border-radius: 10px; border: 0.5px solid #333;">
  <img src="../images/bank payment type in direct purchase.png" style="width: 100%; border-radius: 10px; border: 0.5px solid #333;">
</div>

### Saving and Exporting

After entering all details, click Save to complete the purchase. Upon saving a PDF of the Direct Purchase is generated. Available options in the Top Right Bar:

<div style="text-align:left;">
    <ul>
        <li><strong>Back:</strong> Return to the dashboard.</li>
        <li><strong>Preview Settings:</strong> Customize the document preview.</li>
        <li><strong>Previous Preview:</strong> View previous document versions.</li>
        <li><strong>New Create:</strong> Start a new direct purchase.</li>
        <li><strong>Edit:</strong> Modify the document (before approval only).</li>
        <li><strong>Delete:</strong> Remove the document.</li>
        <li><strong>Print:</strong> Print the purchase record.</li>
        <li><strong>Download:</strong> Export the document.</li>
        <li><strong>Download Without Header and Footer:</strong> Export a clean version.</li>
    </ul>
</div>

<img src="../images/top bar in direct purchase after create.png" alt="top bar in direct purchase after create" style="border-radius: 10px; width: 70%; height: 70%; border: 0.5px solid #333;">

<div style="text-align:left;">
    <ul>
        <li><strong>Go To > Provisional Account Ledger:</strong> View account details.</li>
    </ul>
</div>

<img src="../images/Provisional Account Ledger.png" alt="Provisional Account Ledger" style="border-radius: 10px; width: 70%; height: 70%; border: 0.5px solid #333;">

### Approval Workflow

Action Button: Use the Approve option to finalize the direct purchase. Once approved:

<div style="text-align:left;">
    <ul>
        <li>The status changes from Draft to Approved.</li>
        <li>The Approve button changes to Withdraw.</li>
    </ul>
</div>

<div style="display: flex; gap: 10px;">
  <img src="../images/draft and approve in direct purchase.png" style="width: 100%; border-radius: 10px; border: 0.5px solid #333;">
  <img src="../images/approved and withdraw in direct purchase.png" style="width: 100%; border-radius: 10px; border: 0.5px solid #333;">
</div>

Editing Restrictions: Approved purchases cannot be edited.

Next Step: Proceed to Payments and confirm the payment. 👉 [Learn More About Payments](<direct purchase.md>).