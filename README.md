# Netflix-Movies-and-TV-Shows
Source: 

Firstly, obtained the sample dataset from the Kaggle i.e. Netflix Movies and TV Shows csv file.

Tools:  

Downloaded the free anaconda navigtor and from that the jupyter notebook python (Pandas).

Work Flow :

1.Detected the missing values using .isnull() and .sum() functions and filled the missing values with fillna() function to unknown.
2.Used drop_duplicates() function to eliminate any duplicates.
3.(As Gender is not present in this dataset) I have standardized the Country names column and other text columns using .str.strip().str.title() functions.
4.Converted the date_added column to datetime in dd-mm-yyyy format.
5.Standardized the headers in lowercase and replaced the spaces between them with underscores.
6.Fixed the data types like release_year to int and date_added to datetime as other columns.

Deliverables:

1.Downloaded the cleaned dataset from the current working directory of Jupyter notebook.
2.Next used the alt+A+E function to saggregate the data set into a perfect excel sheet.
