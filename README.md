<div align="center">
  <img width="100" height="100" alt="WebBoost Logo" src="https://github.com/user-attachments/assets/f1885b23-c7fb-418b-989a-cb7ed1d08478" />
  <h1>WebBoost IDE</h1>

  ![.NET](https://img.shields.io/badge/.NET-10.0-512BD4?style=flat-square&logo=dotnet&logoColor=white)
  ![C#](https://img.shields.io/badge/C%23-239120?style=flat-square)
  ![Avalonia UI](https://img.shields.io/badge/Avalonia_UI-12.1.1-8B44AC?style=flat-square)
  ![Architecture](https://img.shields.io/badge/architecture-x64_%7C_x86-6C757D?style=flat-square)

  
  <p>An open-source IDE built for modern web development.</p>
</div>

> [!IMPORTANT]
> WebBoost is currently in active development.

## Quick Start
Prerequisites:
- [.NET SDK 10.0.303](https://dotnet.microsoft.com/download/dotnet/10.0)
- [Git](https://git-scm.com/install/)

The SDK version is pinned in `global.json`.

```
# Clone repository
git clone https://github.com/vldyrex/WebBoost.git
cd WebBoost

# Restore dependencies
dotnet restore WebBoost.slnx

# Build project
dotnet build WebBoost.slnx --configuration Debug --property:Platform=x64

# Run application
dotnet run --project WebBoost.csproj --configuration Debug --property:Platform=x64
```

## Project Structure

```
WebBoost/
├── Assets/                  # Application icons and other resources
│   └── webboost-logo.ico    # Application icon
├── Views/                   # Avalonia UI views
│   ├── MainWindow.axaml     # Main window layout
│   └── MainWindow.axaml.cs  # Main window code-behind
├── App.axaml                # Global application styles and theme
├── App.axaml.cs             # Application initialization and lifecycle
├── Program.cs               # Application entry point
├── app.manifest             # Windows application manifest
```

## License

WebBoost is open-source software released under the [MIT License](LICENSE).
