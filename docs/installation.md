# Instalação — moodle-tool_dbmigrate

## Procedimento de Instalação

1. Clone o repositório na pasta de ferramentas de administração do Moodle:
   ```bash
   cd /caminho/do/moodle/admin/tool
   git clone https://github.com/moodle-by-kelsoncm/moodle-tool_dbmigrate.git dbmigrate
   ```
2. Execute a atualização via linha de comando:
   ```bash
   php admin/cli/upgrade.php --non-interactive
   ```
