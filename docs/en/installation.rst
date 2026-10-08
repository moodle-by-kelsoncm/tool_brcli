Installation
============

Step by Step
------------

1. Navigate to your Moodle installation's administrative tools directory:

   .. code-block:: bash

      cd /path/to/moodle/admin/tool

2. Clone the repository naming the folder `brcli`:

   .. code-block:: bash

      git clone https://github.com/moodle-by-kelsoncm/tool_brcli.git brcli

3. Run the Moodle CLI upgrade script:

   .. code-block:: bash

      php admin/cli/upgrade.php --non-interactive
