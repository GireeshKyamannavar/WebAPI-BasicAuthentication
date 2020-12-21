# Implementing basic authentication in Web API using .NET 5

Step 1: Add app.UseAuthentication() below app.UseRouting()  in Startup.cs

![](https://github.com/GireeshKyamannavar/WebAPI-BasicAuthentication/blob/master/Pictures/Picture1.png)

Step 2: Create Authentication Handler to handle the authorization header, check whether the passing username and password is valid or invalid.

![](https://github.com/GireeshKyamannavar/WebAPI-BasicAuthentication/blob/master/Pictures/Picture2.png)

Step 3: Add services.AddAuthentication in ConfigureServices.

![](https://github.com/GireeshKyamannavar/WebAPI-BasicAuthentication/blob/master/Pictures/Picture3.png)

Step 4 : Add [Authorize] to handle authentication at controller level.

![](https://github.com/GireeshKyamannavar/WebAPI-BasicAuthentication/blob/master/Pictures/Picture4.png)
 
Step 5: Test the API without entering credentials

![](https://github.com/GireeshKyamannavar/WebAPI-BasicAuthentication/blob/master/Pictures/Picture5.png)
  
Step 6: Test the API with entering credentials

![](https://github.com/GireeshKyamannavar/WebAPI-BasicAuthentication/blob/master/Pictures/Picture6.png)


