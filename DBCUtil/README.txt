Run this program in a folder full of .DBCs to quickly convert them all to .dbc.csv files.
Drag & drop DBCs or CSVs onto the program and they will be converted into the opposite type.
To insert comments in CSV (e.g. for adding details on column headers and such) prefix a line with "##" (w/o quotes) and 
	when this file is converted to DBC the comments will be added onto the DBC (this does not affect normal dbc operation, the dbc readers
	will ignore this change)
	Do not add comments before the first line (the type line) or the program will not convert properly!
Execute DBCUtil -h for a list of options.
