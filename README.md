# Template for a Blazor Hosted Application

This project contains a template for a blazor hosted web app with integrated authentication.

## Layers
- Blazor UI
- Server (Asp.Net WebApi)
- Service layer
- Data layer
- UI tests
- Unit tests
- Integration tests

# Install

`git clone https://...`

`cd .\Blazor-hosted-template`

`dotnet new -i .\`

# Create new project

`mkdir MyNewAwesomeProject`

`cd .\MyNewAwesomeProject`

`dotnet new blazorhostedcomplete -n MyNewAwesomeProject`


# Run sql server locally with docker

## First time install
`docker run -e 'ACCEPT_EULA=Y' -e 'SA_PASSWORD=Root1234' -p 1434:1434 -d --name _BlazorHostedCompleteSqlServer mcr.microsoft.com/mssql/server:2017-latest`

## Start the container 
`docker start _BlazorHostedCompleteSqlServer`
