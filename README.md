# <img src="https://raw.githubusercontent.com/prospa-group/DotnetPackaging/master/prospa60x60.png" alt="Prospa Engineering" width="50px"/> Prospa DotNet Solution 

Creates a new visual studio solution including directory structure and common files.

## How to use

#### Install the .NET Core SDK

The .NET Core SDK version specified in `global.json` will need to be [installed](https://www.microsoft.com/net/download/dotnet-core/).

#### Prepare a new directory for the solution and clone the source

```console
git clone git@github.com:prospa-group/DotnetSolution.git MyNewSolution
```

#### Run the setup script in a new Powershell shell

```powershell
cd MyNewSolution
.\run.ps1 "MyNewSolution"
```

#### Use the dotnet cli to attach project templates to the solution

Prospa available templates [here](https://github.com/prospa-group/DotnetTemplates)
