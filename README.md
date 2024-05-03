
Hostname/address: data-pipeline-db
Port: 5432
Maintenance database: POSTGRES_DB(testing)
Username: POSTGRES_USER
Password: POSTGRES_PASSWORD

SELECT * FROM pg_available_extensions WHERE installed_version IS NOT NULL;

CREATE EXTENSION IF NOT EXISTS pldbgapi;
