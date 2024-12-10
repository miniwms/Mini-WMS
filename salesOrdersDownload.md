[← Back](README.md)

# Sales orders download.

Sales orders in your Mini-WMS can be managed through multiple methods. They can be automatically pulled from your Shopify, Amazon, or eBay shops, imported from an Excel spreadsheet, or added manually via the sales order screen.

![Visual Guide](asset/SODownloads.png)

**Shopify Integration**: Requires:  
- Your Shopify store URL.  
- Your Shopify API access token.  

**Amazon Integration**: Requires:  
- Your Amazon marketplace.  
- Amazon client ID.  
- Amazon client secret.  
- Amazon refresh token.  

**eBay Integration**: Requires:  
- Your eBay API OAuth token.  

**Excel Import**:  
- You need to fill in two sheets:  
  - One for sales order headers.  
  - One for sales order details.  
    
Each method provides flexibility to suit your operational needs and streamline sales order processing.

```
The spreadsheet columns should contain the first row as column names then next rows the items details, as shown below:

itemNumber       description          storageStrategy  pickStrategy  itemType  warningLevel  price    weight  length  width  height
1102863754776    Educated              20              1020          BookF        3          8.99      0.741  15      22      2.5
1102863754886    The Shining           70              1070          BookSF       3          9.5       1.041  16      23      3
1102863754996    The Grapes of Wrath   20              1020          BookF        3          7.99      0.654  12      18      2.8

and so on\.\.\.

```
