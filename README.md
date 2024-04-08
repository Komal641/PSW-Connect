To get the application up and running as quickly as possible in the simplest configuration, following are the configurations:

1.	System requirements:
•	Hardware requirements (Minimum Requirement)
CPU: Intel Core i5, Ryzen 5, Apple M1 (any of these)
Ram: 8gb (recommended for smooth operations)
•	OS requirement:
Windows 10 or later
Linux (Ubuntu 18.4 or later)
Mac

2.	Prerequisites: (pre required software/dependencies)
•	Node Js
•	MongoDB
•	MongoDB Compass (DB Editor)
•	VS Code Editor

3.	Installation instruction (Backend & DB)
•	DB Setup:
i.	Download & Install Mongo Db. (https://www.mongodb.com/try/download/community )
ii.	Download & Install MongoDB Compass (https://www.mongodb.com/products/tools/compass )
iii.	Mongo Db Configuration for Mac users: Follow below video instructions.
(https://www.youtube.com/watch?v=8gUQL2zlpvI )
After configuration, start Mongo Db Compass.

•	Code Setup: 
i.	Download & Install VS code (https://code.visualstudio.com/download )

ii.	Download & Install Node Js (https://nodejs.org/en/download )
iii.	Get code from : https://github.com/Komal641/PSW-Connect/tree/master
iv.	Open the downloaded code in vs code or else use git clone command in the terminal of VS code to get code.
“git clone https://github.com/Komal641/PSW-Connect.git .”
v.	After this, run “npm install” command to install all dependencies mentioned in package.json
vi.	After this, run “node index” command to start the application.


Note: once the server is started it will automatically start the application at: http://localhost:3000/



Database Creation: 

To create the application database on a server computer that already has Mongo DB installed – 
1.	Connect to MongoDB: Start by connecting to the MongoDB server on the server computer. You can use the MongoDB shell or server computer terminal.
2.  In the terminal follow the steps:
•	Got to the folder where Mongo Db is installed and downloaded.
•	Open bin folder
•	Under bin, open Unix Executable File – “mongod” in terminal, this will run the file and execute the “mongod” to system.

The terminal would execute the Unix Executable File
3.  Open the bin folder in Terminal and enter the following command:
./mongod --dbpath /Users/macbookpro/Documents/db
Where: ./mongod –dbpath -  is the syntax to set the db path and /Users/macbookpro/Documents/db – is the path where Mongo DB is installed in the system.
This command would make the Mongo Db connection to the host server
4.	Connect the DB Compass
Under Host: Enter hostname, change the URL from local host to new Host name and click Connect (below)

Now the database connection is set up, the database creation and database collection creation are being executed through code. When the code is executed, the node would create the database as well as the collections respectively. That would be accessible under “Databases.”

