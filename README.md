# .NET Core 6.0 API Template

This template provides a Clean Architecture structure for building Web API projects using .NET Core 6.0. It is designed to help developers set up scalable, maintainable, and testable applications quickly. The template ensures separation of concerns, with a focus on clarity and flexibility.

## Table of Contents
- [Getting Started](#getting-started)
- [Prerequisites](#prerequisites)
- [Project Structure](#project-structure)
- [Setup and Installation](#setup-and-installation)
- [Running the Application](#running-the-application)
- [Project Features](#project-features)
- [Contributing](#contributing)
- [License](#license)

## Getting Started
These instructions will help you set up and run the application locally.

### Prerequisites
To run this project, ensure that you have the following installed on your machine:
- [.NET 6.0 SDK](https://dotnet.microsoft.com/download)
- [Visual Studio 2022 or Visual Studio Code](https://code.visualstudio.com/)
- [SQL Server (Optional)] or any other database of your choice.

## Project Structure
The project follows Clean Architecture principles. The main projects are divided into layers as follows:
- **API**: Contains controllers, which expose the API endpoints.
- **Application**: Contains application logic, including services, use cases, and interfaces.
- **Domain**: Contains core business models and domain logic.
- **Infrastructure**: Handles external services like database, file system, etc.
- **Tests**: Contains unit and integration tests.

## Setup and Installation
Follow the steps below to set up the project:

### 1. Clone the Repository

<code>git clone https://github.com/muhammederencennetkusu/DOTNET_CORE_6.0_API_TEMPLATE.git</code>


### 2. Navigate to the Project Directory
<code>cd DOTNET_CORE_6.0_API_TEMPLATE</code>


### 5. Configure the Database (SQL Server)
Update the appsettings.json file in the API project with your database connection string.

<code>{
  "ConnectionStrings": {
    "DefaultConnection": "Server=your-server;Database=your-db;User Id=your-user;Password=your-password;"
  }
}</code>
If you're using SQL Server, the database configuration will be stored here. You can also use other databases (such as MySQL or PostgreSQL) by modifying the connection string and configuring the appropriate providers.
