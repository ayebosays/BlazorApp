# Blazor app

## Create your app
```bash
dotnet new blazorserver -o Blazorapp --no-https
```
- command creates your new **Blazor app** project and places it in a new directory called **BlazorApp** inside your current location.
- Navigate to the new **BlazorApp** directory created by the previous command

```bash
cd BlazorApp
```
- **Program.cs** entry point for the app that starts the server.
  
- **Startup.cs** where you configure the app services and middleware


- **App.razor** root componenet for app


- **BlazorApp/Pages** directory contains some example web pages for the app


- **BlazorApp/csproj** defines the app project and its dependencies


## Run your app
```bash
dotnet watch run
```
- command will build and start the app, and then rebuild and restart the app whenver you made code changes.
- App will listen on **http://localhost:5000**



## Directory
```bash
├── App.razor
├── appsettings.Development.json
├── appsettings.json
├── bin
│   └── Debug
│       └── net5.0
│           └── ref
├── BlazorApp.csproj
├── Data
│   ├── WeatherForecast.cs
│   └── WeatherForecastService.cs
├── _Imports.razor
├── obj
│   ├── BlazorApp.csproj.nuget.dgspec.json
│   ├── BlazorApp.csproj.nuget.g.props
│   ├── BlazorApp.csproj.nuget.g.targets
│   ├── Debug
│   │   └── net5.0
│   │       ├── BlazorApp.AssemblyInfo.cs
│   │       ├── BlazorApp.AssemblyInfoInputs.cache
│   │       ├── BlazorApp.assets.cache
│   │       ├── BlazorApp.csproj.AssemblyReference.cache
│   │       ├── BlazorApp.GeneratedMSBuildEditorConfig.editorconfig
│   │       └── ref
│   ├── project.assets.json
│   └── project.nuget.cache
├── Pages
│   ├── Counter.razor
│   ├── Error.cshtml
│   ├── Error.cshtml.cs
│   ├── FetchData.razor
│   ├── _Host.cshtml
│   └── Index.razor
├── Program.cs
├── Properties
│   └── launchSettings.json
├── README.md
├── Shared
│   ├── MainLayout.razor
│   ├── MainLayout.razor.css
│   ├── NavMenu.razor
│   ├── NavMenu.razor.css
│   └── SurveyPrompt.razor
├── Startup.cs
├── tree.txt
└── wwwroot
    ├── css
    │   ├── bootstrap
    │   │   ├── bootstrap.min.css
    │   │   └── bootstrap.min.css.map
    │   ├── open-iconic
    │   │   ├── font
    │   │   │   ├── css
    │   │   │   │   └── open-iconic-bootstrap.min.css
    │   │   │   └── fonts
    │   │   │       ├── open-iconic.eot
    │   │   │       ├── open-iconic.otf
    │   │   │       ├── open-iconic.svg
    │   │   │       ├── open-iconic.ttf
    │   │   │       └── open-iconic.woff
    │   │   ├── FONT-LICENSE
    │   │   ├── ICON-LICENSE
    │   │   └── README.md
    │   └── site.css
    └── favicon.ico
```

