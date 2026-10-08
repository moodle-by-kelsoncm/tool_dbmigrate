Guia de Execução CLI
====================

Comando de Ajuda
----------------

.. code-block:: bash

   php admin/tool/dbmigrate/cli/migrate.php --help

Execução da Migração
--------------------

.. code-block:: bash

   php admin/tool/dbmigrate/cli/migrate.php \
     --dbtype=pgsql \
     --dbhost=localhost \
     --dbname=moodle_pg \
     --dbuser=moodleuser \
     --dbpass=segredo
