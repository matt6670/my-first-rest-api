# my-first-rest-api

Followed the Relational database style with three different tables to hold the data - SQL 

1. Person table that holds - name ( varchar (50)) , age (int) , and no of people (int)
2. House table that holds - houseId, OwnerId and addressID
3. Address table holds - addressID , postcode(varchar(7)), street address(varchar(100))

-

------ API call to display the house owner Details -------------------------

GET  : https://localhost:3000/:houseID  - Read the data from the database 
PUT   : no update or replace of the data 
POST   : no post of the data 
DELETE  : DELETE 

------ API call to display the household based on the specific age and the no of occupants  ----------------

GET  : https://localhost:3000/:age/:noofpeople
PUT
POST
DELETE   :delete
