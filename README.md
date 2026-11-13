# ProductApiEFCore

### ProductApi
ASP.NET Core Web API project with:

### Product and Category entities
EF Core
SQL Server connection
CRUD endpoints
DTO-based API responses

### Technologies
.NET 8
ASP.NET Core Web API
Entity Framework Core
SQL Server

### Getting Started
Restore packages:
dotnet restore

Update connection string in appsettings.json

### Run migrations:
dotnet ef database update

### Start project:
dotnet run

 Docker info
 sudo docker run -e "ACCEPT_EULA=Y" -e "MSSQL_SA_PASSWORD=pwd" -p 1433:1433 --name sqlserver -d mcr.microsoft.com/mssql/server:2022-latest

 sudo docker start sqlserver
