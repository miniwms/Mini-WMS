[← Back](README.md)

# Sales Order Allocation

Allocation of sales orders refers to the process of assigning available inventory to fulfill customer sales orders.  
It ensures that the required stock is reserved for specific orders, preventing overselling or double allocation of the same inventory.  

Mini-WMS allocation does support full or partial allocation:  
### Full allocation:  
When you click Allocate button, Mini-WMS is able to reserve stock for all the sales order lines, and generate all picking work.  
When you clikc Allocate button, Mini-WMS is not able to fullfill all the sales order lines. So, you can Allocate again when stock is replenished.  

### Key Components of Allocation in Mini-WMS:

**Inventory Reservation:**
- Allocating specific quantities of stock from available inventory to meet the demand in sales orders.
- Reserved inventory is marked and cannot be used for other orders until it is deallocated or fulfilled.

**Allocation Rules:**  
Mini-WMS allocation follows predefined rules or strategies, such as:
- FIFO (First-In-First-Out): Assign the oldest stock first.
- FEFO (First-Expired-First-Out): Allocate stock based on expiration dates.
- Location Priority: Allocate items from preferred locations (e.g., pick zones location class).
- Batch or Lot Priority: Allocate based on batch/lot numbers.

**Stock Availability Check:**  
- The system checks real-time stock availability in the warehouse to determine if items can be allocated for each sales order.

**Single order or group of orders Allocation:**
- Navigate to a single sales order and click the 'Allocate' button.
- Navigate to the sales order result screen and click the 'Allocate' button. Specify the date range. This will allocate all orders within that range.
  
**Partial or Full Allocation:** 
- Full Allocation: All items and quantities in the sales order are allocated.
- Partial Allocation: Only part of the order is allocated if there is insufficient stock.

**Allocation vs. Picking:** 
- Allocation is the planning phase, where inventory is assigned to orders.
- Picking is the execution phase, where the assigned inventory is physically picked from the warehouse to fulfill the allocated orders.

The system checks real-time stock availability in the warehouse to determine if items can be allocated for each sales order.

<table>
  <tr>
    <td style="width: 50%; text-align: left;">View the sales order you want to allocate.</td>
    <td style="width: 50%; text-align: left;">Check the quantity ordered.</td>
  </tr>
  <tr>
    <td style="vertical-align: top;">
      <img src="asset/salesOrderDetail1.png" alt="Step 1">
    </td>
    <td style="vertical-align: top;">
      <img src="asset/salesOrderDetail2.png" alt="Step 2">
    </td>
  </tr>
  <tr>
    <td style="width: 50%; text-align: left;">With Sales order SAL0001, after you click on Allocate button, a popup shows the quantity purcentage allocated. In this case, not all stock can fully be allocated. You have the choice to abort or continue.</td>
    <td style="width: 50%; text-align: left;">The status changed to 'Allocated'.</td>
  </tr>
  <tr>
    <td style="vertical-align: top;">
      <img src="asset/salesOrderAllocate1.png" alt="Step 1">
    </td>
    <td style="vertical-align: top;">
      <img src="asset/salesOrderAllocate2.png" alt="Step 2">
    </td>
  </tr>
  <tr>
    <td style="width: 50%; text-align: left;">In other cases, example sales order SAL0007, all lines are allocated.</td>
    <td style="width: 50%; text-align: left;">Status is set to Allocate.</td>
  </tr>
  <tr>
    <td style="vertical-align: top;">
      <img src="asset/salesOrderAllocate3.png" alt="Step 1">
    </td>
    <td style="vertical-align: top;">
      <img src="asset/salesOrderAllocate4.png" alt="Step 2">
    </td>
  </tr>
  <tr>
    <td style="width: 50%; text-align: left;">You can allocate multiple orders at onces.</td>
    <td style="width: 50%; text-align: left;">Click Allocate button and select date range.</td>
  </tr>
  <tr>
    <td style="vertical-align: top;">
      <img src="asset/salesOrderResults.png" alt="Step 1">
    </td>
    <td style="vertical-align: top;">
      <img src="asset/salesOrderAllocate7.png" alt="Step 2">
    </td>
  </tr>
  <tr>
    <td style="width: 50%; text-align: left;">For every order a popup shows up showing purcentage fill,</td>
    <td style="width: 50%; text-align: left;">and gives you the choice to allocate or abort.</td>
  </tr>
  <tr>
    <td style="vertical-align: top;">
      <img src="asset/salesOrderAllocate7.png" alt="Step 1">
    </td>
    <td style="vertical-align: top;">
      <img src="asset/salesOrderAllocate8.png" alt="Step 2">
    </td>
  </tr>
  
  <tr>
    <td style="width: 50%; text-align: left;">Click allocate or abort.</td>
    <td style="width: 50%; text-align: left;"></td>
  </tr>
  <tr>
    <td style="vertical-align: top;">
      <img src="asset/salesOrderAllocate9.png" alt="Step 1">
    </td>
    <td style="vertical-align: top;">
    </td>
  </tr>
</table>
