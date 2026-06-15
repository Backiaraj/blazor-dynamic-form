# Blazor Dynamic Form Builder

Build dynamic forms in Blazor with automatic field generation from data annotations, integrated Blazor components ([TextBox](https://www.syncfusion.com/blazor-components/blazor-textbox), [DatePicker](https://www.syncfusion.com/blazor-components/blazor-datepicker), [NumericTextBox](https://www.syncfusion.com/blazor-components/blazor-numeric-textbox), [DropDownList](https://www.syncfusion.com/blazor-components/blazor-dropdown-list), [ComboBox](https://www.syncfusion.com/blazor-components/blazor-combobox)), and comprehensive client-side validation.

## Overview

This project showcases a powerful pattern for building data-driven forms in Blazor applications. Rather than manually declaring each form field, the `DynamicFormBuilderSample` uses reflection to inspect a model's properties and their data annotations, then dynamically generates the appropriate Blazor components.

The form automatically handles:
- **Field type detection** from `DataType` attributes
- **Component rendering** using Blazor's `RenderFragment` and component builder API
- **Two-way data binding** with reflection-based value expressions
- **Validation** through data annotations and validators
- **Multi-format support** for text, email, phone, dates, numbers, and custom dropdowns

## Features

- **Dynamic Form Generation** - Auto-generates forms from model properties using reflection
- **Multiple Input Types** - Text, email, phone, date picker, numeric fields, dropdown lists, and combo boxes
- **Data Annotations Validation** - Built-in validation through `DataType`, `Required`, `EmailAddress`, `Phone`, `Range` attributes
- **Integration** - Leverages Blazor components (TextBox, DatePicker, NumericTextBox, DropDownList, ComboBox)
- **Floating Labels** - Auto-floating labels for better UX
- **Component Builder Pattern** - Demonstrates advanced Blazor patterns with `RenderFragment` and reflection
- **Form Submission** - Ready-to-extend submit handling for data persistence

## Prerequisites

* [.NET SDK 10.0](https://dotnet.microsoft.com/en-us/download/dotnet/10.0) or later
* [Visual Studio 2022](https://visualstudio.microsoft.com/vs/) or later
* [Visual Studio Code](https://code.visualstudio.com/)

## Getting Started

### Clone the Repository

```bash
git clone https://github.com/SyncfusionExamples/blazor-dynamic-form.git
cd blazor-dynamic-form
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

* [Online examples](https://blazor.syncfusion.com/demos/)
* [Documentation](https://blazor.syncfusion.com/documentation/getting-started/blazor-server-side-visual-studio)
* [Blog reference](https://www.syncfusion.com/blogs/post/spice-up-your-blazor-editform-with-syncfusion-blazor-components)