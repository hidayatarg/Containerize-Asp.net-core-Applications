## Pull Image

```docker run -e "ACCEPT_EULA=Y" -e "SA_PASSWORD=ProductApi(!)" -e "MSSQL_PID=Express" -p 1433:1433 --name=catalogdb microsoft/mssql-server-linux```



Apply Migration

```dotnet ef migrations add  InitialMigration -o Data/Migrations```
