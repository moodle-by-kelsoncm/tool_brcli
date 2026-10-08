Instalação
==========

Passo a Passo
-------------

1. Acesse o diretório de ferramentas administrativas do Moodle:

   .. code-block:: bash

      cd /caminho/do/moodle/admin/tool

2. Clone o repositório nomeando a pasta como `brcli`:

   .. code-block:: bash

      git clone https://github.com/moodle-by-kelsoncm/tool_brcli.git brcli

3. Execute o script de upgrade via linha de comando do Moodle:

   .. code-block:: bash

      php admin/cli/upgrade.php --non-interactive
