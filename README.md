# Actions and WorkFlow (continuous integration)
This repository tests Github Workflow that is continuous integration (CI) with a .NET 5 console application with a related Test project

## Procedure
Inside Github go to Action and: 
```
Create New Workflow > Choose .NET Template
```
At your local PC do following: 
```
- Clone this repo to local PC
- Inside VScode create .net 5.0 project: `dotnet new console --framework net5.0`
- Commit and push changes. 
- The workflow will be triggered on the Push event. 
```
