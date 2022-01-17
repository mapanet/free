## Table definitions
Mapanet table definitions

<br>
#### Regions table

<table class="table table-bordered table-striped">
<thead>
  <tr><th width="15%">Field</th><th width="15%">Field type</th><th width="70%">Description</th><th width="20">Key</th></tr>
</thead>
<tbody>
  <tr><td>ISO</td><td>varchar(2)</td><td>Country code ISO 3166-1</td><td>PK</td></tr>
  <tr><td>Country</td><td>nvarchar(45)</td><td>Country name</td><td>&nbsp;</td></tr>
  <tr><td>Language</td><td>varchar(2)</td><td>Language code</td><td>PK</td></tr>
  <tr><td>Level</td><td>int</td><td>Administrative level</td><td>PK</td></tr>
  <tr><td>Category</td><td>nvarchar(45)</td><td>Type of administrative division</td><td>&nbsp;</td></tr>
  <tr><td>CategoryEN</td><td>nvarchar(45)</td><td>Type in English</td><td>&nbsp;</td></tr>
  <tr><td>Region1Code</td><td>varchar(10)</td><td>Administrative level 1 code</td><td>PK</td></tr>
  <tr><td>Region2Code</td><td>varchar(10)</td><td>Administrative level 2 code</td><td>PK</td></tr>
  <tr><td>Region3Code</td><td>varchar(10)</td><td>Administrative level 3 code</td><td>PK</td></tr>
  <tr><td>Region4Code</td><td>varchar(10)</td><td>Administrative level 4 code</td><td>PK</td></tr>
  <tr><td>Region</td><td>nvarchar(85)</td><td>Administrative region name</td><td></td></tr>
  <tr><td>Latitude</td><td>Decimal(10,6)</td><td>EPSG:4326 (WGS84)</td><td>&nbsp;</td></tr>
  <tr><td>Longitude</td><td>Decimal(10,6)</td><td>EPSG:4326 (WGS84)</td><td>&nbsp;</td></tr>
  <tr><td>Elevation</td><td>Integer</td><td>Elevation in meters (average)</td><td>&nbsp;</td></tr>
  <tr><td>ISO2</td><td>varchar(10)</td><td>ISO code</td><td>&nbsp;</td></tr>
  <tr><td>FIPS</td><td>varchar(10)</td><td>American code</td><td>&nbsp;</td></tr>
  <tr><td>NUTS</td><td>varchar(12)</td><td>European Union area code</td><td>&nbsp;</td></tr>
  <tr><td>HASC</td><td>varchar(12)</td><td>Statoids code</td><td>&nbsp;</td></tr>
  <tr><td>STAT</td><td>varchar(20)</td><td>Statistics code - organization of country</td><td>&nbsp;</td></tr>
</tbody>
</table>

<br>
#### Postal Codes

<table class="table table-bordered table-striped">
<thead>
  <tr><th width="15%">Field</th><th width="15%">Field type</th><th width="70%">Description</th><th width="20">Key</th></tr>
</thead>
<tbody>
  <tr><td>ISO</td><td>varchar(2)</td><td>Country code ISO 3166-1</td><td>PK</td></tr>
  <tr><td>Country</td><td>nvarchar(45)</td><td>Country name</td><td>&nbsp;</td></tr>
  <tr><td>Language</td><td>varchar(2)</td><td>Language code</td><td>PK</td></tr>
  <tr><td>ID</td><td>bigint</td><td>Record ID</td><td>PK</td></tr>
  <tr><td>PostalCode</td><td>varchar(10)</td><td>Postal code</td><td>&nbsp;</td></tr>
  <tr><td>Region1</td><td>nvarchar(85)</td><td>Administrative level 1 name</td><td>&nbsp;</td></tr>				
  <tr><td>Region2</td><td>nvarchar(85)</td><td>Administrative level 2 name</td><td>&nbsp;</td></tr>				
  <tr><td>Region3</td><td>nvarchar(85)</td><td>Administrative level 3 name</td><td>&nbsp;</td></tr>				
  <tr><td>Region4</td><td>nvarchar(85)</td><td>Administrative level 4 name</td><td>&nbsp;</td></tr>
  <tr><td>Locality</td><td>nvarchar(110)</td><td>Locality name</td><td>&nbsp;</td></tr>
  <tr><td>Suburb</td><td>nvarchar(110)</td><td>Suburb name</td><td>&nbsp;</td></tr>
  <tr><td>Latitude</td><td>Decimal(10,6)</td><td>EPSG:4326 (WGS84)</td><td>&nbsp;</td></tr>
  <tr><td>Longitude</td><td>Decimal(10,6)</td><td>EPSG:4326 (WGS84)</td><td>&nbsp;</td></tr>
  <tr><td>Elevation</td><td>Integer</td><td>Elevation in meters (average)</td><td>&nbsp;</td></tr>
  <tr><td>Timezone</td><td>varchar(35)</td><td>Time zone name (Olson)</td><td>&nbsp;</td></tr>
  <tr><td>UTC</td><td>varchar(6)</td><td>Coordinated Universal Time</td><td>&nbsp;</td></tr>
  <tr><td>DST</td><td>varchar(6)</td><td>Daylight saving time</td><td>&nbsp;</td></tr>
