Guia de Uso CLI
===============

Comandos de Backup
------------------

Exibir ajuda do script de backup:

.. code-block:: bash

   sudo -u www-data php admin/tool/brcli/backup.php --help

Executar backup em lote por categoria:

.. code-block:: bash

   sudo -u www-data php admin/tool/brcli/backup.php --categoryid=5 --destination=/var/backups/moodle/

Comandos de Restauração
-----------------------

Exibir ajuda do script de restauração:

.. code-block:: bash

   sudo -u www-data php admin/tool/brcli/restore.php --help

Executar restauração em lote:

.. code-block:: bash

   sudo -u www-data php admin/tool/brcli/restore.php --categoryid=10 --filedir=/var/backups/moodle/
