This is sample for implementing MongoDB with .net core webapi.

Steps:
1.Install MongoDB in OS(Window 10).
2.Install MongoDB Compass which is used to have GUI view of DB.
3.Create .net core web api.

---------Test Data-------------
1.Message body in JSON formart below:
{
  "BookName" : "Clean Code",
  "Price" : 43.15,
  "Category" : "Computers",
  "Author" : "Robert C. Martin"
}
2.Use Postman to fire a POST request to insert above record to MongoDB.
