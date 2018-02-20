# Cake example repository

This repository is based on the minimal example of using the [Cake build system](https://cakebuild.net)

You can read more in the Cake [Getting Started guide](https://cakebuild.net/docs/tutorials/getting-started).

# What Does this demo do?
It uses the offical Cake Build Tool example which was built apon. This example demonstrates the following
- Clean
- Restore Nuget
- Build
- Run Tests (using Nunit)
- Nuget package (to Nupkg)


# Run The Build
1. Open PowerShell window as Administrator
2. Issue this command in PowerShell : Set-ExecutionPolicy -Scope Process -ExecutionPolicy Bypass
3. Change to the correct directory with the .cake file in it, and issue this command : .\build.ps1
4. You should see some output, where it eventually completes
5. You should also see a tools folder


# To Publish the Nuget
1. Open PowerShell window as Administrator
2. Issue this command in PowerShell : Set-ExecutionPolicy -Scope Process -ExecutionPolicy Bypass
3. Issue this command in PowerShell : .\build.ps1 -Target Package



