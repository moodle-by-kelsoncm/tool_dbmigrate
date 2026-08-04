# Configuração — moodle-tool_dbmigrate

## Pré-requisitos para Migração

1. Criar o banco de dados de destino (ex: PostgreSQL) com encoding UTF-8.
2. Certificar-se de que os drivers PHP de origem (ex: `pdo_mysql` / `mysqli`) e destino (ex: `pdo_pgsql` / `pg_sql`) estão habilitados no PHP CLI.
