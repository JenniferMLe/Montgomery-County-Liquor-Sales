## Montgomery County Liquor Sales Analysis

This project uses excel and Tableau to analyze the Warehouse and Retail Sales dataset from Montgomery County's Alcohol Beverage Services linked <a href="https://data.montgomerycountymd.gov/Community-Recreation/Warehouse-and-Retail-Sales/v76h-r7br/about_data" target="_blank">here</a>.

Some context from wikipedia:

"Alcohol Beverage Services, previously known as the Department of Liquor Control (DLC) is a government agency within the County of Montgomery, Maryland, and is the wholesaler of beer, wine and spirits alcoholic beverage throughout the county's 507-square-mile (1,310 km2) area. Montgomery County Department of Liquor Control also exercises control over retail sales for off-premises consumption, either through government-operated package stores or designated agents."

more info <a href="https://en.wikipedia.org/wiki/Montgomery_County_Alcohol_Beverage_Services" target="_blank">here</a>.

### Dataset Terms and Definitions (from various sources)
- <u>ABS</u>: Alcohol Beverage Services, previously called the Department of Liquor Control (DLC)
- <u>Retail Sales</u>: Cases of product sold from ABS dispensaries
- <u>Retial Transfers</u>: Cases of product transferred to ABS dispensaries
- <u>Warehouse Sales</u>: Cases of product sold to MC licensees
- <u>Beer/Wine Credit</u>: Credit or refund for returned, damaged, or unsellable products.
- <u>NR</u>: Stands for Non-Returnable and typically refers to non-returnable bottles or packaging.
- <u>100P</u>: Stands for 100 Proof or 50% Alcohol by Volumn (ABV)
- <u>#/# e.g 6/4</u>: Stands for 6 packs per case and 4 bottles per pack

### Data Cleaning with Excel
1. Replace blank values in Supplier column by filtering for blank cells and replacing them with 'NULL'
2. Replaced blank item type cell for item description FONTANAFREDDA BAROLO SILVER LABEL 750 ML with 'WINE'

### View Dashboard
<a href="https://public.tableau.com/app/profile/jennifer.le2881/viz/sales_17423555670390/SalesDashboard" target="_blank">Dashboard</a>

View in full screen to prevent text from being cut off.