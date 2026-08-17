# Blazor Kanban - Swimlane Row Custom Sorting

A sample Blazor application showcasing **custom swimlane row sorting** in the Syncfusion [Blazor Kanban](https://www.syncfusion.com/gantt-sdk/blazor-kanban-board) component.

## Overview

By default, the Blazor Kanban orders swimlane rows alphabetically or by data source order. This sample demonstrates how to override that behavior and **define a custom, programmatic order** for swimlane rows — essential for workflows that require priority-based sorting, custom status sequences, or user-defined task organization.

## Features

- **Custom Swimlane Row Ordering** — Demonstrates programmatic reordering of swimlane rows via the `SwimlaneSorting` event
- **Multi-Column Kanban Board** — Blazor Kanban with three workflow columns (To Do, In Progress, Done)
- **Interactive Server Rendering** — Built with Blazor Interactive Server components for real-time interactivity
- **In-Memory Data Source** — Complete working example with in-memory task data (no database required)
- **Event-Driven Sorting Logic** — Type-safe event binding demonstrating how to capture and reorder swimlane rows dynamically

## Getting started

### Prerequisites

- [.NET 10 SDK](https://dotnet.microsoft.com/download) or later
- [Visual Studio 2022](https://visualstudio.microsoft.com/)
- [Visual Studio Code](https://code.visualstudio.com/)

### Clone the repository:
   
```bash
git clone https://github.com/SyncfusionExamples/blazor-kanban-swimlane-sorting.git
cd blazor-kanban-swimlane-sorting
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

**Documentation**: https://help.syncfusion.com/gantt-sdk/blazor/kanban/swimlane

**Online example**: https://blazor.syncfusion.com/demos/kanban/swimlane?theme=fluent2
