# text_compare
Oracle APEX plugin for comparing text in a report Columns, based on [htmldiff-js](https://github.com/tnwinc/htmldiff.js/tree/master)

To use this plugin:
1. Create an interactive Report
2. Be sure in the report you have 3 columns holding the 3 parameters needed:
<br> a. Base text: The initial or Original text
<br> b. New text: The modified text you want to compare with the original
<br> c. Unique Identifier: A unique string to identify the row where the text is stored.
4. Select the column holding the "New text"
5. Under the columns properties, Section "Settings", Select the corresponding columns to use in each parameter.
