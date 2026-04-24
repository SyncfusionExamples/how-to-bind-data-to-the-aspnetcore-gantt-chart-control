# ASP.NET Core Gantt Chart Data Binding Sample

A sample ASP.NET Core Razor Pages application demonstrating how to bind the Syncfusion EJ2 Gantt Chart to a remote data service.

## Project Overview

The sample focuses on loading Gantt task data from a remote web API and rendering it in a Razor Pages application. It demonstrates how hierarchical task information, scheduling dates, progress values, and predecessor relationships can be visualized using the Syncfusion EJ2 Gantt Chart. The example highlights common data‑binding scenarios used in project scheduling applications.

## Features

- Remote data binding using `DataManager` and `WebApiAdaptor`
- Syncfusion EJ2 Gantt Chart integration with Razor Pages
- Task field mapping for ID, name, start date, end date, duration, progress, dependencies, and child tasks
- Weekly timeline view configuration

## Getting Started

### Prerequisites

- .NET SDK (8.0 or later)
- Visual Studio or a compatible ASP.NET Core development environment

### Run the Application

1. Open the project file in your development environment.
2. Restore NuGet packages.
3. Build and run the application.
4. Open the home page to view the Gantt Chart.

## Notes

- A Syncfusion‑hosted web API endpoint is used for demonstration purposes.
- The data source configuration can be modified to use local collections.
- Task models and mapping logic are defined in the Razor Pages code‑behind.

## Resources

- Documentation: https://ej2.syncfusion.com/aspnetcore/documentation/gantt/data-binding
- Online example: https://ej2.syncfusion.com/aspnetcore/gantt/remotedata#/bootstrap5
