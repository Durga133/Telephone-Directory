# Telephone-Directory
Telephone Directory using CRUD Operation
Telephone directory: Performing CRUD operation using mongodb and python.
Import necessary modules
Performed CRUD operations to manipulate data in MongoDB. Create, retrieve, update, and delete (CRUD)
Created a database using attribute style on a MongoClient instance. Declare a variable db and assigned the new database as an attribute of the client.
Created a collection.
For performing CRUD operation, created a directory which has fields like Name, Phone number, Pincode
Inserted the record into the collection.
Make a query to find records you just created.
Modified the records, use the update_one() method. The update_one() method requires two arguments, query and update.
Deleted the record, use delete_one() method. delete_one() requires a query parameter which specifies the document to delete.
