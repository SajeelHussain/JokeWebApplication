# Joke Web Application

A simple Joke Web Application built with C# and ASP.NET Core, inspired by a YouTube tutorial by FreeCodeCamp by Shad Sluiter. This application allows users to browse, add, and manage jokes through a web interface.

## Features

- **User Authentication**: Secure login and registration using ASP.NET Identity.
- **CRUD Operations**: Create, Read, Update, and Delete jokes.
- **Responsive Design**: Optimized for both desktop and mobile users.
- **Modern UI**: Clean and user-friendly interface.

## Project Structure

```
JokeWebApplication/
├── Areas/Identity/Pages       # Authentication-related pages
├── Controllers                # Application controllers for routing and logic
├── Data                       # Database context and migrations
├── Models                     # Application models for jokes and users
├── Properties                 # Application settings and configurations
├── Views                      # Razor views for the UI
├── wwwroot                    # Static files (CSS, JS, images, etc.)
├── JokeWebApplication.csproj  # Project file
├── Program.cs                 # Application entry point
├── appsettings.json           # Configuration settings
├── appsettings.Development.json # Development-specific settings
```

## Getting Started

### Prerequisites

- [.NET 8.0 SDK](https://dotnet.microsoft.com/download)
- [SQL Server](https://www.microsoft.com/en-us/sql-server)

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/SajeelHussain/JokeWebApplication.git
   cd JokeWebApplication
   ```

2. Restore dependencies:

   ```bash
   dotnet restore
   ```

3. Apply database migrations:

   ```bash
   dotnet ef database update
   ```

4. Run the application:

   ```bash
   dotnet run
   ```

5. Open your browser and navigate to `https://localhost:5001`.

## Usage

- Browse the jokes collection.
- Add your own jokes by logging into the application.
- Edit or delete jokes that you created.

## Technologies Used

- C#
- ASP.NET Core
- Entity Framework Core
- Razor Pages
- SQL Server

## Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/your-feature-name`).
3. Commit your changes (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature/your-feature-name`).
5. Open a pull request.


## Acknowledgments

- Special thanks to the creator of the YouTube tutorial for guiding this project.(https://www.youtube.com/watch?v=BfEjDD8mWYg)

---

Feel free to connect with me on [LinkedIn](https://www.linkedin.com/in/sajeel-awan/) or check out more of my projects on [GitHub](https://github.com/SajeelHussain).
