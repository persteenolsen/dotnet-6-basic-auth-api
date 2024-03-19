# dotnet-6-basic-auth

.NET 6.0 - Basic HTTP Authentication API

# Functionality of the Web App

- BASIC HTTP authentication

# Tech used for creating the Web App

- A .NET 6 Web API
- A Blazor Webassembly Web Client for the frontend
- A Vue 3 Client for the Frontend
- A traditional Webhotel for hosting
- VS Code

# Development

dotnet run

# Production

Create a self contained build for production at the remote server / traditionel web hotel

dotnet publish webapi.csproj --configuration Release --runtime win-x86 --self-contained

Upload the build to remote server

At my remote servers the web.config needs to be without the folowing:

hostingModel="inprocess"



