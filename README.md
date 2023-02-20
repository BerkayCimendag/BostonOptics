# BostonOptics (E-Commerce)

A Sample N-layered .NET CORE Project Demonstrating Clean Architecture and the Generic Repository Pattern.

## Migrations

### Infrastructure
Firstly,Set the project "Web" as startup project.
Secondly, choose infrastructure on Package Manager Console .
```
Add-Migration InitialCreate -context ShopContext -o Data/Migrations 
Update-Database -context ShopContext
```


## Packages Installed

### Application Core
```
Install-Package Ardalis.Specification 
```
### Infrastructure
```
Install-Package Microsoft.EntityFrameworkCore -v 6.0.14
Install-Package Microsoft.EntityFrameworkCore.Tools -v 6.0.14
Install-Package Npgsql.EntityFrameworkCore.PostgreSQL -v 6.0.8
```
## Useful Links
### Documentation
* https://learn.microsoft.com/en-us/dotnet/architecture/modern-web-apps-azure/ 

### Github
* https://github.com/dotnet-architecture/eShopOnWeb

### E-book
* https://aka.ms/webappebook



