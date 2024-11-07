# Jokes App

## Overview
Jokes App is a web application built using C# and ASP.NET Core MVC, providing a platform where users can create, edit, delete, and view jokes. Additionally, users can register, log in, and explore a collection of jokes with questions and answers. The app demonstrates the core functionalities of an MVC-based web application, including user authentication, CRUD operations, and a responsive user interface.

## Features
- **User Registration**: New users can create an account.
- **User Login**: Registered users can securely log in.
- **Create Jokes**: Authenticated users can create new jokes.
- **Edit Jokes**: Users can edit jokes they have created.
- **Delete Jokes**: Users can delete their jokes.
- **View Jokes**: All users can browse and view joke questions and answers.
  
## Technologies Used
- **Framework**: ASP.NET Core 6 MVC
- **Language**: C#
- **Database**: SQLite (or specify the database used, e.g., SQL Server, MySQL)
- **Front-End**: HTML, CSS, JavaScript (with optional frameworks if used, like Bootstrap for styling)
- **Authentication**: ASP.NET Identity for user registration and login

## Installation and Setup

### Prerequisites
- .NET SDK (version 6.0 or higher)
- Visual Studio or any preferred C# IDE
- A database (SQLite, SQL Server, etc.)

### Steps to Run the Project Locally
1. **Clone the Repository**: <br />
   bash <br />
   <code> git clone https://github.com/NOBERT167Jokes-App.git</code>
2. **Navigate to the Project Directory:** <br />
bash <br />
<code>cd jokes-app </code> <br />

3. Configure Database:** <br />
Update the appsettings.json file to specify your database connection string. <br />

4. **Run Database Migrations:** <br />
bash <br />
<code>dotnet ef database update</code> <br />

5. **Run the Application:** <br />
bash <br />
<code>dotnet run</code><br />
The project will run on your browser. <br />

## Usage 
Register a new account or log in with an existing account.
Use the "Create Joke" feature to add a new joke question and answer.
Edit or delete jokes that you created from the joke detail view.
View all jokes created by users on the platform.

## Contributing
Contributions are welcome! Please fork the repository, create a feature branch, and submit a pull request for review.
