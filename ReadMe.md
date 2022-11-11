ASP.NET Core 6.0 Web API (MVC) Demo

This is a project that demonstrates CRUD Operations (Create, Read, Update and Delete) 
with ASP.NET Core 6.0 Web API (MVC) using Entity Framework Core and InMemoryDatabase. 

This web app is developed in Visual Studio 2022.

This application includes the usages of followings:

        <li>ASP.NET Core 6.0 Web API (C#)</li>
        <li>Define EF Core Model</li>
        <li>Dependency Injection</li>
        <li>DB Connection String / Configuration</li>
        <li>Database Migration / Update</li>
        <li>Scaffolding Controllers/Views</li>
        <li>Layout Page</li>        
        <li>CRUD Operations (Create, Read, Update and Delte Records)</li>
    
Note. InMemoryDatabase can be replaced with other databases such as SqlServer, SQLite or MongoDB.</p>

How to call API

1. Swagger

This API comes with Swagger client.
Run the API to open browser.
Add /swagger at the end of the URL. 
e.g. https://localhost:7126/swagger

2. Postman 

Open Postman and run the URLs
Get (all items) https://localhost:7126/api/TodoItems
Get (Selected item) https://localhost:7126/api/TodoItems/2
