[![NuGet](https://img.shields.io/nuget/v/dotnet-pr.svg)](https://www.nuget.org/packages/dotnet-pr/)
[![NuGet](https://img.shields.io/nuget/dt/dotnet-pr.svg)](https://www.nuget.org/packages/dotnet-pr/)

## dotnet-pr


This a .NET Core Global Tool that ..

1) Given your terminals working directory is a git repo
2) And that git repo has a remote that is a code collaboration tool (ex. GitHub, BitBucket/Stash)
3) Opens your default browser in Pull Request UI for the _current branch_ in the tool connected to the remote branch.

## Install

```
$ dotnet tool install dotnet-pr -g
``` 

## Usage

After install, navigate to a git repo and just call `pr` from the terminal