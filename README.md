# Demo of Vault Agent Injector to connect to Microsoft SQL Server

## Environment variables
MSSQL_CONNECTION_STRING=jdbc:sqlserver://<database IP address>:1433;databaseName=<database name>;encrypt=false;
MSSQL_DB_USERNAME=<database username> - it will be shown on the API response
MSSQL_DB_PASSWORD=<database password> - it will be shown on the API response
LDAP_USERNAME=<LDAP username> - it will be shown on the API response
LDAP_PASSWORD=<LDAP password> - it will be shown on the API response

## API Endpoint
http://<hostname>/api/v1/companies
