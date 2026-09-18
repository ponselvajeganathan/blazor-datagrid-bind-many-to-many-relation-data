# Blazor DataGrid - Bind Many-to-Many Relation Data

## Overview

This sample demonstrates how to display and edit many-to-many relational data in the Syncfusion Blazor DataGrid. Since the DataGrid does not provide built-in support for directly binding many-to-many relationship properties, the implementation uses `ColumnTemplate` and `EditTemplate` to render related values and provide editing capabilities within the grid. The sample also demonstrates CRUD operations while managing relationship data, making it a useful reference for applications that need to present and maintain complex relational datasets in a DataGrid interface.

## Key Features

- Demonstrates display of many-to-many relational data in the Syncfusion Blazor DataGrid.
- Uses the `ColumnTemplate` feature to render related values within DataGrid columns.
- Uses the `EditTemplate` feature to provide a customized editing experience for many-to-many relationships.
- Demonstrates CRUD operations while maintaining relationship data.
- Shows how relationship information can be presented when direct DataGrid support for many-to-many binding is unavailable.
- Provides a practical implementation pattern for displaying related collections within a grid column.
- Demonstrates template-based customization for both display and edit scenarios.
- Maintains standard DataGrid functionality while extending support for relational data visualization and editing.
- Serves as a reference implementation for applications working with many-to-many entity relationships.

## Prerequisites

- Visual Studio 2022 or Visual Studio Code
- .NET SDK compatible with the project's target framework

## How to Run the Project

**Visual Studio 2022**

1. Clone or download the repository.
2. Open the solution file located in the `Grid-ManyToManyRelation` project folder. `[VERIFY: exact .sln file name]`
3. Restore all NuGet packages.
4. Set the appropriate startup project within the `Grid-ManyToManyRelation` solution if required.
5. Build the solution.
6. Run the application using `Ctrl+F5`.

**Visual Studio Code**

1. Open the repository folder in Visual Studio Code.
2. Open the integrated terminal.
3. Navigate to the project directory.

```bash
cd Grid-ManyToManyRelation
dotnet restore
dotnet run
```

4. Open the local URL displayed in the terminal after the application starts.

## Project Structure

- `Grid-ManyToManyRelation/Pages/` — contains the Blazor DataGrid implementation, column template configuration, edit template configuration, and CRUD interaction logic.

## Support and Feedback

- For general product questions, visit the [Syncfusion Community Forum](https://www.syncfusion.com/forums) or [Syncfusion Support](https://www.syncfusion.com/support).
- To report an issue specific to this sample, open a GitHub issue in this repository.
- For feature documentation, see the Syncfusion Blazor DataGrid Column Template documentation: https://help.syncfusion.com/grid-sdk/blazor/data-grid/column-template

## License

This is a Syncfusion sample project provided to demonstrate product usage. Review the [Syncfusion license terms](https://www.syncfusion.com/sales/pricing?category=ui-components) before using Syncfusion components in your own applications.