<h1>Location classes or location groups</h1>

<p>We have adopted the following location labelling system:</p>
<p>AISLE - ROW - COLUMN</p>
<p><b>A5   -   05  -  10</b></p>

<ul>
  <li><b>A5</b> represents the <b>Aisle number</b>, indicating the specific section of the warehouse.</li>
  <li><b>05</b> represents the <b>Row number</b>, referring to the horizontal line of storage within the aisle.</li>
  <li><b>10</b> represents the <b>Column number</b>, identifying the vertical position or specific bin within the row.</li>
</ul>
<table style="width: 100%; border-collapse: collapse;">
  <tr>
    <!-- Column 1 -->
    <td style="width: 60%; text-align: right; vertical-align: top;">
      <img src="asset/locationClass.png" alt="Step 1" width="600">
    </td>
    <!-- Column 2 -->
    <td style="width: 40%; text-align: right; vertical-align: top;">
      <img src="asset/locationsAdd.png" alt="Step 2" width="300">
    </td>
  </tr>
</table>
<ul>
  <li>Click the Location button, the next screen will display the list of existing locations in alphabetical order.</li>
  <li>You can add new locations by using the + button from the locations result screen. To do so, enter the starting and ending locations in this format: starting location A10000 and end location A30505. Enter a location class and length, width & height. A1 and A3 represent the Aisle number, the second two digits represents the rows and the last two represent the column.</li>
  <li>This will generate 96 physical locations belonging to a single location class with identical dimensions. You can repeat the same process to generate other sets of locations with different location class.</li>
  <li>This location labelling system will work either you have one racking or multiple rackings..</li>
  <li>You can delete locations by using the bin button. Enter the start and end locations to complete the delete.</li>
  <li>You can also import locations from an excel spreadsheet. Use "import locations" button.</li>
</ul>

<p>The spreadsheet columns should contain the first row as column names then next rows the location details:</p>

<p>location  loc_class  empty_flg  length  width  height</p>
<p>A10101      100        Y          50      30     40</p>
<p>A10102      100        Y          50      30     40</p>
<p>A10103      100        Y          50      30     40</p>
<p>and so on...</p>
<p>length, width and height are in user defined cm or inch</p>

<h2 style="color: #009688;">Location Fields:</h2>
<ul>
  <li><strong>Location</strong>: Location name.</li>
  <li><strong>Empty flag</strong>: If set to Yes, the location is empty, otherwise stock exist in it.</li>
  <li><strong>Location class</strong>: Identifier that groups a set of physical locations.</li>
  <li><strong>Length</strong>: Length of the location.</li>
  <li><strong>Width</strong>: Width of the location.</li>
