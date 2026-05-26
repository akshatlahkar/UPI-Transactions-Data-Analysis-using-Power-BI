# UPI-Transactions-Data-Analysis-using-Power-BI
Interactive Power BI dashboard analyzing UPI transaction trends, customer behavior, balances, merchant activity, and payment patterns using Power Query, DAX, Sync Slicers, Conditional Formatting, Bookmarks, Matrix Visuals, and Power BI Service.

---

## Problem Statement

This project focuses on analyzing UPI transaction data using Power BI to identify transaction trends, customer demographics, merchant activity, payment behavior, and balance variations over time.

The dashboard allows users to dynamically filter and analyze transaction details using synchronized slicers, report-level filters, matrix visuals, and interactive bookmarks. Power Query transformations, data profiling operations, DAX calculated columns, and advanced formatting techniques were implemented to prepare and model the dataset.

The project involved data cleaning, column profiling, conditional formatting, matrix hierarchy analysis, and interactive chart switching using bookmarks and bookmark navigator. Various DAX functions such as IF, ABS, POWER, and AVERAGE were implemented for categorization and statistical analysis.

The final report was published to Power BI Service and designed using synchronized slicers, customized layouts, matrix visuals, line charts, column charts, and interactive navigation features.

---

## Features

- Dynamic Transaction Filtering using Slicers
- Sync Slicers across Multiple Pages
- Interactive Bookmark Navigation
- Line & Column Chart Switching
- Power Query Data Profiling
- Conditional Formatting using Cell Elements
- Matrix Hierarchy Analysis
- DAX Based Calculated Columns
- Report Level Currency Filtering
- Power BI Service Publishing

---

## Tools & Technologies Used

- Power BI Desktop
- Power Query Editor
- DAX
- Excel Workbook
- Power BI Service
- Bookmark Navigator
- Sync Slicers
- Conditional Formatting

---

### Steps followed 

- Step 1 : UPI Transactions dataset was imported into Power BI using Excel Workbook as the data source.

- Step 2 : Column profiling based on the entire dataset was enabled using:
  
  (a) Column Quality
  
  (b) Column Distribution
  
  (c) Column Profile

to analyze distinct values, unique values, empty values, errors, and value distributions.

- Step 3 : Data types for all columns were validated to ensure proper data modeling and reporting accuracy.

- Step 4 : Transaction Time column was transformed using Split Column by Delimiter operation to separate date and time components.

- Step 5 : Customer Account Number and Merchant Account Number columns were converted from exponential format to text data type.

- Step 6 : Data validation and profiling operations were performed for:
  
  (a) Transaction Amount
  
  (b) Remaining Balance
  
  (c) Currency
  
  (d) Device Type
  
  (e) Merchant Name
  
  (f) Customer Age
  
  (g) Payment Method
  
  (h) Transaction Status

- Step 7 : A calculated column named "Age Groups" was created using Nested IF DAX function for customer segmentation.

- Step 8 : Multiple slicers were added for interactive filtering including:
  
  (a) Bank Name Sent
  
  (b) Bank Name Received
  
  (c) City
  
  (d) Device Type
  
  (e) Gender
  
  (f) Age Groups
  
  (g) Merchant Name
  
  (h) Payment Method
  
  (i) Purpose
  
  (j) Transaction Type

- Step 9 : Visual alignment, positioning calculations, sizing adjustments, and dashboard formatting operations were performed for consistent report design.

- Step 10 : Separate report pages were created for multi-page dashboard analysis.

- Step 11 : Line Chart visual was created to analyze transaction amount trends over time using Transaction Date hierarchy.

- Step 12 : Advanced chart formatting operations were performed including:
  
  (a) Smooth Interpolation
  
  (b) Data Labels
  
  (c) Marker Formatting
  
  (d) Gridline Customization
  
  (e) Axis Formatting
  
  (f) Border Styling
  
  (g) Title Formatting

- Step 13 : Report-level currency filter was implemented using Filters Pane for currency-wise transaction analysis.

- Step 14 : Matrix Visual was created to represent:
  
  (a) Transaction Amount
  
  (b) Remaining Balance

across:
  
  - Months
  
  - Cities
  
  - Currencies

- Step 15 : Hierarchical matrix structure was implemented using Month, City, and Currency hierarchy.

- Step 16 : Row subtotals and column subtotals were disabled for cleaner matrix representation.

- Step 17 : Conditional Formatting using Cell Elements was applied to dynamically represent transaction intensity using color gradients.

- Step 18 : Sync Slicers functionality was implemented to synchronize filters across multiple report pages.

- Step 19 : Bookmarks and Selection Pane were used to dynamically switch between:
  
  (a) Line Chart for Transaction Amount
  
  (b) Column Chart for Transaction Amount
  
  (c) Line Chart for Remaining Balance
  
  (d) Column Chart for Remaining Balance

- Step 20 : Bookmark Navigator was added to provide interactive chart switching directly within the report page.

- Step 21 : Additional DAX functions including IF, ABS, POWER, and AVERAGE were implemented for grouping and statistical calculations.

- Step 22 : Interactive filtering and cross-page analysis were tested using synchronized slicers and report-level filters.

- Step 23 : Final dashboard formatting and responsive visualization adjustments were completed.

- Step 24 : The report was published to Power BI Service.

---

# Snapshot of Dashboard (Power BI Desktop)

![Dashboard_1](ADD_IMAGE_LINK_HERE)

![Dashboard_2](ADD_IMAGE_LINK_HERE)

![Dashboard_3](ADD_IMAGE_LINK_HERE)

---

# Insights

### [1]

The dashboard enables dynamic transaction analysis using synchronized slicers and report-level filtering.

### [2]

Conditional formatting and matrix hierarchy visuals were used to identify high and low transaction intensity areas.

### [3]

Bookmarks and Bookmark Navigator provided interactive switching between multiple chart representations.

### [4]

Power Query profiling and DAX calculations helped improve data quality, segmentation, and analytical reporting.

### [5]

The project demonstrates end-to-end Power BI workflow including data cleaning, transformation, visualization, DAX calculations, interactive reporting, and Power BI Service deployment.
