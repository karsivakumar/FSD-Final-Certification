# fsd-final-certification
FSD final certification

webhook test

### Executing the Application

- Without Docker
	
Open command prompt prompt window and run following  on ./taskmanagerfrontend
	
	-- NPM Install
	ng serve --proxy-config proxy.conf.json
	
	make sure FrontEnd is running on port 4200:80
	
Open new command prompt window and run following  on MongoDB Folder

	mongod
	
	make sure mongodb is running on port 27017
	
Open new command prompt window and run following  on ./taskmanagerbackend
	
	-- NPM Install
	node index.js
	
	make sure back end is running on port 3000 and MongoDB connection is successful
	
- With Docker
    Please run the below command to execute with docker 
    ```
    docker-compose up --build 
    ```

### Github link: 
- https://github.com/karsivakumar/FSD-Final-Certification.git
