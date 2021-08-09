# Module 4: Cleaning Data

## Removing Duplicated or Inaccurate Data and Empty Rows

​	It’s very common when collecting or importing data - whether through manual or automated

​	processes - to get errors and inconsistencies in your data

​		Things like:

​				-Spelling Errors

​				-Extra white space

​				-Incorrect use of case used

​		In Text:

​				-Empty Rows

​				-Missing Values

​				-Inaccurate or duplicated data

### This requires working with some form of data-cleaning

​	Start off with **"Spell Checker"** (works the same way is in Microsoft word)

​		**Select the Column/Row** of data you wish to check, **click 'spelling'** on **'the review tab'**

​	Next Inconsistency-Look for this in empty rows

​		Empty row can cause a lot of issues working with formulas, sorting and filtering 

​			-Important to remove them from the data.

​				-clicking **CTRL+DOWN ARROW**, it should take us to the end of that column of data, but notice if we do that in this dataset, the cursor keeps stopping when it gets to an empty row meaning that the dataset if essentially being split into multiple sections, separated by these empty rows.

### 	To resolve the issue: Empty Columns, Rows and Cells

It involves selecting all our data first, either using the mouse, or the **CTRL+SHIFT+END** keyboard shortcut.

Then we select the **Filter icon** on the **Data tab**.

We can now see that each column has a **filter icon** next to the column header.

If we then select the Customer Name column-filter in column M

then uncheck **Select All**

then scroll down to the bottom of the list, we can check the item called **'Blanks**', and 

then click **OK**.

**(This will now show only the empty rows)** 

Select the rows by using the **mouse** or **CTRL+SHIFT+END** shortcut the delete the empty rows

### Duplicated Data Rows:

​	Two ways to handle:

​		1)The first way includes reviewing the data you plan to remove first, before deleting it, to 			ensure you are deleting the right data.

​				So, we select the column…and choose **Conditional Formatting**, then Highlight **Cells 				Rules**, and then **Duplicate Values**.

​				When we click **OK**, and scroll down the sheet, we can see that only a few values have     				been identified as being duplicates.

​		2) The second method is simpler as you don't review the data before removing it but lacks 		security. ***(It's important to select a column of data that you would NOT expect to have a 		   		duplicate)***

​			Select the whole datasheet and on the 'Data tab' use the 'Remove Duplicates' button

​				-Then unselect all the columns, then select only the columns that are duplicated (then 				duplicate rows are deleted)

​	'**Find and Replace'** tools are under the **'Home tab'** in excel

# Dealing with Inconsistencies in Data

***Changing Case of Text file**

​	Using **'UPPER, LOWER AND PROPER** functions'

​		Insert "Helper row" , type function = (cell reference)

​			Use mouse or **SHIFT+RIGHT ARROW** to select the columns across to desired location

​				then press **F2** to bring the cursor into focus, then hold down **CRTL** key while press **ENTER**

​		Finish by copying the 'Helper Row' and use **'paste values'** option, then remove 'Helper row'

Use the same method for insert 'Helper Column' and use UPPER, LOWER OR PROPER to fix

​	You can then fill the rest of the column by *double-clicking the **FILL HANDLE** cross symbol*

​		(repeat previous steps to remove helper column)

***Fixing Data formatting errors (no new information)**

Select all the data **(CTRL + A)** from first cell, then on **'Home'** tab click '**Find and Select'**, then  		      	**'Replace'**

​		(getting rid of white spaces) in find, type 2 empty spaces, replace type 1 empty space

​			Then click, **Find Next**, and choose **Replace** for each item with white space ********(alternately 			you can click replace all if you are sure about all of the data)*****

***Trimming Whitespace from data**

​	Insert helper Column/Row, type = TRIM, (cell referenced)

​		Double-click the FILL Handle symbol to copy formula as before

​			Then copy contents as before

## More Data Cleaning Features

**Flash Fill as a data cleaning tool**

​	**Combining or separating names**(Using **'FLASH FILL'**)

​		Insert Helper column (Title the column), enter the information in the format of your choice

​			After pressing ENTER, start typing the information from the next cell and you'll see FLASH 			FILL will start filling the information in the way you formatted

​				Remove remaining columns if you no longer need them

​	Separating names into tow columns (Using '**Text to Columns**')

​		Insert new columns, type column headers, 

​			Click on **'DATA tab'** and then click **'Text to Columns**' (make sure to choose 							      			**'Delimited'**)****(on the second page make sure **'Space'** is selected as delimited) , next on 			the third page click the little arrow next to **'Destination'** and select the cell on the 		             			worksheet, then click the little arrow again to return to the worksheet and hit 			     			**'Finished'**

![image-20210717170440455](C:\Users\Christopher\AppData\Roaming\Typora\typora-user-images\image-20210717170440455.png)

Using Formulas ( This formula with extract the length of characters from cell A2 from the right)

Can fill remaining cell using the same formula by double-clicking the Fill Handle in the cell you just completed 

## Issues with Data Quality 