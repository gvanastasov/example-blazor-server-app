# example-blazor-server-app
 A simple demo app showcasing a server app built with blazor.

## How
1. Generate solution via template
```ssh
dotnet new sln -n ExampleBlazorServerApp
```
2. Generate blazor project
```ssh
# create project dir
mkdir src/ExampleBlazorServerApp

# navigate to project dir
cd src/ExampleBlazorServerApp

# generate .csproj
dotnet new blazorserver

# add .csproj to sln
dotnet sln ExampleBlazorServerApp.sln add src/ExampleBlazorServerApp/ExampleBlazorServerApp.csproj
```

> at this point you might need to restart your IDE if it did not trigger refresh on your plugins (like for example in vscode)
