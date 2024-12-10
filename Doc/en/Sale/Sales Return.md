# Sales Return

The Sales Return module allows you to handle returned items, adjust stock, and manage refunds or credits efficiently.

## Accessing Sales Return Dashboard

>     Navigate to Sale > Sales Return.

<img src="../images/sales return dashboard.png" alt="sales return dashboard" style="border-radius: 10px; width: 70%; height: 70%; border: 0.5px solid #333;">

The Sales Return Dashboard will appear, displaying: All sales returns categorized as Draft or Approved. There will be options to Search or use Advanced Filters for refined results.

## Export to Excel

Export all sales returns by clicking the Export to Excel button.

## Creating a New Sales Return

Click Create New in the top-right bar to open the Sales Return form. Follow these steps:

### Document Information

Document Number Series: Automatically generated. Configure via the 👉 [Document Series Settings](<direct purchase.md>).<br>
Date: Specify the return date.

### Customer Selection

Customer: Choose the customer from the dropdown. Add new customers via 👉 [Customer Menu](<direct purchase.md>).<br>
Displays the Due Amount for the selected customer.<br>
Get Button: Click Get to choose between Direct Sale or Sales Invoice.<br>
If you select Invoice, all invoices associated with the customer will be listed.<br>
Select the relevant invoice and choose the item(s) to return.<br>
Click Get to automatically populate details like item, price, and total.

<div style="display: flex; gap: 10px;">
  <img src="../images/choose direct or invoice that need SR.png" style="width: 100%; border-radius: 10px; border: 0.5px solid #333;">
  <img src="../images/select invoice for SR.png" style="width: 100%; border-radius: 10px; border: 0.5px solid #333;">
  <img src="../images/select item that need to returned.png" style="width: 100%; border-radius: 10px; border: 0.5px solid #333;">
</div>

### Item and Pricing Details

Price Type: Automatically fetched from the associated invoice.<br>
Store: Automatically fetched from the associated invoice.<br>

#### Item Return Details:

Automatically item(s) will be fetched from the invoice or direct sale.<br>
Specify the Return Store where the item will be returned.<br>
Enter the Quantity for return. Fields such as Unit, Price, and Total will be fetched automatically.

<img src="../images/enter qty that need to be returned.png" alt="enter qty that need to be returned" style="border-radius: 10px; width: 70%; height: 70%; border: 0.5px solid #333;">

### Salesperson and Project Information

Salesperson: Assign a salesperson. Create new salespersons via 👉 [Salesperson Settings](<direct purchase.md>).<br>
Project: Link the return to a specific project. Configure via 👉 [Project Settings](<direct purchase.md>).<br>

### Additional Details

Reference Number: Add any relevant reference number.<br>
Statement Reference: Provide additional reference details.<br>

### Payment Section

Select which payment you needed

<img src="../images/select payment type for SR.png" alt="select payment type for SR" style="border-radius: 10px; width: 70%; height: 70%; border: 0.5px solid #333;">

### Saving and Approving Sales Return

Save: After entering all details, click Save to create the sales return.<br>
Approve: Click Approve to finalize the sales return.<br>

<img src="../images/approved SR.png" alt="approved SR" style="border-radius: 10px; width: 70%; height: 70%; border: 0.5px solid #333;">

## Next Steps

After approving the sales return: Proceed to the Receipt module for payment adjustments or refunds. Learn more about 👉 [Receipt](<direct purchase.md>).<br>