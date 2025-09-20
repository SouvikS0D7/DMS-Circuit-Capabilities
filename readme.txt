S0D7
_______________________________
Comparing tool for Excel - based on the DMS_Circuit_Capabilities structure
_______________________________
1. Extract the current Database table and save it as extract.xlsx in the same folder (file to compare with)
2. Get the updated excel sheet and save it as standard.xlsx in the same folder	(going to be the base file)
3. Run source.py
_______________________________
Two files are created:
1. output.txt :
	Provides a base statistic for the dissimilarities
	Provides an SQL-query that can be copied and pasted to SQL Developer
2. result.xlsx :
	This has three sheets -
	i>	Comparison	the comparison with color coding
				colors :-
					a. Colorless	: These cells were similar
					b. Yellow	: Extract has it but Standard does not
					c. Blue		: Standard has it but Extract does not 
				this bears the Standard file as the base file and highlights differences
	ii>	Extract		the original Extract
	iii>	Standard	the original Standard file
_______________________________
A sample is provided in the excel sheets. PLEASE adhere to the convention
No need to put headers in the excel sheet that you upload
Please provide the name and the four columns ONLY
Make sure your data is on the FIRST sheet of the workbook
	