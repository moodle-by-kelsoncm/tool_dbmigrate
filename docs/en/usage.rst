CLI Execution Guide
===================

Help Command
------------

.. code-block:: bash

   php admin/tool/dbmigrate/cli/migrate.php --help

Running the Migration
---------------------

.. code-block:: bash

   php admin/tool/dbmigrate/cli/migrate.php \
     --dbtype=pgsql \
     --dbhost=localhost \
     --dbname=moodle_pg \
     --dbuser=moodleuser \
     --dbpass=secret
