# ![MudBlazor](content/MudBlazor-GitHub-NoBg.png)
# Blazor Template pre configured with MudBlazor.

[![GitHub](https://img.shields.io/github/license/garderoben/mudblazor?color=%23594ae2&style=flat-square)](https://github.com/Garderoben/MudBlazor.Templates/blob/master/LICENSE)
[![Discord](https://img.shields.io/discord/786656789310865418?color=%237289da&label=Discord&logo=discord&logoColor=%237289da&style=flat-square)](https://discord.gg/mudblazor)
[![Twitter](https://img.shields.io/twitter/follow/MudBlazor?color=1DA1F2&label=Twitter&logo=Twitter&style=flat-square)](https://twitter.com/MudBlazor)
[![Nuget version](https://img.shields.io/nuget/v/MudBlazor.Templates?color=ff4081&label=nuget%20version&logo=nuget&style=flat-square)](https://www.nuget.org/packages/MudBlazor.Templates/)
[![Nuget downloads](https://img.shields.io/nuget/dt/MudBlazor.Templates?color=ff4081&label=nuget%20downloads&logo=nuget&style=flat-square)](https://www.nuget.org/packages/MudBlazor.Templates/)

## Prerequisites

- .NET 6
- Visual Studio 2022, JetBrains Rider or VsCode 

## Getting Started
### Installation
```
dotnet new install MudBlazor.Templates
```
### Usage
```
dotnet new mudblazor --host wasm --name MyApplication
```
### Template Options
Specific template options:
| Options                 | Description                                           | Type                                                                         | Default   |
|-------------------------|-------------------------------------------------------|------------------------------------------------------------------------------|-----------|
| `-ho` \| `--host`       | Project Type                                          | `wasm` \| `wasm-hosted`<br> `wasm-pwa` \| `wasm-pwa-hosted`<br> `server`<br> | `wasm`    |
| `-s` \| `--skipRestore` | Skips the automatic restore of the project on create. | `bool`                                                                       | `false`   |

For none MudBlazor specific options run:
```
dotnet new -h
```

# New Web App Template for .NET 8

We're excited to announce the availability of a new template for .NET 8 Web Apps: the MudBlazor Web App template. This template is based on the Microsoft Web App template, but has been modified to include MudBlazor components.

To get started with this template, please ensure that you have the following installed:

1. The latest .NET 8 SDK
2. The latest Visual Studio 2022 Preview (to view the template in the list of available templates)
3. The most recent version of MudBlazor.Templates from NuGet (to access the template)

## How to Use the New .NET 8 Web App Template

### Interactive per Page
```
dotnet new mudblazorwebapp --interactivity (Auto|Server|WebAssembly)
```

### Interactive Global
```
dotnet new mudblazorwebapp --interactivity (Auto|Server|WebAssembly) --all-interactive
```

### Adding Authentication
```
dotnet new mudblazorwebapp --interactivity Auto --auth Individual
dotnet new mudblazorwebapp --interactivity Auto --auth Individual --all-interactive
```

## To Do for the .NET 8 Template

- Integrate MudBlazor components into the authentication system (currently using Bootstrap components from the original template)

### Visual Studio Templates
The templates can be used in Visual Studio as well and should show up in the list when creating a new project.
![VisualStudioTemplate](content/visual-studio-template.png)

## Default Blazor - Template
![DefaultBlazorTemplate](content/DefaultBlazorTemplate.png)
