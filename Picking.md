[← Back](README.md)

# Allocation and Picking Process  

Allocation generates picking work to streamline order fulfillment. Follow these steps to begin:

### Navigate to the Picking Screen  
- Click on "Pick Stock" from the main screen.
- Select the sales order you want to pick.
- Picking Options

### The picking process in Mini-WMS offers flexibility to suit different scenarios:
- Pick full quantity: Fulfill the entire order line in one operation.
- Pick partial quantity: Pick part of the order and defer the rest for later.
- Short pick: Record a short pick for the sales order line, either as a zero pick or a partial pick.

### Advanced Features
Mini-WMS supports advanced picking options for enhanced traceability and accuracy:
- Lot control: Pick stock based on lot numbers.
- Serial number tracking: Ensure precise tracking of serialized inventory.

### Container Options
- You can pick the entire order into a single container, or distribute it across multiple containers as needed.
- This flexibility ensures accurate and efficient order fulfillment, tailored to your warehouse operations.

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
