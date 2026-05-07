# TCSA.OOP.LibraryManagementSystem

Lightweight library management system implemented in C# (.NET 10). This repository contains a simple OOP-based example app with controllers and a mock in-memory database for learning, prototyping, or testing UI/UX ideas.

## Features
- Basic controller-based structure (e.g., `Controllers/BaseController.cs`, `Controllers/MagazineController.cs`)
- In-memory mock database (`MockupDatabase.cs`) for quick development and testing
- Targets `.NET 10`

## Requirements
- .NET 10 SDK
- __Visual Studio__ 2026 (recommended) or any editor/IDE that supports .NET 10
- PowerShell (preferred terminal in this workspace) or any shell to run CLI commands

## Quick start

1. Clone the repository
   - git clone https://github.com/urasylmaz1/TCSA.OOP.LibraryManagementSystem.git

2. Restore and build (from the project root)
   - powershell: `dotnet restore`
   - powershell: `dotnet build`

3. Run the application
   - From the project folder: `dotnet run`
   - Or open the solution in __Visual Studio__ and run using the IDE

## Project layout (selected)
- `Controllers/` — controller classes (e.g., `BaseController.cs`, `MagazineController.cs`)
- `MockupDatabase.cs` — in-memory mock data store for samples and test data
- `Program.cs` — application entry point
- `*.csproj` — project definition targeting `.NET 10`

## Usage
This is intended as a sample/library project. Inspect controllers and `MockupDatabase` to see how entities are created, queried, and managed. Adapt or extend models and controllers to integrate with a persistent data store or UI.

## Repository
- Origin: https://github.com/urasylmaz1/TCSA.OOP.LibraryManagementSystem
