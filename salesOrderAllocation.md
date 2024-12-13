[← Back](README.md)

<h1>Sales Order Allocation</h1>
<p>The picking process involves the following steps:</p>
<p>The sales orders upload can be done multiple ways:</p>
<ul>
  <li>Manually add a sales order via the sales order screen by clicking the sales order button from the Home screen.</li>
  <li>Import sales orders through the "Import Sales Orders" button in the Sales Order Results screen.</li>
  <li>You have four options:</li>
  <ul>
    <li>Import sales orders via an Excel spreadsheet.</li>
    <li>Import sales orders from Shopify using Shopify credentials.</li>
    <li>Import sales orders from Amazon using Amazon credentials.</li>
    <li>Import sales orders from eBay using eBay credentials.</li>
  </ul>
</ul>
<p>Tape on one of the sales order. check the items and quantity on this order, then click on Allocate. This should generate picking work so the order can be picked.</p>
<p>Navigate to the "Pick Stock" screen by clicking the "Pick Stock" button from the home screen.</p>

<h2>Picking Process</h2>
<table style="width: 100%; border-collapse: collapse;">
  <tr>
    <!-- Column 1 -->
    <td style="width: 33%; text-align: center; vertical-align: top;">
      <strong>Step 1: PO ready to picking</strong>
      <p>Verify your sales order is in the dropdown list.</p>
      <img src="asset/Picking1.png" alt="Step 1" width="200">
    </td>
    <!-- Column 2 -->
    <td style="width: 33%; text-align: center; vertical-align: top;">
      <strong>Step 2: Picking from a location</strong>
      <p>The Mini-WMS app will automatically know which location the item will be picked from. The operator will go straight to the shown location on the picking screen. You can scan the item number and shipping container or enter them manually. Click on the Pick button, then take the stock from the location into the container.</p>
      <img src="asset/Picking2.png" alt="Step 2" width="200">
    </td>
    <!-- Column 3 -->
    <td style="width: 33%; text-align: center; vertical-align: top;">
      <strong>Step 3: Short pick</strong>
      <p>You can pick less than the required quantity. The app will ask you to confirm:</p>
      <p>1- Do you want to pick the remaining quantity later?</p>
      <p>2- Or do you want to short pick the remaining quantity?</p>
      <img src="asset/Picking3.png" alt="Step 3" width="200">
    </td>
  </tr>
</table>
