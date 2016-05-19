# databaseAssignment
A repository for the database assignment


SELECT * FROM Users WHERE id = 5;
	
	This command will query the Users table and 
	return the data in the row with id equal to 5


SELECT COUNT(id) FROM Users WHERE Sex = "MALE";

	This command will query the Users table and
	return number(quantity) of male users in the the
	table


DELETE * FROM Size WHERE Chest = 25 LIMIT 1;

	This command will query the Size table and return
	and delete the first row where chest is equal to 25



DROP TABLE Size;
	
	This will delete the Size table.


TRUNCATE TABLE Label_Design;

	This will empty all the data in the table.