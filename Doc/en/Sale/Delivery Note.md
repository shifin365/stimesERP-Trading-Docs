# Delivery Note

The Delivery Note module facilitates the process of tracking and managing the delivery of goods to customers. It integrates seamlessly with sales orders and invoicing workflows for smooth operations.

## Accessing Delivery Note Dashboard

>     Navigate to Sale > Delivery Note.

<img src="../images/delivery note dashboard.png" alt="delivery note dashboard" style="border-radius: 10px; width: 70%; height: 70%; border: 0.5px solid #333;">

The Delivery Note Dashboard will appear, displaying: All delivery notes categorized as Draft or Approved. There will be options to Search or use Advanced Filters for refined results.

## Export to Excel

You can export all delivery notes by clicking the Export to Excel button.

## Creating a New Delivery Note

Click Create New in the top-right bar to open the Delivery Note form. Follow these steps:

<img src="../images/create new delivery note.png" alt="create new delivery note" style="border-radius: 10px; width: 70%; height: 70%; border: 0.5px solid #333;">

### Document Information

Document Number Series: Auto-generated by the system. Configure via the 👉 [Document Series Settings](<direct purchase.md>).<br>
Date: Specify the delivery date.

### Customer Selection

Customer: Select the customer from the dropdown. Add customers via 👉 [Customer Menu](<direct purchase.md>).<br>
Displays any Due Amount for the selected customer.<br>
If the customer has any prior orders, an get deliveries Button will appear. Click it to view and select existing orders.<br>
Upon selection, the system will automatically populate:

<div style="text-align:left;">
    <ul>
        <li>Items</li>
        <li>Order Quantity</li>
        <li>Delivered Quantity</li>
        <li>Pending Quantity</li>
    </ul>
</div>

<div style="display: flex; gap: 10px;">
  <img src="../images/select customer.png" style="width: 100%; border-radius: 10px; border: 0.5px solid #333;">
  <img src="../images/select order for dn.png" style="width: 100%; border-radius: 10px; border: 0.5px solid #333;">
  <img src="../images/item auto added in dn.png" style="width: 100%; border-radius: 10px; border: 0.5px solid #333;">
</div>

The corresponding store will also be fetched automatically based on the selected order.

### Additional Information

Salesperson: Assign a salesperson. Create salespersons via 👉 [Salesperson Settings](<direct purchase.md>).<br>
Delivery Person: Select the delivery person from the dropdown. If the desired delivery person is not listed, click Add to create one.<br>
Delivery Place: Specify the delivery location. Configure via 👉 [Delivery Place Settings](<direct purchase.md>).<br>
Project: Link the delivery note to a specific project. Configure via 👉 [Project Settings](<direct purchase.md>).<br>

### Financial and Other Details

Details: Enter optional fields such as:

<div style="text-align:left;">
    <ul>
        <li>Reference Number</li>
        <li>Statement Reference</li>
        <li>Delivered Quantity</li>
        <li>Pending Quantity</li>
    </ul>
</div>

## Saving and Approving Delivery Note

Save: Once all details are entered, click Save to create the delivery note.<br>
Approve: After saving, click Approve to finalize the delivery note.

<img src="../images/approved dn.png" alt="approved dn" style="border-radius: 10px; width: 70%; height: 70%; border: 0.5px solid #333;">

## Next Step

After the delivery note is approved, the next step is to generate a Sales Invoice. For more details, refer to Sales Invoice Documentation.