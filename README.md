# Jira Docker Compose
JIRA Docker Compose File with a Microsoft SQL Server DB.

## Usage
*Change the password* in the compose file, and `docker-compose up` then configure initial setup on port 8080. Select "Manual Configuration" and when asked about database, use the following values:
```
Database Type: Microsoft SQL Server
Hostname: mssql
Database: jira
Username: sa
Password: YOUR PASSWORD
```

That should be about it.
