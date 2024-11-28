# Purchase Order

The Purchase Order feature enables users to manage purchase requests systematically by specifying required items, delivery dates, and supplier details. Here's an overview of the module:

## Accessing Purchase Order

>     To access Purchase Order, Navigate to: Purchase > Purchase Order.

<div style="text-align:left;">
    <ul>
        <li><strong>Purchase Order Dashboard:</strong> This dashboard displays all purchases Order categorized as Draft, Approved and if checkbox enabled Include WithDraw Data.</li>
    </ul>
</div>

<img src="../images/purchase order dashboard.png" alt="purchase order dashboard" style="border-radius: 10px; width: 70%; height: 70%; border: 0.5px solid #333;">

## Export to Excel

You can export Purchase Orders from the dashboard into an Excel file for easy tracking and reporting.

## Filtering Options

The dashboard provides filtering options for managing and locating purchase orders:

<div style="text-align:left;">
    <ul>
        <li><strong>Search:</strong> Locate orders using keywords.</li>
        <li><strong>Document Number:</strong> Filter by document number.</li>
        <li><strong>Min-Max Book Date:</strong> Filter purchases based on the booking date range.</li>
        <li><strong>Reference Number:</strong> Search for purchases using their reference numbers.</li>
        <li><strong>Supplier Name:</strong> Locate purchases by the supplier's name.</li>
        <li><strong>Verification Status:</strong> Filter records by their status (e.g., Draft, Approved, All).</li>
        <li><strong>Tax:</strong> Filter purchases that involve specific tax types.</li>
        <li><strong>Show Withdrawn Entry:</strong> Check this box to include withdrawn purchases in the results.</li>
    </ul>
</div>

<img src="../images/filtering in purchase order dashboard.png" alt="filtering in purchase order dashboard" style="border-radius: 10px; width: 70%; height: 70%; border: 0.5px solid #333;">

## Creating a New Purchase Order

To create a new purchase order, click the Create New button on the top-right bar. A new form will open, requiring the following details:

<img src="../images/create new purchase order.png" alt="create new purchase order" style="border-radius: 10px; width: 70%; height: 70%; border: 0.5px solid #333;">


### Document Number Series

Configure the series through Document Series Settings. [Set Document Series](<../Purchase/direct_purchase.md>)

### Date

Select the date of the purchase.

### Supplier

Select the supplier from the dropdown list. if you already create a quotation against that supplier the quotation will show there. Add suppliers via the Supplier Menu. [Add Suppliers](<direct purchase.md>) 

#### Supplier Tax Settings

If the supplier has tax settings (e.g., UAE VAT, India GST), a Tax Column will appear on the item side. Select the tax type from the dropdown.The total amount will adjust based on the subtotal and tax automatically.

### Expected Delivery Date

Specify the delivery date for the items.

### Project

Link the purchase to a project. Configure projects here: [Set Projects](<direct purchase.md>)

<img src="../images/field in purchase order.png" alt="field in purchase order" style="border-radius: 10px; width: 70%; height: 70%; border: 0.5px solid #333;">

### Item Selection

Choose the item from the dropdown. Items display current stock, reorder quantity, and average rate. Add or edit items here: [Add Items](<direct purchase.md>). After selecting an item:

<img src="../images/item dropdown in purchase order.png" alt="item dropdown in purchase order" style="border-radius: 10px; width: 70%; height: 70%; border: 0.5px solid #333;">

<div style="text-align:left;">
    <ul>
        <li>Enter the quantity. The unit is pre-configured when the item is created.</li>
        <li>The rate is auto-filled based on configurations but can be edited.</li>
        <li>The total price is calculated automatically.</li>
        <li>Add multiple products by clicking Add.</li>
    </ul>
</div>

<img src="../images/auto calculation in purchase order.png" alt="auto calculation in purchase order" style="border-radius: 10px; width: 70%; height: 70%; border: 0.5px solid #333;">

### Additional Fields for Reference

<img src="../images/reference in purchase order.png" alt="reference in purchase order" style="border-radius: 10px; width: 70%; height: 70%; border: 0.5px solid #333;">

<div style="text-align:left;">
    <ul>
        <li>Statement Reference: Add relevant notes or statements.</li>
        <li>LPO No. and LPO Date: Enter the Local Purchase Order number and date.</li>
        <li>Container No.: Add a container number if needed.</li>
        <li>Message: Include any additional messages.</li>
    </ul>
</div>

Billing Address: Choose a billing address. 👉 [Set Billing Address](<direct purchase.md>)<br>
Shipping Address: Specify the shipping address. 👉 [Set Shipping Address](<direct purchase.md>)<br>
Terms and Conditions: Select pre-configured terms from the dropdown. 👉 [Set Terms and Conditions](<direct purchase.md>). Also enter custom terms if necessary.

<img src="../images/Terms and Conditions in purchase order.png" alt="Terms and Conditions in purchase order" style="border-radius: 10px; width: 70%; height: 70%; border: 0.5px solid #333;">

### Saving and Exporting

After filling out the details: Click Save to generate the purchase order. A PDF of the purchase order will be available for download or print.

### Actions on a Saved Purchase Order

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

<img src="../images/top bar in purchase order.png" alt="top bar in purchase order" style="border-radius: 10px; width: 70%; height: 70%; border: 0.5px solid #333;">

### Approval Workflow

Action Button: Use the Approve option to finalize the purchase order. Once approved:

<div style="text-align:left;">
    <ul>
        <li>The status changes from Draft to Approved.</li>
        <li>The Approve button changes to Withdraw.</li>
    </ul>
</div>

<div style="display: flex; gap: 10px;">
  <img src="../images/draft and approve in purchase order.png" style="width: 100%; border-radius: 10px; border: 0.5px solid #333;">
  <img src="../images/approved and withdraw in purchase order.png" style="width: 100%; border-radius: 10px; border: 0.5px solid #333;">
</div>

Editing Restrictions: Approved purchases cannot be edited.

Next Step: Once the purchase order is approved, proceed to GRN (Goods Received Note). 👉 [Learn More About GRN](<direct purchase.md>).