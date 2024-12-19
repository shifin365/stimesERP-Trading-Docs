# **Item Management**

## **Overview**
The **Item Management** section allows you to manage and create items for stock. You can add products either manually or in bulk using an Excel file. This guide walks you through the steps of adding items, setting up taxes, and configuring alternate units of measurement (UOM). 

---

## **How to Access Item Management**
1. **Navigate to Stock > Items**.
2. You will be directed to the **Item Dashboard** where all items are displayed.

---

## **Searching Items**
- Use the **Search** option at the top of the page to find a specific item quickly.
- There is also an **Advanced Filter** option to refine your search.

<img src="../images/ITEM DASHBOARD.png" alt="ITEM DASHBOARD" style="border-radius: 10px; width: 70%; height: 70%; border: 0.5px solid #333;">

---

## **Creating Items**
You can create items in two ways:
- **Bulk Item Import**
- **Manual Entry**

### **Bulk Item Import**
1. To import items in bulk, click the **Excel Operations** button.
2. Select **Import from Excel**. 
3. You will be prompted to download the **Sample Import Data Format**. 
4. Open the downloaded file, fill in the item data, and then upload it using the **Import Excel** option from the dashboard.

<img src="../images/BULK IMPORT ITEM.png" alt="BULK IMPORT ITEM" style="border-radius: 10px; width: 70%; height: 70%; border: 0.5px solid #333;">

### **Manual Item Creation**
To create a new item manually, click the **Create New** button in the top-right corner.

---

## **Creating a New Item**
When you click **Create New**, you will see several tabs to fill out:

### **General Tab**
Here, you will select the item type and enter basic information.

#### 1. **Item Type**
   - **Goods** or **Services** (Radio button selection)
   
   If **Goods** is selected:
   - **Item Image**: Upload an image of the item.
   - **Barcode**: Enter the barcode.
   - **Item Code**: Enter the item unique code.
   - **Item Name**: Enter the name of the item.
   - **Alias Name**: Optional.
   - **Description**: A brief description of the item.
   - **Item Group**: Select item group or you can create using click this link👉 [item group](<direct_purchase.md>).
   - **Item Type**: Choose from **Manufacture**, **General**, or **Component**.
   - **Unit**: Select from available units or create a new one using 👉 [Unit](<direct_purchase.md>).
   - **Brand**: Select brand from dropdown or you can create using 👉 [Brand](<direct_purchase.md>).
   - **Kit Type**: If this is a kit, check the **Is Kit** checkbox. You will then be able to select the items for this kit, along with quantity and price.
   - **Cost Price**: Enter the cost price of the item.
   - **Selling Price**: Enter the selling price. If there are multiple price points (e.g., retail, wholesale), click the **Add** button to enter different prices.
     - **Price Type**: Select **Retail** or **Wholesale** and enter the price.
   - **Default Discount**: If applicable, check the **Is Default Discount** checkbox and specify the discount value (in percentage and amount).
   - **Preferred Supplier**: Select or create a supplier using 👉 [supplier](<direct_purchase.md>).
   - **Lead Time in Days**: Enter the lead time.
   - **Reorder Level**: Specify the reorder level.
   - **Reorder Quantity**: Enter the reorder quantity.
   - **Reorder Unit**: Select the reorder unit.
   - **Weight per Unit**: Specify the weight per unit.
   - **Opening Stock**: Enter the initial stock quantity.
   - **Shelf Life in Days**: Specify the shelf life if applicable.
   - **Valuation Rate Based On**: Choose from **FIFO**, **LIFO**, **Average Cost**, or **Specific Identification**.
   - **Properties**: Select properties such as **Machinable** or **Fixed Asset**.
   - **Allow Sale**: Check if the item is allowed for sale.
   - **Allow Purchase**: Check if the item is allowed for purchase.
   - **Maintain Inventory**: Check if the item should be tracked in inventory.
   - **Allow Negative Stock**: **Do NOT check this box** without confirming with your admin team.

   **Note**: Be sure to confirm with your admin before enabling **Allow Negative Stock**.

<div style="display: flex; gap: 10px;">
  <img src="../images/CREATE NEW ITEM GOODS.png" style="width: 100%; border-radius: 10px; border: 0.5px solid #333;">
  <img src="../images/CREATE NEW ITEM GOODS 2.png" style="width: 100%; border-radius: 10px; border: 0.5px solid #333;">
</div>

   **Tax Details**:
   - **Cost Price Includes Tax**: Check if the cost price includes tax.
   - **Selling Price Includes Tax**: Check if the selling price includes tax.
   - **Delivered by Supplier (Drop Ship)**: If this item is delivered by the supplier, check the box.

---

### **Tax Tab**
- **Taxable** or **Non-Taxable** (Radio button selection)
   - If **Taxable**:
     - **SAC Code**: Search and select the SAC code.
     - **Intra-State Tax Rate**: Select the applicable tax rate for intra-state.
     - **Inter-State Tax Rate**: Select the applicable tax rate for inter-state.
   - If **Non-Taxable**:
     - **Description**: Enter a description for non-taxable items.

<img src="../images/TAX IN ITEM.png" alt="TAX IN ITEM" style="border-radius: 10px; width: 70%; height: 70%; border: 0.5px solid #333;">

---

### **Alternate UOM Tab**
1. Click the **Add** button to add alternate units of measurement (UOM).
2. Fill in the following details:
   - **Unit**
   - **Item Name**
   - **Item Code**
   - **Alias**
   - **Barcode**
   - **Conversion Factor**: How many of the unit fits into the base unit.
   - **Cost Price**
   - **Selling Price**

   This tab is not mandatory to fill.

<img src="../images/UOM IN ITEM.png" alt="UOM IN ITEM" style="border-radius: 10px; width: 70%; height: 70%; border: 0.5px solid #333;">

---

### **If Item is a Service**
- Follow similar steps as for Goods.
- Add a **Barcode**, **Item Code**, **Item Name**, and **Description**.
- **Item Type**: Select whether it's **Manufacture**, **General**, or **Component**.
- Set the **Unit**, **Brand**, **Cost Price**, and **Selling Price** (same as for goods).
- Under the **Tax** tab, set whether the item is taxable or non-taxable, and provide necessary tax details.
- Under the **Alternate UOM** tab, add any alternate UOM if applicable.

<img src="../images/CREATE NEW ITEM SERVICES.png" alt="CREATE NEW ITEM SERVICES" style="border-radius: 10px; width: 70%; height: 70%; border: 0.5px solid #333;">

---

## **Saving the Item**
Once all tabs are completed:
- Click the **Save** button.
- The newly created item will now appear in the **Item Dashboard**.

---

## **Item Dashboard**
After saving, your item will be listed in the **Item Dashboard** where you can view, edit, and manage your stock items.

---

## **🎉 Congratulations! 🎉**
You have successfully created a new item! You're one step closer to mastering item management! 🎯 Keep going, and don’t forget to check your items regularly. 😎

---