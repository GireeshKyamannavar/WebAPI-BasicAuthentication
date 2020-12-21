# Implementing basic authentication in Web API using .NET 5

Step 1: Add app.UseAuthentication() below app.UseRouting()  in Startup.cs

Step 2: Create Authentication Handler to handle the authorization header, check whether the passing username and password is valid or invalid.

Step 3: Add services.AddAuthentication in ConfigureServices.

Step 4 : Add [Authorize] to handle authentication at controller level.
 
Step 5: Test the API without entering credentials
  
Step 6: Test the API with entering credentials


