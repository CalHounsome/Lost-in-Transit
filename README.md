Links for the order numbers Imput:

Working Folder:  W:\Logistics\Elliott\Callum\LIT

Looker Folders:
Outbound: https://supergroup.eu.looker.com/looks/16330

Return: https://supergroup.eu.looker.com/looks/16329

in the script, select the week you want to obtain the data for (e.g. Week 28) - this will look up the sheet name also in the step below

Step 1) obtain frankie cratchley refund & exchange cost drilldown report, (via email), put into Refund and Exchange data in the working folder.

Step 2) Obtain Order Numbers - script prints this into output folder, put into the links above (set of order numbers for returns, set for outbound.

Step 3) Put order numbers into looker filter, obtain dataset for outbound and returns, put into the folders (outbound looker, return looker)

Step 4) Run script again, will assess the status's, if script prints non-normalized status's, these need to be normalised in the 'status lookups' sheet

Step 5) Run script again, will export clean excel file for that week in the LIT Output folder (week number will be displayed as its name)

Step 6) Copy and paste the sheet into the master data sheet, which is linked to the power bi report.

Step 7) Refresh Power BI report.
