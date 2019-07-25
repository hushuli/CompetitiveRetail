# CompetitiveRetail
1. The file prices.csv describes prices collected for products, represented as UPC, at specific
physical store locations, represented as Store ID. The auditors who collected prices at each
store are represented as Auditor ID. Store attribute information is described in stores.json,
and auditor information is shown in auditors.csv. Can you transform these sources into a
cross-tabulation of regional prices alongside each other, broken down by banner, and write
this out to a spreadsheet (CSV or XLSX)? Note that a given product is not guaranteed to
be found in all markets at a given banner.

![output](/img/output.PNG)


2. Do you notice anything that seems off with the data we've collected? Call out anything you
find noteworthy. Again, it is not necessary to use the model to find the anomalies we're
looking for, but you may use it as a tool to assist you if you wish.

![des](/img/describe.PNG)

![heatmap](/img/heatmap.PNG)

* Summary:


From the data we can see Northern California average of product price is higher than Kansas, New York and Texas. 
There have an anomalies phenomenon at 25th percentails, Kansas has price at 1.99 which way lower than other States which price around $16 and $19.
There may have data input mistake or something need noticed.
From the heatmap we can see there doesnt have wholefoods data in Knasas, safeway in New York, and Wegmans in Northern California.
There may have missing data or there doesnt have those retail in that State, we need to confirm.
