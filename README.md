
# Blazor Synchronized Charts

A Blazor application demonstrating synchronized chart interactions using Blazor Chart component. This project showcases how to synchronize crosshair, tooltip, selection, and zoom behaviors across multiple charts.

## Overview

This sample demonstrates synchronized interactions in  [Blazor Charts](https://www.syncfusion.com/blazor-components/blazor-charts). When you interact with one chart (hover, select, zoom), the same interaction is mirrored across all synchronized charts.

The sample uses currency exchange rate data (USD to EUR, JPY, SGD, INR) spanning February to August 2023.

## Features

Four synchronization modes are available:

* **Crosshair**  - Synchronizes crosshair position across charts when hovering 
* **Tooltip** - Shows synchronized tooltips on all charts simultaneously 
* **Selection**- Synchronizes point selection across charts 
* **Zooming** - Synchronizes zoom level and pan position across charts 

## Prerequisites

- [.NET SDK 8.0](https://dotnet.microsoft.com/download/dotnet/8.0) or later
- [Visual Studio 2022](https://visualstudio.microsoft.com/) or later
- [VS Code](https://code.visualstudio.com/)

## Getting Started

### Clone the repository:

```bash
git clone https://github.com/SyncfusionExamples/Blazor-Synchronized-Charts.git
cd Blazor-Synchronized-Charts
```

### Run with Visual Studio

1. Open the solution file using Visual Studio 2022 or later.
2. Restore the NuGet packages by rebuilding the solution.
3. Build the project to ensure there are no compilation errors.
4. Run the project.

### Run with .NET CLI

```bash
# Restore dependencies
dotnet restore

# Run the project
dotnet run
```

## References

- [Syncfusion Blazor Charts Documentation](https://blazor.syncfusion.com/documentation/chart/chart-events)
- [Syncfusion Blazor Components](https://www.syncfusion.com/blazor-components)
- [.NET Blazor Documentation](https://learn.microsoft.com/aspnet/core/blazor/)
