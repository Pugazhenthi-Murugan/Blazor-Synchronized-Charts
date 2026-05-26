
# Blazor Synchronized Charts

A Blazor application demonstrating synchronized chart interactions using [Blazor Chart](https://www.syncfusion.com/blazor-components/blazor-charts) component. This project showcases how to synchronize crosshair, tooltip, selection, and zoom behaviors across multiple charts.

## Overview

This sample demonstrates synchronized interactions in  Blazor Charts component. When you interact with one chart (hover, select, zoom), the same interaction is mirrored across all synchronized charts.

## Features

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

- https://blazor.syncfusion.com/documentation/chart/cross-hair-and-track-ball
- https://blazor.syncfusion.com/documentation/chart/selection
- https://blazor.syncfusion.com/documentation/chart/zooming
- https://blazor.syncfusion.com/documentation/chart/tool-tip
