# Module 5: Data Analysis Basics, Filtering and Sorting Data

## Filtering

​	On the **'Data tab'** select **'Filter'** (if you only want to filter certain columns select those columns 	first before selecting the filter option)

​	To clear filter either select the 'clear filter' or hit the select all button on the filter

​	To narrow down further you may select may filter options at one time to narrow select (number 	of records displayed will be shown below)

![image-20210717194031765](C:\Users\Christopher\AppData\Roaming\Typora\typora-user-images\image-20210717194031765.png)

You can also see the missing rows on the side bar that are not visible 

![image-20210717194324791](C:\Users\Christopher\AppData\Roaming\Typora\typora-user-images\image-20210717194324791.png)



​		To clear ALL filters use the **clear** button in the sort and filter group on the **data** **tab**

### Custom Filters

![image-20210717193932408](C:\Users\Christopher\AppData\Roaming\Typora\typora-user-images\image-20210717193932408.png)

### Text Filters

![image-20210717194611212](C:\Users\Christopher\AppData\Roaming\Typora\typora-user-images\image-20210717194611212.png)

## Sorting:

​	Sorting by single column select the single data point in the column and sorting function either 	ascending or descending 

​	To sort using multiple  Simply select a cell in your data then on the data tab click "sort," then   	    	either use the sort-by column suggested or use the drop-down list to select a different				      	column. 

<img src="C:\Users\Christopher\AppData\Roaming\Typora\typora-user-images\image-20210717195552424.png" alt="image-20210717195552424"  />

To add column to sort by click 'Add Level'

If you have headers in your data be sure to select "my data has headers" check box

## Useful Functions

### "IF" Function

Yes or no example (A Boolean is a data type with only two possible values)

![image-20210717200659834](C:\Users\Christopher\AppData\Roaming\Typora\typora-user-images\image-20210717200659834.png)

Over/Under example

![image-20210717201250139](C:\Users\Christopher\AppData\Roaming\Typora\typora-user-images\image-20210717201250139.png)

Nested Functions for two or more conditions

![image-20210717201426686](C:\Users\Christopher\AppData\Roaming\Typora\typora-user-images\image-20210717201426686.png)



Excel can support up to 64 "if" conditions but it's not recommended. To make this easier IFS  was developed.

The IFS function is only supported on Excel 2019, Excel for Microsoft 365, and Excel for the web.

![image-20210717202127578](C:\Users\Christopher\AppData\Roaming\Typora\typora-user-images\image-20210717202127578.png)

Notice using "IFS" function only one set of parentheses is needed

***With 'Conditional Formatting Example' (Retention of value as a %)***

![image-20210717202519891](C:\Users\Christopher\AppData\Roaming\Typora\typora-user-images\image-20210717202519891.png)

To Highlight more: On the 'Home tab' click Conditional Formatting and make a new rule.

![image-20210717202953327](C:\Users\Christopher\AppData\Roaming\Typora\typora-user-images\image-20210717202953327.png)

Then hit format and select your formatting:

![image-20210717203116111](C:\Users\Christopher\AppData\Roaming\Typora\typora-user-images\image-20210717203116111.png)

Next you will select 'manage rules' because you're adding a rule to your existing rule

![image-20210717203537443](C:\Users\Christopher\AppData\Roaming\Typora\typora-user-images\image-20210717203537443.png)

## COUNTIF Function

![image-20210717203809480](C:\Users\Christopher\AppData\Roaming\Typora\typora-user-images\image-20210717203809480.png)

## COUNTIFS Function

This removes the need to use multiple COUNTIF functions in a long and complex single formula.

## SUMIF Function

You use the SUMIF function to sum the values within a specified range that meet specified criteria.

​	For example, you might want to add up only the salaries that are over a specified salary

![image-20210717204356891](C:\Users\Christopher\AppData\Roaming\Typora\typora-user-images\image-20210717204356891.png)

Again, notice that because we have used an arithmetic operator, that is the ‘greater than’ operator, we must enclose the criterion in quotes.

If we specify a criterion that is only a number, we don’t enclose it in quotes.

You can also use wildcards such as ‘question mark’ (?) and ‘asterisk’ (*) when searching for partial matches, and you can also specify to extract values from a different column than the column where you have specified the criteria.

![image-20210717204937726](C:\Users\Christopher\AppData\Roaming\Typora\typora-user-images\image-20210717204937726.png)

## Using VLOOKUP AND HLOOKUP Functions

## VLOOKUP:

The most commonly used reference-type functions In Excel to find referenced data in a lookup table

Stand for **"Vertical Lookup"** useful went you want to find something in a range by row (a typical VLOOKUP would look like): =VLOOKUP(B3,AR:B12,2FALSE)

![image-20210717205847417](C:\Users\Christopher\AppData\Roaming\Typora\typora-user-images\image-20210717205847417.png)

The first thing we need to do, is put the column containing the value we want to search for, in the leftmost column, as VLOOKUP requires this. Then we can delete the original column.

If you don't specify True of False it will default to False (optional you may use 0 for false or 1 for true in the statement)

![image-20210717210053672](C:\Users\Christopher\AppData\Roaming\Typora\typora-user-images\image-20210717210053672.png)



In order to change the reference type to absolute from relative as is the default you can do it manually or put your cursor in each cell reference and in turn in the formula press **F4** to automatically add **$** signs

![image-20210717210724799](C:\Users\Christopher\AppData\Roaming\Typora\typora-user-images\image-20210717210724799.png)



To copy to the rest of the cells you need to change the absolute value in the row parameter by removing the $ symbol (change $V$5 to $V5, in this example)

![image-20210717211052124](C:\Users\Christopher\AppData\Roaming\Typora\typora-user-images\image-20210717211052124.png)



## HLOOKUP

## Looks for data in columns, rather than rows.

HLOOKUP looks for a word or value in the top row of a table, and then returns a value in the same column from a row specified in the table array.

![image-20210717211455308](C:\Users\Christopher\AppData\Roaming\Typora\typora-user-images\image-20210717211455308.png)

![image-20210717211646899](C:\Users\Christopher\AppData\Roaming\Typora\typora-user-images\image-20210717211646899.png)



## XLOOKUP

![image-20210717211938415](C:\Users\Christopher\AppData\Roaming\Typora\typora-user-images\image-20210717211938415.png)

