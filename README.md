# Task Manager

## Objective
Using the provided files, create a Task Manager API that allows for full CRUD operations on both ToDoLists and Items with the ability to retrieve Items for a specific list. 

## .NET CLI Commands

```bash
# Installing global tools (only need to do once)
dotnet tool install -g dotnet-ef
dotnet tool install -g dotnet-aspnet-codegenerator

# Installing Entity Framework
dotnet add package Microsoft.EntityFrameworkCore
dotnet add package Microsoft.EntityFrameworkCore.Sqlite
dotnet add package Microsoft.EntityFrameworkCore.SqlServer
dotnet add package Microsoft.EntityFrameworkCore.Design
dotnet add package Microsoft.EntityFrameworkCore.Tools

# Generating DBContext and Data Models for SQLite Database
dotnet ef dbcontext scaffold "Data Source={Path to Database}" Microsoft.EntityFrameworkCore.Sqlite -o DataAccess

# Creating a new Controller
dotnet new class -n {FileName} -o {DirectoryName}

```
