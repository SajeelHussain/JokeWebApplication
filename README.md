
# 😂 Joke Web Application

A simple Joke Web Application built using **C#** and **ASP.NET Core**, inspired by a [YouTube tutorial by Shad Sluiter on FreeCodeCamp](https://www.youtube.com/watch?v=BfEjDD8mWYg). This app allows users to browse, add, and manage jokes through a clean, user-friendly web interface.

---

## ✨ Features

- 🔐 **User Authentication**: Secure login and registration using ASP.NET Identity.
- ✏️ **CRUD Operations**: Create, Read, Update, and Delete jokes with ease.
- 📱 **Responsive Design**: Fully optimized for both desktop and mobile devices.
- 🎨 **Modern UI**: Minimal, intuitive, and clean user interface.

---

## 🗂️ Project Structure

```
JokeWebApplication/
├── Areas/Identity/Pages         # Authentication pages (login, register, etc.)
├── Controllers                  # Handles application logic and routing
├── Data                         # Database context and EF migrations
├── Models                       # Data models (Joke, ApplicationUser)
├── Properties                   # Project configuration settings
├── Views                        # Razor pages for frontend rendering
├── wwwroot                      # Static assets (CSS, JS, images)
├── JokeWebApplication.csproj    # Project file for build configuration
├── Program.cs                   # Main entry point for the application
├── appsettings.json             # Configuration settings
├── appsettings.Development.json# Development environment config
```

---

## 🚀 Getting Started

### ✅ Prerequisites

- [.NET 8.0 SDK](https://dotnet.microsoft.com/en-us/download/dotnet/8.0)
- SQL Server (Express or LocalDB)

### 🔧 Installation

1. **Clone the repository**:

```bash
git clone https://github.com/SajeelHussain/JokeWebApplication.git
cd JokeWebApplication
```

2. **Restore dependencies**:

```bash
dotnet restore
```

3. **Apply EF Core migrations**:

```bash
dotnet ef database update
```

4. **Run the application**:

```bash
dotnet run
```

Then open your browser and navigate to: [https://localhost:5001](https://localhost:5001)

---

## 🧪 Usage

- Browse through a list of hilarious jokes.
- Log in or register to contribute your own jokes.
- Edit or delete jokes you’ve created.

---

## 💻 Technologies Used

- **C#**
- **ASP.NET Core**
- **Entity Framework Core**
- **Razor Pages**
- **SQL Server**

---

## 🤝 Contributing

Contributions are welcome! Here's how you can contribute:

1. Fork the repository.
2. Create your feature branch:

```bash
git checkout -b feature/your-feature-name
```

3. Commit your changes:

```bash
git commit -m "Add some feature"
```

4. Push to your branch:

```bash
git push origin feature/your-feature-name
```

5. Open a pull request and describe your changes.

---

## 🙏 Acknowledgments

Special thanks to **Shad Sluiter** and **FreeCodeCamp** for the amazing tutorial that inspired this project: [Watch it here](https://www.youtube.com/watch?v=BfEjDD8mWYg).

---

Feel free to connect with me on [LinkedIn](https://www.linkedin.com/) or explore more projects on [GitHub](https://github.com/SajeelHussain).
