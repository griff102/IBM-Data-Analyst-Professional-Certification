# Analyzing Data with Excel: Final Assignment

## Part I

### Tasks to perform:

1. **Save the CSV file as an XLSX file:** Click the 'Edit Workbook' button in the ToolTip to save the file as an XLSX file. The file is converted when you select 'OK' in the prompt.

2. **Column widths:** Adjust the widths of all columns so that the data is clearly visible in all cells.

   **Change the column width to automatically fit the contents (AutoFit)**

   1. Select the column or columns that you want to change.
   2. On the Home tab, in the Cells group, click Format.
   3. Under Cell Size, click AutoFit Column Width.

3. **Empty rows:** Use the Filter feature to look for blanks and remove all empty rows from the data.

   **Delete Blank Rows**

   1. On the Home tab, in the Editing group, click Find & Select.
   2. Click Go To Special.
   3. Select Blanks and click OK. Excel selects the blank cells.
   4. On the Home tab, in the Cells group, click Delete.
   5. Click Delete Sheet Rows. Result:

4. **Duplicate records:** Use either the Conditional Formatting or Remove Duplicates feature to look for and remove any duplicated records from the data based on the contents of Column A.

   ***\*Remove duplicate\** values**

   1. Select the range of cells that has **duplicate** values you want to **remove**. Tip: **Remove** any outlines or subtotals from your data before trying to **remove duplicates**.
   2. Click Data > **Remove Duplicates**, and then Under Columns, check or uncheck the columns where you want to **remove** the **duplicates**. ...
   3. Click OK.

5. **Sorting:** Sort the data in Column A from smallest to largest.

   ​	Use the filter function at the top of the column to select smallest to largest

6. **Format Cells:** In column C, set the type as Number and format it to remove the decimals. In column E, set the type as Number and format it to show up to two decimals.

   ​	1.Select the column

   ​	2.Then select number format from the drop-down on the home page

   ​	3.Select increase decimals button on the home page (or decrease) 

7. **Whitespace:** Use the Find and Replace feature to remove all double-spaces from the data.

   If you want to **remove** all whitespaces, select the cell or whole document,  Find and Replace dialog, type two spaces in the Find what text box, and one space in Replace with text box. Click Replace, and then the extra **spaces** in the cell or document have been removed

8. **Contact Name:** The contact name is divided into two columns as CONTACTLASTNAME (Column W) and CONTACTFIRSTNAME (Column X). Use Flash Fill to reduce the names to just one column, and then remove any unnecessary columns. Show the column values as FirstName LastName.

   1.  Create an empty column next to the columns you want to combine

   2.  Type the new header for the column
   3. Type the information from the first cell (space) and the information from the second cell,
   4. Use the flash fill button under the data tab to auto fill the rest of the document

9. **Save your workbook:** Use 'Save As' to save your completed workbook as **sales_data_sample_PART1.XLSX**.

   https://1drv.ms/x/s!AmjhrBiT5e5xg6QBJv7JdC5bCu86kA?e=skzJe8

   ## Part II

   ### Tasks to perform:

   1. **Format the data as a table:** Use the Insert, Table command to format the data as a table.

      *Under home tab, click format as table icon, select a table format

   2. Use AutoSum to calculate values:

       

      Use AutoSum to find the following values for column 'E' and record each of the values:

      - SUM
      - AVERAGE
      - MIN
      - MAX
      - COUNT

      *Make space at the bottom of the table, Place each title next to another in a row besides and use the AutoSum feature under the home tab to create each formula (make sure that the correct cells are highlighted manually or by dragging your cursor)

   3. **Create a Pivot Table:** Use the PivotTable feature to create a pivot table that displays the PRODUCTLINE field in the Rows section, and the QUANTITYORDERED in the Values section, so that the pivot table displays the total quantity count by product.

      *Use the CTRL + A to select the entire table, then select pivot table under the insert tab. Use the menu to select the fields you wish to include.

   4. **Sort the pivot table data:** Use the Sort By Value setting on the pivot table to sort it in descending order by the sum of total quantity count.

      *Sort using the sort feature on top of the header

   5. **Make two more pivot tables that are the same as the one your created in task 3:** Follow the same steps you performed in Tasks 3 and 4 to create two more identical pivot tables so that you end up with 3 worksheets that contain identical pivot tables.

      *Repeat steps

   6. Analyze data in the pivot table:

       

      Use the PivotTable Fields pane to manipulate and analyze data in the two copied pivot table as follows:

      - In pivot table 2, add the STATUS field below the PRODUCTLINE field so that the status of order shows up with their respective counts.
      - Collapse all fields except the top one – **Classic Cars**.
      - In pivot table 3, add the STATUS field above the PRODUCTLINE field so that the different status appears first, with the different product listed underneath each status with their respective counts.
      - Collapse all fields except the top one – **Cancelled**.

   7. **Save your workbook:** Use 'Save As' to save your workbook as **sales_data_sample_PART_2.XLSX**.

https://1drv.ms/x/s!AmjhrBiT5e5xg6QG0r1ItVGbdgqQWg?e=NIuyQM