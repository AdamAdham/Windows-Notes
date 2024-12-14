# Windows-Notes

## Start/Restart/Stop PostgreSQL service
1. Open the "Run" dialog by pressing Win + R.
2. Type services.msc and press Enter to open the Services Manager.
3. In the Services Manager, locate the PostgreSQL service. It's usually named something like 
   "postgresql-x64-15" or similar, depending on your PostgreSQL version and architecture.
   Right-click on the PostgreSQL service and select "Stop" from the context menu.

## To check for where a version is from
```
where java
```
Outputs the paths that java is using in order of priority
