# EXPBank
Versatile Bukkit server XP storage and sharing plugin.

To convert from one type of database to another follow these intructions:

First stop the server completely to ensure that the correct player levels are saved in the current database.

If you are currently using a YAML database (FlatFile):
- Going from YAML to SQLite:
	1. Make sure the database-type in the config file is set to "yaml"
	2. Start the server, whitelisting is preferred.
	3. From the console run the following command: /exp y2s
	4. Note in the console the messages that the new database has been setup and the data conversion is complete.
	5. Stop the server.
	6. Change the database-type to "sqlite" in the config file.
	
- Going from YAML to MySQL:
	1. Make sure the database-type in the config file is set to "yaml"
	2. Fill in the HOST, USER, PASS, NAME, and PORT fields for the MySQL in the config file, and save the file.
	3. Start the server, whitelisting is preferred.
	4. From the console run the following command: /exp y2m
	5. Note in the console the messages that the new database has been setup and the data conversion is complete.
	6. Stop the server.
	7. Change the database-type to "mysql" in the config file.


If you are currently using an SQLite database (Database file):
- Going from SQLite to YAML:
    1. Make sure the database-type in the config file is set to "sqlite"
	2. Start the server, whitelisting is preferred.
	3. From the console run the following command: /exp s2y
	4. Note in the console the messages that the new database has been setup and the data conversion is complete.
	5. Stop the server.
	6. Change the database-type to "yaml" in the config file.
	
- Going from SQLite to MySQL:
	1. Make sure the database-type in the config file is set to "yaml"
	2. Fill in the HOST, USER, PASS, NAME, and PORT fields for the MySQL in the config file, and save the file.
	3. Start the server, whitelisting is preferred.
	4. From the console run the following command: /exp s2m
	5. Note in the console the messages that the new database has been setup and the data conversion is complete.
	6. Stop the server.
	7. Change the database-type to "mysql" in the config file.


If you are currently using a MySQL database:
- Going from MySQL to YAML:
    1. Make sure the database-type in the config file is set to "mysql"
	2. Start the server, whitelisting is preferred.
	3. From the console run the following command: /exp m2y
	4. Note in the console the messages that the new database has been setup and the data conversion is complete.
	5. Stop the server.
	6. Change the database-type to "yaml" in the config file.

- Going from MySQL to SQLite:
	1. Make sure the database-type in the config file is set to "mysql"
	2. Start the server, whitelisting is preferred.
	3. From the console run the following command: /exp m2s
	4. Note in the console the messages that the new database has been setup and the data conversion is complete.
	5. Stop the server.
	6. Change the database-type to "sqlite" in the config file.
