# Customize the Title of a Syncfusion Blazor Chart

## Overview

This sample demonstrates how to customize the title of a Syncfusion [Blazor Charts](https://www.syncfusion.com/blazor-components/blazor-charts) component. The chart renders medal data using a column series and applies title styling through the `ChartTitleStyle` configuration.

The sample shows how to control title appearance by modifying alignment, font family, font color, and text overflow behavior. These customization options help developers create more visually appealing charts that align with application branding and design requirements.

## Key Features

- Uses the `SfChart` component to render chart data.
- Sets the chart title using the `Title` property.
- Customizes title appearance through the `ChartTitleStyle` component.
- Configures title overflow handling using `TextOverflow="TextOverflow.Wrap"`.
- Controls title alignment using `TextAlignment="Alignment.Far"`.
- Changes title font color using `Color="blue"`.
- Applies a custom font using `FontFamily="Helvetica"`.
- Uses a category-based primary axis with `ChartPrimaryXAxis`.
- Sets `ValueType="Syncfusion.Blazor.Charts.ValueType.Category"` for category data rendering.
- Binds chart data through the `DataSource` property.
- Maps category values using the `XName` property.
- Maps numeric values using the `YName` property.
- Displays chart data using `ChartSeriesType.Column`.

## Prerequisites

- [Visual Studio 2022](https://visualstudio.microsoft.com/vs/) or [Visual Studio Code](https://code.visualstudio.com/)
- [.NET SDK](https://dotnet.microsoft.com/en-us/download/dotnet) compatible with the project's target framework

## How to Run the Project

**Visual Studio 2022**

1. Clone or download this repository.
2. Open the `TitleCustomization.csproj` file from the `TitleCustomization` folder.
3. Restore the NuGet packages.
4. Build the project.
5. Run the application using `Ctrl+F5`.

**Visual Studio Code**

1. Clone or download this repository.
2. Open the repository folder in Visual Studio Code.
3. Open the integrated terminal.
4. Navigate to the project directory.

```bash
cd TitleCustomization
dotnet restore
dotnet run
```

5. After the application starts successfully, open the local URL displayed in the terminal.

## Project Structure

`TitleCustomization/Pages/Index.razor` - Implements the chart title customization example using `SfChart`, `ChartTitleStyle`, `ChartSeries`, and category axis configuration.

## Support and Feedback

- For general product questions, visit the [Syncfusion Community Forum](https://www.syncfusion.com/forums) or [Syncfusion Support](https://www.syncfusion.com/support).
- To report an issue specific to this sample, open a GitHub issue in this repository.
- Refer to the official documentation: https://help.syncfusion.com/chart-sdk/blazor/charts/advanced-accessibility-configuration#title-and-subtitle

## License

This is a Syncfusion sample project provided to demonstrate product usage. Review the [Syncfusion license terms](https://www.syncfusion.com/sales/pricing?category=ui-components) before using Syncfusion components in your own applications.