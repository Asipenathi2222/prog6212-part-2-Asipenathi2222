# RaceDayAPI– PROG6212 Part 2

## Project Overview
RaceDay is an event management system developed for the PROG6212 Part 2 project. It is built using C# and ASP.NET Core Web API, with SQL Server and Entity Framework Core for data persistence.

## Technologies Used
- C#
- ASP.NET Core Web API (.NET 8)
- SQL Server
- Entity Framework Core
- Swagger / OpenAPI
- Visual Studio 2022
- Automated testing

## Features
- User registration and login
- Organiser and Participant roles
- Session-based authentication
- Role-protected endpoints
- Event management
- Category management
- Registrations
- Results

## Project Structure
- `RACEDAY.API/` — API application, controllers, models and database configuration.
- Test project — automated tests.
- Solution file (`.sln`) — opens the projects in Visual Studio.

## Requirements
- Visual Studio 2022
- .NET 8 SDK
- SQL Server

## Setup Instructions
1. Clone or download this repository.
2. Open the solution file in Visual Studio 2022.
3. Configure the SQL Server connection string for your environment.
4. Restore NuGet packages.
5. Apply the database migrations or create/update the database using the project's configured approach.
6. Set `RACEDAY.API` as the startup project.
7. Run the application and open the Swagger URL displayed by Visual Studio.

## Running Tests
1. Open the solution in Visual Studio.
2. Build the solution.
3. Open **Test → Test Explorer**.
4. Select **Run All Tests** and review the results.

## Security
Do not commit database passwords, API keys, tokens or other sensitive credentials. Use configuration appropriate to your local environment.

## Academic Project
**Module:** PROG6212  
**Project:** RaceDay – Part 2
