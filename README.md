# CSC-4402-Library-Database
Code was developed and run on the classes server, these readme instructions will be tailored toward the classes server, but may also be generalized (Note that you will have to fix the location of the load infile statements in accordance to the location you have stored the files).

1. Create a directory in the classes server called GroupProject
2. Place each file in the GroupProject folder
3. run the createTables_sql file by putting mysql --local-infile -ucs4402xx -pzzzzzz cs4402xx <createTables_sql into the terminal where zzzzzz is 6-digit sql server password, and XX is the student id you were given. Only run createTables once.
4. run the queries by inputting mysql --local-infile -ucs4402xx -pzzzzzz cs4402xx <queries_sql using the same rules as above.
