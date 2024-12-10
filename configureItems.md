[← Back](miniWMSConfiguration.md)

# Configure item types and items/SKUs

Item types and SKUs (Stock Keeping Units) are critical elements in a Warehouse Management System (WMS). Properly defining these ensures efficient warehouse operations and seamless inventory management.

By setting up item types and SKUs effectively, your warehouse operations become more organized and efficient, resulting in reduced errors, faster processing times, and improved inventory control.

SKUs are unique identifiers assigned to each individual item or product. SKUs are essential for:

- Inventory Tracking.
- Order Fulfillment.
  
Click on the item type button to setup item types.  
Click on the Item button to setup the items/SKUs

The item number can be your barcode number (you can scan it) or contains alphanumerical values.

| List of items/SKUs | Item edit | Item edit picture input |
| ------------ | ----------- | ----------- |
| ![Step 1](asset/itemList.png) |  ![Step 2](asset/itemEdit.png) | ![Step 2](asset/itemEdit1.png)|


```
The spreadsheet columns should contain the first row as column names then next rows the items details, as shown below:

itemNumber       description          storageStrategy  pickStrategy  itemType  warningLevel  price    weight  length  width  height
1102863754776    Educated              20              1020          BookF        3          8.99      0.741  15      22      2.5
1102863754886    The Shining           70              1070          BookSF       3          9.5       1.041  16      23      3
1102863754996    The Grapes of Wrath   20              1020          BookF        3          7.99      0.654  12      18      2.8

and so on\.\.\.

```
