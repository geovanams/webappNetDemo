# webappNetDemo

A simple ASP.NET Core 8.0 MVC web application demonstrating the Model-View-Controller pattern.

## Description

This is a .NET 8.0 web application built using ASP.NET Core MVC. It follows the standard MVC architecture with separate concerns for models, views, and controllers.

## Prerequisites

- [.NET 8.0 SDK](https://dotnet.microsoft.com/download/dotnet/8.0) or later
- A code editor (Visual Studio, Visual Studio Code, or JetBrains Rider)

## Project Structure

```
webappNetDemo/
├── Controllers/         # MVC Controllers
│   └── HomeController.cs
├── Models/             # Data models
│   └── ErrorViewModel.cs
├── Views/              # Razor views
│   ├── Home/
│   │   ├── Index.cshtml
│   │   └── Privacy.cshtml
│   └── Shared/
│       ├── _Layout.cshtml
│       ├── _ValidationScriptsPartial.cshtml
│       └── Error.cshtml
├── wwwroot/            # Static files (CSS, JS, images)
│   ├── css/
│   ├── js/
│   └── lib/
├── Program.cs          # Application entry point
├── appsettings.json    # Configuration settings
└── webapp.csproj       # Project file
```

## Getting Started

### Installation

1. Clone the repository:
   ```powershell
   git clone https://github.com/geovanams/webappNetDemo.git
   cd webappNetDemo
   ```

2. Restore dependencies:
   ```powershell
   dotnet restore
   ```

### Running the Application

1. Build the project:
   ```powershell
   dotnet build
   ```

2. Run the application:
   ```powershell
   dotnet run
   ```

3. Open your browser and navigate to:
   - HTTPS: `https://localhost:5001`
   - HTTP: `http://localhost:5000`

   (Port numbers may vary; check the console output for the exact URLs)

### Development Mode

To run the application in development mode with hot reload:

```powershell
dotnet watch run
```

## Features

- **MVC Architecture**: Clean separation of concerns with Models, Views, and Controllers
- **Razor Views**: Dynamic HTML generation using Razor syntax
- **Bootstrap Integration**: Responsive design using Bootstrap CSS framework
- **jQuery**: Client-side JavaScript functionality
- **Error Handling**: Built-in error pages and exception handling
- **Static Files**: Organized CSS, JavaScript, and library files

## Configuration

Application settings can be modified in:
- `appsettings.json` - Production settings
- `appsettings.Development.json` - Development-specific settings

## Built With

- [ASP.NET Core 8.0](https://docs.microsoft.com/aspnet/core/) - Web framework
- [Bootstrap](https://getbootstrap.com/) - CSS framework
- [jQuery](https://jquery.com/) - JavaScript library

## License

This project is available for educational and demonstration purposes.

## Author

- GitHub: [@geovanams](https://github.com/geovanams)
