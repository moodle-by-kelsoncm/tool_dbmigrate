# Guia de Execução — moodle-tool_dbmigrate

## Comando de Ajuda
```bash
php admin/tool/dbmigrate/cli/migrate.php --help
```

## Execução da Migração
```bash
php admin/tool/dbmigrate/cli/migrate.php \
  --dbtype=pgsql \
  --dbhost=localhost \
  --dbname=moodle_pg \
  --dbuser=moodleuser \
  --dbpass=segredo
```
