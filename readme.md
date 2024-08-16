1. Download the source code from zip file
2 .Create a MySQL database with Database name "vpms". 
This Empty database must be created for successfully running this project.
3. Edit the connection string settings in the DataBaseOperation.py and set the database name as "vpms", user id to your "mysql login id" and password to your "mysql password" to successfully connect to the database. 
4. Use python version 2.* or more. Install the python packages PyQt5 and mysql-connector-python
5. Run the MainProgram.py
6. If the Database is empty, InstallWindow.py will be shown (one time) where the database details needs to be configured. In this screen, the Admin username and password needs to be set for VPMS application login. 
7. config.json file will be created in the project folder if the database is correctly configured. Then LoginWindow.py will be shown where the user can login with he Admin username and password set for VPMS application. 