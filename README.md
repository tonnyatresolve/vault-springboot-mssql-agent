# Demo of Vault Agent Injector to connect to Microsoft SQL Server

## Environment variables
MSSQL_CONNECTION_STRING=jdbc:sqlserver://[database IP address]:1433;databaseName=[<]database name];encrypt=false;<br />
MSSQL_DB_USERNAME=[database username] - it will be shown on the API response<br />
MSSQL_DB_PASSWORD=[database password] - it will be shown on the API response<br />
LDAP_USERNAME=[LDAP username] - it will be shown on the API response<br />
LDAP_PASSWORD=[LDAP password] - it will be shown on the API response<br />

## API Endpoint
http://[hostname]/api/v1/companies