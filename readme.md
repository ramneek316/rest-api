-----------------**\*\***\*\*\*\***\*\***--------------------
**_CREATE a .env file_**
#add the required credentials with the reference of example.env
**_Install the Appp_** ###**Command to install the app npm install**
**\_COMMAND TO RUN APP: npm start**
######REST API with PAGING, SEARCHING, SORTING#####
--------------------------x--------------------------
**Filter with Page and limit METHOD GET**
e.g; http://localhost:5001/api/users?page=1&limit=4  
--------------------------x--------------------------
**search with username || name || hobby METHOD GET**
eg; http://localhost:5001/api?username=sanjit&name=sanjit&hobby=dancing
--------------------------x--------------------------
**Sort in ascending || descending order METHOD GET**
e.g; http://localhost:5001/api/users/ascending
--------------------------x--------------------------
**GET ALL USERS METHOD GET**
endpoint: http://localhost:5001/api/users
--------------------------x--------------------------
**REGISTER NEW USER METHOD POST**
endpoint: http://localhost:5001/api/post
--------------------------x---------------------------
**DELETE USER BY ID METHOD DELETE**
endpoint: http://localhost:5001/delete/id
--------------------------x----------------------------
**UPDATE USER BY ID METHOD PATCH**
endpoint: http://localhost:5001/update/id
--------------------------x-----------------------------
**GET USER BY ID METHOD GET**
endpoint: http://localhost:5001/api/getById
--------------------------x-----------------------------
**_Swagger UI_**
http://localhost:5001/api-docs
