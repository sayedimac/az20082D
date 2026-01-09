# Az20082D MVC Application

This is a basic .NET 10.0 Core MVC (Model-View-Controller) web application.

## Project Structure

The application follows the standard ASP.NET Core MVC pattern:

- **Controllers/**: Contains the controller classes that handle HTTP requests
  - `HomeController.cs`: Main controller with Index, Privacy, and Error actions
  
- **Models/**: Contains the data models and view models
  - `ErrorViewModel.cs`: Model for error page display
  
- **Views/**: Contains the Razor view templates
  - `Home/`: Views for the Home controller (Index, Privacy)
  - `Shared/`: Shared layout and partial views

- **wwwroot/**: Static files (CSS, JavaScript, images)

- **Program.cs**: Application entry point and configuration

## Prerequisites

- .NET 10.0 SDK or later

## How to Build

```bash
cd source/Az20082DApp
dotnet build
```

## How to Run

```bash
cd source/Az20082DApp
dotnet run
```

The application will start and be available at:
- http://localhost:5000 (HTTP)
- https://localhost:5001 (HTTPS)

## Features

- Home page with welcome message
- Privacy page
- Error handling with custom error page
- Responsive layout using Bootstrap
- MVC routing configuration
