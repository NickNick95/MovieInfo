# MovieInfo
 API server for searching movie information in database

Technologies stack:
.Net Cor 3.1;
MS SQL Server last version; 

How to run: 
 1) Update your DefaultConnection in MovieInfor.API/appsettings.json;
 2) Run migration: Add-Migration InitialCreate. You can use .net CLI or package management in VisualStudio
    link: https://learn.microsoft.com/en-us/ef/core/managing-schemas/migrations/?tabs=dotnet-core-cli
 3) Run Update-Database in the same terminal;
 4) Run application, by default you can see Swagger page;