Instalação
==========

Procedimento de Instalação
--------------------------

1. Clone o repositório na pasta de ferramentas de administração do Moodle:

   .. code-block:: bash

      cd /caminho/do/moodle/admin/tool
      git clone https://github.com/moodle-by-kelsoncm/tool_dbmigrate.git dbmigrate

2. Execute a atualização via linha de comando:

   .. code-block:: bash

      php admin/cli/upgrade.php --non-interactive
