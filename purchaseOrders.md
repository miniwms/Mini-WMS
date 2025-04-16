[← Back](README.md)

# Purchase orders.

Purchase orders in your Mini-WMS can be added either manually or via the import of excel spreadsheet methods in the purchase order screen.

The purchase order can be in one of the following statuses at any time: <br>The status goes from:<br>0 (available)<br> 2  (in receiving) When receiving work exist<br> 10 (Fully received and closed)

<table>
  <tr>
    <th>Click on the purchase Order button</th>
    <th>This screen displays a list of purchase orders.</th>
    <th>Click '+' to add new purchase order.</th>
  </tr>
  <tr>
    <td style="vertical-align: top;">
      <img src="asset/purchaseOrderButton.png" alt="Step 1">
    </td>
    <td style="vertical-align: top;">
      <img src="asset/purchaseOrderScreen1.png" alt="Step 2">
    </td>
    <td style="vertical-align: top;">
      <img src="asset/purchaseOrderScreen2.png" alt="Step 2">
    </td>
  </tr>
  <tr>
    <th>After you click Add, the App shows the PO header and details. To delete the purchase order click the delete button.</th>
    <th>To add more PO lines, click the '+' sign. To delete the purchase order line click the delete button.</th>
    <th></th>
  </tr>
  <tr>
    <td style="vertical-align: top;">
      <img src="asset/purchaseOrderScreen3.png" alt="Step 1">
    </td>
    <td style="vertical-align: top;">
      <img src="asset/purchaseOrderScreen4.png" alt="Step 2">
    </td>
    <td style="vertical-align: top;">
    </td>
  </tr>
  <tr>
    <th>When looking at the purchase order result screen, you can slide to the right to see more details.</th>
    <th>To the right you can see the quantity ordered, quantity to put and quantity received.</th>
    <th>If the item is lot controlled, then you should be able to see a lot number on the PO line item.</th>
  </tr>
  <tr>
    <td style="vertical-align: top;">
      <img src="asset/purchase-1-1.png" alt="Step 1">
    </td>
    <td style="vertical-align: top;">
      <img src="asset/purchaseOrder-1-2.png" alt="Step 2">
    </td>
    <td style="vertical-align: top;">
      <img src="asset/purchaseOrder-1-3.png" alt="Step 2">
    </td>
  </tr>
</table>

**Import process: The format of the Excel file to Import**:  
- You need to fill in two sheets:  
  - One for purchase order headers.  
  - One for purchase order details.
    
To import purchase orders via excel, click on the "Import Purchase Orders" button and upload your Excel spreadsheet.
The spreadsheet should consist of two sheets: "purchaseorder" and "purchaseorderline". The import process will look for these sheet names with the exact spelling, it is case sensitive.
So, it needs to be written as they are. Below are the excel sheets and their columns.

The purchaseorder spreadsheet columns should contain the first row as the column names of the purchase order header fields, then, in the next rows the header information, as shown below:
In the case below we have shown 2 orders. You can have as many as you like.  

```
"purchaseorder"
po_number  vendor_number
POrder001  Amazon
POrder002  Waterstones
```

The purchaseorderline spreadsheet columns should contain the first row as the column names of the purchase order detail fields, then, in the next rows the details information, as shown below:  
You can see below, some items are lot controlled and some are not. Also, those item requiring expiry date, it has been set, otherwise the expiry date should be set to 2100-01-01 i.e. never expires. For the fifo date default is 2000-01-01.  

```
"purchaseorderline"
po_number   line_number   item_number     lot_num   fifo_date   expiry_date   qty_ordered  
POrder001   1             1628437592043   LOT1020   2000-01-01  2024-09-01    6  
POrder001   2             7026814395746             2000-01-01  2024-09-05    9  
POrder001   3             9421863057291   LOT1099   2000-01-01  2024-09-20    10  
POrder002   1             5139678402157             2000-01-01  2024-09-01    5  
POrder002   2             8715246309132   LOT1000   2000-01-01  2024-09-01    2  
```
