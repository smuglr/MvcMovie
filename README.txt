Sarath Somasekharan Nair(0857114)
Web app created w/ VS2022 .NET 7


Recreated the ASP .NET MVC Core application
Using .Net 7,no authentication


1325
Run the program, Confirmed the default works:
https://localhost:7261/
Modified the index.cshtml title to MVC MOVIE by replacing the default title WELCOME
Created README.txt for documentation.
Ran the application again to confirm the changes


1330
I tried Part1 of the tutorial is complete, The started with part2
Part2 - Add a Controller


1350
Commented the default index method which is returning to class view()
Then added new index method and changed the content to "This is my default action..."
Ran the program, Confirmed the changes works:
The URL to confirm
https://localhost:7261/HelloWorld



1400
Added another method called welcome with the content of "This is the Welcome action method..."
Ran the program, Confirmed the changes works:
The URL to confirm
https://localhost:7261/HelloWorld/welcome



1415
Change the Welcome method to include two parameters(name,numtimes)
Ran the program, Confirmed the changes works:
The URL to confirm
https://localhost:7261/HelloWorld/welcome?name=sarath&numtimes=4



1445
Replace the Welcome method and changed the parameters(name,id)
Ran the program, Confirmed the changes works:
The URL to confirm
https://localhost:7261/HelloWorld/welcome/0857114?name=sarath




0853
alter welcome method without sending any parameter through URL
Ran the program, Confirmed the changes works:
The URL to confirm
https://localhost:7261/HelloWorld/welcome/






PART 3

1411
Setting up views in ASP.NET core
updated the HelloWorldController class to utilize Razor view files, providing a clear and organized approach to generating HTML responses for clients.
 
 1420
The templates are created usig Razor with .cshtml file , and return a message in the controller class .
and added the code succesfully
tested the https://localhost:7061/helloworld and bang... !!!

1431
edited the 3 lines as per mentioned in the document


PART 4
1520

Adding model to ASP.NET
Adding classes for managing movies in a database

1542
Add a data Model class
Right-click the Models folder > Add > Class. Name the file Movie.cs.
given code is added 

1547
Tried to add scaffold  for CURD purpose but its showing error and I was not able to go forward for migration.
 



1415

did the scaffold agin and done without error
comple it and make sure its working properly

2024/30/05
1420
Add Migrations feature to create the database
Examine the generated database connection string in appsettings.json file
Examine the Migrations/20240530175613_InitialCreate migration file:
Confirmed with table creation called Movie.
Ran the program, Confirmed the changes works:
The URL to confirm
https://localhost:7261/movies/
https://localhost:7261/Movies/Create
https://localhost:7261/Movies/Edit/1
chttps://localhost:7261/Movies/Details/1


2024/30/05
1320
Starting part5
Examine the database by opening SQL Server Object Explorer (SSOX).
Create a new class named SeedData in movie model
Replace the contents of Program.cs
Ran the program, Confirmed the changes works:
The URL to confirm
https://localhost:7261/movies/




Part 9
6/6/2024

1455


Implemented DRY for better coding 
Add validation rules for certain Critiria and checked in https://localhost:7061/Movies/Create it's Donee...!!! Hureey
We review the project's Details and Delete methods.


1555

Then last created a git repo and push the file with newly added films and push to the git hub named mvcmovie sucessss....!
here is  the link
https://github.com/smuglr/sarath.git
