CLI Usage Guide
===============

Backup Commands
---------------

Display backup script help:

.. code-block:: bash

   sudo -u www-data php admin/tool/brcli/backup.php --help

Execute batch backup by category:

.. code-block:: bash

   sudo -u www-data php admin/tool/brcli/backup.php --categoryid=5 --destination=/var/backups/moodle/

Restoration Commands
--------------------

Display restore script help:

.. code-block:: bash

   sudo -u www-data php admin/tool/brcli/restore.php --help

Execute batch restoration:

.. code-block:: bash

   sudo -u www-data php admin/tool/brcli/restore.php --categoryid=10 --filedir=/var/backups/moodle/
