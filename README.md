Step 1: Load Your Data
1.	Open Power BI Desktop.
2.	Click on Home > Get data > Excel (or other sources like SQL, CSV, etc.).
3.	Load your dataset (e.g., Excel file) and click Load after selecting the relevant sheet.
Step 2: Prepare the Data
1.	Go to the Model view or Power Query to clean and transform the data if needed.
2.	Ensure columns like Date, Amount, Order ID, Gender, etc., are correctly typed (Date, Number, Text).
Step 3: Create Relationships (if needed)
•	If using multiple tables, go to the Model view and create relationships between keys (e.g., Customer ID, Order ID).
Step 4: Add Filters (Slicers)
1.	From Visualizations, select the Slicer icon.
2.	Drag fields like:
o	Month
o	Channel
o	Category
into separate slicers for dynamic filtering.
Step 5: Add KPI Cards
1.	Use Card visuals for metrics like:
o	Total Quantity (Qty)
o	Total Sales (Amount)
o	B2B Count (B2B)
2.	Drag and drop the field into a Card visual and apply aggregation (Sum, Count, etc.).
Step 6: Create Graphs
1.	Column Chart for Monthly Order Count:
o	Use Month on Axis.
o	Use Order ID (Count) and Amount (Sum) on Values.
2.	Pie Chart for:
o	Order by Status.
o	Amount by Gender.
o	Orders by Channel.
Step 7: Bar Chart for Shipping States
•	Use ship-state on Y-axis.
•	Use Amount (Sum) on X-axis.
Step 8: Clustered Column Chart for Age Group
•	Use Gender and Age Group on Axis.
•	Use Count of Gender on Value.
Step 9: Format the Dashboard
•	Use themes, background colors, borders.
•	Format titles, values, and labels.
•	Align visuals for a clean layout.
Step 10: Save & Publish
•	Save your report (.pbix).
•	Click on Publish to upload it to Power BI Service.
