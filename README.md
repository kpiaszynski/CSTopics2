# CSTopics2
## Homework 2
### Katie Piaszynski

## 1) HTML set-up for table of US Population Data (plus small bit of CSS)
This initializes the HTML set-up. It is given in VSCode by entering "html:5" in an html file. The title of the website is set to "US Population."
![image](https://github.com/user-attachments/assets/31c36805-193c-4b38-af58-95ce7617de85)

This small amount of CSS styling is simply to add boxes to the table at a specific width-without the typical double border, along with centered headers.

![image](https://github.com/user-attachments/assets/2b586db6-e461-4bc2-bb36-b697af746140)

This sets up the centered column names and widths, with "US Population" spanning the two total columns of "Year" and "Population." The table's body id is named "popTable" for reference by JavaScript later.
![image](https://github.com/user-attachments/assets/f0ac1c13-21af-4da1-9d02-14b622026c81)

## 2) JavaScript set-up for parsing data and adding to HTML table
The beginning function simply grabs the data to be used.
The second function is where this data gets parsed and input into their respective columns and added to the table described above. This function is wrapped in an IIFE to load this population data as soon as possible (whenever the site is loaded :) ).
![image](https://github.com/user-attachments/assets/f42dbeb6-0655-4784-b88b-81b1c5a2c7cf)


