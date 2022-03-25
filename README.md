# FirstMicroservice
Microservice represent architectural style in which system is broken into many small individual services exposed as an API to the rest of the system & external consumers.
Two key elements of .NET Core's design are:
1.	modularity 
2.	lightweight nature.

Tasks:
1.	Create a web API project.
2.	Add a model class and a database context.
3.	Scaffold a controller with CRUD methods.
4.	Configure routing, URL paths, and return values.
5.	Call the web API with Postman.

Tools & Extensions to install: 
•	Visual Studio Code
•	C# for Visual Studio Code (latest version)
•	.NET 6.0 SDK

CLI Commands:
1.	Create an empty solution
dotnet new sln --name <sln_name>
2.	Create a web api 
dotnet new webapi -n <apiname>
Default version: 5.0

3.	Associate the webapi with the solution
dotnet sln add <api>\<csproj name>.csproj

4.	Build project using below command
Dotnet build
5.	start <sln_name>.sln
6.	Create a Models Folder & create model class by right click->Add new file in VSCode
