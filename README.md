# data-sourcing-challenge
***
## Description
This is a program for accessing and manipulating data of Coronal Mass Ejection (CME) and Geomagnetic Storm (GST) from NASA's APIs from the Space Weather Database Of Notifications, Knowledge, Information (DONKI) over the span of 2013-05-01 to 2024-05-01 (YYYY-MM-DD).

## Project Status
The code is at a stable state. May revise the code in order to improve understanding of working with APIs and manipulating more data.

## Conditions
The specifications for this program is that it is running on Python 3.10.14 for a Conda environment, kernel, used an API key to access NASAs GST and CME files, and imported requests, time, load_dotenv from dotenv, os, pandas, json, and datetime.

## Authors and Acknowledgement
Author: AndHol996
I would like to acknowledge my teacher, N. Sanka, and TA, V. Reddy for assistance during examples in class.

## Code Sourcing and Influences
The code was influenced by the OSU AI Bootcamp lessons. Code took influence from "Adding a New Column to a Pandas DataFrame using List" in "Adding new column to existing DataFrame in Pandas" by Chaitanya Tyagi on geeksforgeeks.org for Code Cell 10, Line 7 of retrieve_data.jpynb, from "Method 1: Drop Rows with Missing Values in One Specific Column" in "Pandas: How to Use dropna() with Specific Columns" by Zach Bobbitt from statology.org for Cell 11, Line 6 of retrieve_data.jpynb, and from "Method 1 : Using contains()" in "Select rows that contain specific text using Pandas" by deveshkumarsharma from geeksforgeeks.org for Code Cell 14, Line 7 of retrieve_data.jpynb.

## References

*Adding a New Column to a Pandas DataFrame using List*  from *Adding new column to existing DataFrame in Pandas* by Chaitanya Tyagi from geeksforgeeks.org, accessed on 9/28/24. [Adding new column to existing DataFrame in Pandas](https://www.geeksforgeeks.org/adding-new-column-to-existing-dataframe-in-pandas/#add-a-new-column-to-an-existing-pandas-dataframe-using-dataframeloc) 

*Method 1: Drop Rows with Missing Values in One Specific Column* from *Pandas: How to Use dropna() with Specific Columns* by Zach Bobbitt from website, accessed on 9/28/24. [Pandas: How to Use dropna() with Specific Columns](https://www.statology.org/pandas-dropna-specific-column/)

*Method 1 : Using contains()* from *Select rows that contain specific text using Pandas* by deveshkumarsharma
from geeksforgeeks.org, accessed on 9/28/24. [Select rows that contain specific text using Pandas](https://www.geeksforgeeks.org/select-rows-that-contain-specific-text-using-pandas/) Cell 14 Line 7
