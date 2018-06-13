# dotnet Solution

Creates a new visual studio solution including directory structure and common files.

## How to use

### Install .Core sdk version set in global.json

### Prepare a new directory for the solution and clone the source

```console
mkdir MyNewSolution
cd MyNewSolution
git init .
git remote add origin git@github.com:prospa-group/DotnetSolution.git
git pull origin master
```

### Run the setup script in a new Powershell shell

```powershell
.\run.ps1 "MyNewSolution"
```

### Use the dotnet cli to attach project templates to the solution

Prospa available templates [here](https://github.com/prospa-group/DotnetTemplates)