Configuration & Prerequisites
=============================

Migration Prerequisites
-----------------------

1. Create the destination database (e.g. PostgreSQL) using UTF-8 character encoding.
2. Ensure that both source (e.g. `pdo_mysql` / `mysqli`) and destination (e.g. `pdo_pgsql` / `pgsql`) PHP database drivers are enabled in the PHP CLI runtime.