</tbody>
</table>

<br>
#### Streets table

<table class="table table-bordered table-striped">
<thead>
  <tr><th width="15%">Field</th><th width="15%">Field type</th><th width="70%">Description</th><th width="20">Key</th></tr>
</thead>
<tbody>
  <tr><td>ISO</td><td>varchar(2)</td><td>Country code ISO 3166-1</td><td>PK</td></tr>
  <tr><td>Country</td><td>nvarchar(45)</td><td>Country name</td><td>&nbsp;</td></tr>
  <tr><td>Language</td><td>varchar(2)</td><td>Language code</td><td>PK</td></tr>
  <tr><td>ID</td><td>bigint</td><td>Record ID</td><td>PK</td></tr>
  <tr><td>PostalCode</td><td>varchar(10)</td><td>Postal code</td><td>&nbsp;</td></tr>
  <tr><td>Region1</td><td>nvarchar(45)</td><td>Administrative level 1 name</td><td>&nbsp;</td></tr>				
  <tr><td>Region2</td><td>nvarchar(45)</td><td>Administrative level 2 name</td><td>&nbsp;</td></tr>				
  <tr><td>Region3</td><td>nvarchar(45)</td><td>Administrative level 3 name</td><td>&nbsp;</td></tr>				
  <tr><td>Region4</td><td>nvarchar(85)</td><td>Administrative level 4 name</td><td>&nbsp;</td></tr>
  <tr><td>Locality</td><td>nvarchar(110)</td><td>Locality name</td><td>&nbsp;</td></tr>
  <tr><td>Suburb</td><td>nvarchar(110)</td><td>Suburb name</td><td>&nbsp;</td></tr>
  <tr><td>Street</td><td>nvarchar(110)</td><td>Name</td><td>&nbsp;</td></tr>
  <tr><td>NumType</td><td>varchar(10)</td><td>Segment designation other than number: porta, door...</td><td>&nbsp;</td></tr>
  <tr><td>NumLow</td><td>varchar(10)</td><td>Street Lower number</td><td>&nbsp;</td></tr>
  <tr><td>NumHigh</td><td>varchar(10)</td><td>Street Upper number</td><td>&nbsp;</td></tr>
  <tr><td>OddEven</td><td>varchar(1)</td><td>Street side: B=both E=even O=odd N=None</td><td>&nbsp;</td></tr>
  <tr><td>Enum</td><td>varchar(30)</td><td>Enumeration when other than number</td><td>&nbsp;</td></tr>
  <tr><td>Building</td><td>nvarchar(110)</td><td>Building name</td><td>&nbsp;</td></tr>
  <tr><td>IntType</td><td>varchar(15)</td><td>Interior (Apartment, Suite, etc.) * US and Canada only</td><td>&nbsp;</td></tr>
  <tr><td>IntLow</td><td>varchar(10)</td><td>Interior lower number * US and Canada only</td><td>&nbsp;</td></tr>
  <tr><td>IntHigh</td><td>varchar(10)</td><td>Interior upper number * US and Canada only</td><td>&nbsp;</td></tr>
  <tr><td>IntOddEven</td><td>varchar(1)</td><td>Interior range: B=both E=even O=odd N=None * US and Canada only</td><td>&nbsp;</td></tr>
  <tr><td>Latitude</td><td>Decimal(10, 6)</td><td>EPSG:4326 (WGS84)</td><td>&nbsp;</td></tr>
  <tr><td>Longitude</td><td>Decimal(10, 6)</td><td>EPSG:4326 (WGS84)</td><td>&nbsp;</td></tr>
  <tr><td>Elevation</td><td>Integer</td><td>Elevation in meters</td><td>&nbsp;</td></tr>
  <tr><td>Timezone</td><td>varchar(35)</td><td>Time zone name (Olson)</td><td>&nbsp;</td></tr>
  <tr><td>UTC</td><td>varchar(6)</td><td>Coordinated Universal Time</td><td>&nbsp;</td></tr>
  <tr><td>DST</td><td>varchar(6)</td><td>Daylight saving time</td><td>&nbsp;</td></tr>
</tbody>
</table>

<br>
#### Boundaries/Polygons of postal codes table

<table class="table table-bordered table-striped">
<thead>
  <tr><th width="15%">Field</th><th width="15%">Field type</th><th width="70%">Description</th><th width="20">Key</th></tr>
</thead>
<tbody>
  <tr><td>ISO</td><td>varchar(2)</td><td>Country code ISO 3166-1</td><td>PK</td></tr>
  <tr><td>Layer</td><td>int</td><td>Layer (7)</td><td>PK</td></tr>
  <tr><td>Code</td><td>varchar(12)</td><td>Postal code</td><td>PK</td></tr>
  <tr><td>Name</td><td>nvarchar(85)</td><td>Name: "Postal code: 33129"</td><td>&nbsp;</td></tr>
  <tr><td>Geometry</td><td>geography</td><td>POINT(Lon,Lat)&nbsp; POLYGON((Lon,Lat))&nbsp; MULTIPOLYGON(((Lon,Lat)))</td><td>&nbsp;</td></tr>				
  </tbody>
</table>
