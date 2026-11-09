# MizuMi & Bomi Product Sales Analytics

Independent portfolio project by Wiwat Wetmongkongorn analyzing a public product-listing snapshot from the MizuMi & Bomi Official Shop on Shopee Thailand. The supplied report identifies the collection date as 20 March 2026 and describes 167 included listings.

## Business questions
- Which products and categories lead in estimated sales value and units sold?
- How do price, discounts, and ratings relate to reported sales indicators?
- What product and category patterns can inform further investigation?

## Tools and workflow
Excel and Power Query for preparation, SQLite for analysis, and Power BI for reporting. The report also documents AI-assisted Python product-name cleaning. Separate SQL query and Python source files are not included in this upload.

## View the work
Start with the analysis report and dashboard PDF. Open the `.pbix` file in Power BI Desktop on Windows. The Excel workbooks show raw, cleaned, and finalized datasets; the `.db` file can be inspected using SQLite.

## Interpretation and limitations
This is a single snapshot, not a transaction history. Units sold are approximate listing indicators. Estimated sales value is calculated from snapshot price and estimated units sold; it is not verified company revenue and may differ substantially from realized sales. Associations do not establish causal effects of prices, discounts, or ratings. Refreshing the Power BI report may require updating local source paths. The supplied report's findings have not been independently revalidated for this upload.

This project is independent and is not affiliated with or endorsed by the brands or Shopee. No redistribution license is granted for third-party material.

## Files
- `01_Raw_Dataset_Step1.xlsx`
- `02_Cleaned_Dataset_Step2.xlsx`
- `03_Finalized_Dataset_Step3.xlsx`
- `04_SQL_Database.db`
- `05_MizuMI_PowerBI_Dashboard.pbix`
- `05_MizuMi_PowerBI_Dashboard_Export.pdf`
- `06_Mizumi_Analysis_Report.pdf`
