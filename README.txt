

 First, I created a new project using the MVC template.
 Next, I added a Movie class to the Models folder, which defined the properties of the movie data.
 Then, I added a MvcMovieContext class to the Data folder, which represented the database context for accessing the movie data.
 After that, I registered the context as a service in Program.cs, which enabled dependency injection of the context into the controllers.
 Furthermore, I added a connection string to the appsettings.json file, which specified the database provider and the name of the database.
 Moreover, I used the scaffolding tool to generate CRUD pages for the movie model, which created a Movies controller and corresponding views.
 Finally, I used the EF Core migrations feature to create the database from the model, and ran the app to test the movie pages.



 This tutorial taught me how to create a web app project using the MVC template, add a model class and use Entity Framework Core to work with a database, use scaffolding to generate controllers and views, perform CRUD operations on the model data, and use migrations to update the database schema.


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

