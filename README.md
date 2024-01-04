# bug-free-dollop
[C#] (Microsoft AZ-204 certification) Exercise: Create resources by using the Microsoft .NET SDK v3

# Notes
[https://learn.microsoft.com/en-us/training/modules/work-with-cosmos-db/3-exercise-work-cosmos-db-dotnet](https://learn.microsoft.com/en-us/training/modules/work-with-cosmos-db/3-exercise-work-cosmos-db-dotnet)

# Commands
* az login;
* az group create --location UKSouth --name az204-cosmos-rg;
* az cosmosdb create --name bugfreedollop --resource-group az204-cosmos-rg;
* az cosmosdb keys list --name bugfreedollop --resource-group az204-cosmos-rg;
