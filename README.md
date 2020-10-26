Problem statement is defined in the file "Bungee Coding Round.docx". Please refer to this file. 

In SQlite to select USA country contain rows SELECT * FROM main WHERE c9 LIKE 'USA%';

Saved this file names ad 'filteredCountry.csv'

TO Select MIN price of each SKU SELECT SKU, MIN(PRICE) as FIRST_MIN_PRICE FROM filteredCountry

GROUP BY SKU; Saved result file named as 'lowestPrice.csv'
