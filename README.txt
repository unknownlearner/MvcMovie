

 First, I created a new project using the MVC template.
 Next, I added a Movie class to the Models folder, which defined the properties of the movie data.
 Then, I added a MvcMovieContext class to the Data folder, which represented the database context for accessing the movie data.
 After that, I registered the context as a service in Program.cs, which enabled dependency injection of the context into the controllers.
 Furthermore, I added a connection string to the appsettings.json file, which specified the database provider and the name of the database.
 Moreover, I used the scaffolding tool to generate CRUD pages for the movie model, which created a Movies controller and corresponding views.
 Finally, I used the EF Core migrations feature to create the database from the model, and ran the app to test the movie pages.



First, I created a database context class that inherited from DbContext and defined a DbSet property for each entity type.
This class handled the connection and mapping of Movie objects to database records. 
Next, I registered the database context with the dependency injection system in the Program.cs file, and specified the connection string and database provider. 
For local development, I used SQL Server LocalDB, which was a lightweight version of SQL Server Express. Then,
I populated the database with some initial data by creating a SeedData class with a static method that checked if the database was empty and added some sample records.
I called this method from the Program.cs file before running the application. 
Finally, I viewed the database using the SQL Server Object Explorer in Visual Studio, which allowed me to browse the tables and query the data.


I learned how to use ASP.NET Core MVC to create a web application that managed a database of movies. 
I used scaffolding to generate code for the movie model, database context, and controller actions. 
I also learned how to use Tag Helpers to simplify the HTML markup and enable server-side code to participate in creating and rendering HTML elements.
Additionally, I implemented the Edit action methods in the Movies controller, using various attributes and the Form Tag Helper.


Part 5

 I learnt how to utilize MvcMovieContext for database operations, set up connection strings, and use LocalDB.
I also used SQL Server Object Explorer to populate the database using the SeedData class. This training was quite helpful in improving my web app development abilities.



Part 6


 I learned how to design a movie data model and utilize scaffolding to produce code for CRUD operations.
 I found how to utilize Tag Helpers to simplify my HTML code and enabled movie data validation on both the server and client sides.


 

 Part 7

 I learnt how to add search features to an ASP.NET Core MVC project, including a search box and drop-down list for filtering movies by genre or name. 
and used LINQ to query the database using user input.
 I used HTML helpers like DisplayNameFor and DisplayFor to show movie attributes and the search box. I discovered that using the HTTP GET method for the search form captures the search information in the URL, making it easy to save and share.


 Part 8

 I looked into Entity Framework Code First Migrations, a feature that allows me to update my database schema based on changes in my model classes while preserving any current data. 
 I created a Movie model class with characteristics including Id, Title, ReleaseDate, Genre, Price, and Rating. I learnt how to add a new Rating property to the Movie class and then used the Add-Migration and Update-Database commands to implement the modifications to the database. I also changed the view templates and controller actions to show, create, and update the new Rating attribute in the browser1.
 The homepage closed with links that allowed me to submit comments on the instruction and view the source code onGitHub.


 part 9

  I learnt about data validation and how to utilize data annotations to define validation rules for model characteristics.
  This validation was applied on both the client and server sides. 
  I also learned how to utilize the DataType and DisplayFormat properties to govern the formatting and presentation of data fields like dates and currencies.
