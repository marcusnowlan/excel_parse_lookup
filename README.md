# excel_parse_lookup
# This is a project in which data from the Excel file agenda.xls (given) is parsed, with the data put into a
# a SQLite database structure (via ./import_agenda.py agenda.xls in the command line). Then, lookup_agenda.py
# can be used to print data from the SQLite database with a specified column and value 
# (via ./lookup_agenda.py column value in the commmand line, where column is one of {date, time_start, 
# time_end, title, location, description, speaker}, and value is the expected value for that field). The file
# db_table.py was given as a basic SQLite wrapper and contains useful functions to interact with the SQLite
# database.
# 
# In this project, agenda.xls was given as a sample Excel file to be parsed, and db_table.py was given as
# the basic SQLite wrapper to make interacting with the SQLite database easier. Both import_agenda.py and
# lookup_agenda.py were created as part of the project, to make a SQLite database from the Excel data and 
# to make an easy mechanism for returning data from the Excel file (with specified column and value fields).
