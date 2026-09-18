# Blazor DataGrid Batch Editing

## Overview

This sample demonstrates how to enable and use batch editing in the Syncfusion Blazor DataGrid (`SfGrid`). Batch editing allows users to modify multiple cells across different rows without immediately committing each change. All pending modifications can be reviewed and saved together, making data entry scenarios faster and reducing the number of individual update operations performed by the grid.

The sample uses a local `OrderDetails` data source and renders the grid through a Razor page within a Blazor Server application.

## Key Features

- Uses the Syncfusion Blazor DataGrid (`SfGrid`) component to display tabular order data.
- Configures grid editing through the `GridEditSettings` configuration.
- Enables batch update behavior by setting the grid edit mode to `EditMode.Batch`.
- Allows editing multiple cells and rows before committing changes.
- Uses a local `OrderDetails` model as the grid data source.
- Demonstrates client-side batch modification workflow where changes are accumulated and saved together instead of being applied immediately after each edit.
- Displays editable order records generated from the sample data source in the `Data` folder.

## Prerequisites

* Visual Studio 2022 or Visual Studio Code

## How to Run the Project

**Visual Studio 2022**

1. Clone or download this repository.
2. Open `BatchEditingSample.sln` using Visual Studio 2022.
3. Restore NuGet packages for the project.
4. Build the solution.
5. Run the application.
6. Navigate to the default page to view the Syncfusion Blazor DataGrid batch editing sample.
7. Edit multiple cells across different rows and save the pending changes through the grid's batch editing workflow.

**Visual Studio Code**

1. Open the repository folder in Visual Studio Code.
2. Open the integrated terminal.
3. Navigate to the project directory.

```bash
dotnet restore
dotnet run
```

## Project Structure

- `Pages/Index.razor` — hosts the Syncfusion `SfGrid` implementation, column definitions, data binding configuration, and batch editing settings.

- `Data/OrderDetails.cs` — contains the `OrderDetails` model and sample records used as the grid data source.

## Support and Feedback

- For general product questions, visit the [Syncfusion Community Forum](https://www.syncfusion.com/forums) or [Syncfusion Support](https://www.syncfusion.com/support).
- To report an issue specific to this sample, open a GitHub issue in this repository.
- For feature documentation, see the Syncfusion Blazor DataGrid batch editing documentation: https://help.syncfusion.com/grid-sdk/blazor/data-grid/batch-editing

## License

This is a Syncfusion sample project provided to demonstrate product usage. Review the [Syncfusion license terms](https://www.syncfusion.com/sales/pricing?category=ui-components) before using Syncfusion components in your own applications.
