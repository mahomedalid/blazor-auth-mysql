# Blazor + Auth + MySQL

Blazor boilerplate template including user authentication with a MySQL database. This template uses Pomelo.EntityFrameworkCore.MySql for the connection to the database throught the Entity Framework.

# Pre-reqs

* dotnet sdk
* dotnet entity framework tool
* MySQL/MariaDB server

# How to use it

* Create a MySQL/MariaDB database, no need to create any tables this repo will execute some **migrations**.
* Clone ths repo
* Update the `DefaultConnection` setting in [appsettings.json](appsettings.json) with the hostname/ip, port, user, password and database name.
* Run `dotnet ef database update`
* Run `dotnet watch`