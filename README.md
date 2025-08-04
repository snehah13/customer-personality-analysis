# customer-personality-analysis

#Data Cleaning Steps (Using Excel)

1. Open the customer.csv file in Excel using get data
   - Original file had all data in a single column due to tab delimiters.

using power query window
2. Split Data into Columns:
   - Select Column A → Go to Data tab → Click 'Text to Columns'.
   - Choose 'Delimited' → Select 'Tab' → Click 'Finish'.

3. Correct Data Types:
   - Year_Birth: Format as Number.
   - Income: Format as Currency.
   - Dt_Customer: Format as Date (DD-MM-YYYY).
   - Binary column Response:  format as Yes/No.

4. Remove Null Values:
   - Use filters to find blanks in Income or Education.
   - Delete rows with missing values or fill with default values.

5. Standardize Column Headers:
   - Rename headers for clarity (e.g., MntWines → AmountSpent_Wine).
   - used first row as header and removed some unwanted columns.

6. Save Cleaned File:
   - File → Save As → Excel Workbook (.xlsx).
   - Name the file 'customer_personality_cleaned.xlsx'.

7. Optional Summary Sheet:
   - Use formulas: AVERAGE, COUNTA, COUNTBLANK, UNIQUE, etc.
