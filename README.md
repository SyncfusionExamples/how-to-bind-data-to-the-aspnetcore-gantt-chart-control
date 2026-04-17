# ASP.NET Core Gantt Chart Data Binding Sample

A sample ASP.NET Core Razor Pages project demonstrating remote data binding for the Syncfusion EJ2 Gantt Chart control.

## Overview

This sample binds the Gantt Chart to remote data via `e-data-manager` and `WebApiAdaptor`. It maps task fields such as ID, name, dates, duration, progress, predecessor, and child tasks.

## Features

- Remote data binding with `DataManager`
- Syncfusion EJ2 Gantt in Razor Pages
- Task field mapping
- Weekly timeline view

## Project details

- .NET 8.0
- `Syncfusion.EJ2.AspNet.Core` v27.1.52
- `Pages/Index.cshtml`
- `Program.cs`

## Prerequisites

- .NET 8 SDK
- Visual Studio 2022 or later
- Syncfusion license key

## Run

1. Open `GanttExample.csproj` in Visual Studio.
2. Restore NuGet packages.
3. Set the Syncfusion license key in `Program.cs`:

```csharp
Syncfusion.Licensing.SyncfusionLicenseProvider.RegisterLicense("Your License Key");
```

4. Build and run.
5. Open the home page.

## Notes

- Remote endpoint: `https://services.syncfusion.com/aspnet/production/api/GanttData`
- For local data, update the `Index.cshtml` data source.
- `GanttDataSource` in `Pages/Index.cshtml.cs` defines the task model.

## Resources

- Syncfusion docs: https://ej2.syncfusion.com/aspnetcore/documentation/gantt/data-binding
- Example: https://ej2aspnetcore.azurewebsites.net/aspnetcore/gantt/localdata#/bootstrap5
