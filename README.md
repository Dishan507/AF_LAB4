# AF_LAB3
There are ten questions with their answers related to basic concepts in MongoDB

1. Start MongoDB instance locally by issuing the following command inside the bin folder inside MongoDB installation directory.

2. Check MongoDB is working by connecting to the local instance using an IDE. Default port for MongoDB is 27017. 

3. Add the following document to the database sliit;     
{       
"name": "John",       
"dateOfBirth": "1990-01-01T00:00:00Z",       
"subjects": [ "Application frameworks", "Computer architecture" ] 
} 

● We always make sure to add dates in MongoDB as a UTC date since MongoDB by default deals with UTC timezone and format.

4. Find the document by ‘name’. 
 
5. Find the document by ’_id’.

6. Add ‘Distributed Computing’ to the subject list. 
 
7. Add the following 2 document to the same collection; 
 {      
 "name": "Smith",      
 "dateOfBirth": "1990-01-15T00:00:00Z",       
 "subjects": ["Application frameworks", "Computer architecture"],       
 "isActive": true } 
 
{      
"name": "Smith",      
"dateOfBirth": "1990-01-15T00:00:00Z",      
"subjects": ["Application frameworks", "Computer architecture"],      
"isActive": false 
} 
 
8. Find the document with the name ‘Smith’ and isActive flag is true and add Distributed computing to subjects.   
 
9. Update the first document ‘isActive’ to false.   
 
10. Remove the first document created.
