Visão Geral - moodle-tool_brcli
===============================

O **moodle-tool_brcli** (**BrCLI - Backup & Restore Command-Line Interface**) é um plugin de ferramenta administrativa (`admin/tool`) para o Moodle que permite realizar backups e restaurações em lote de **categorias completas de cursos** via linha de comando.

Recursos Principais
-------------------

- **Backup em Lote por Categoria**: Executa o backup de todos os cursos pertencentes a uma categoria específica com um único comando.
- **Restauração em Lote**: Restaura um conjunto de arquivos de backup `.mbz` em uma categoria de destino definida.
- **Integração CLI Nativa**: Opera em segundo plano via PHP CLI sem estourar limites de timeout do navegador web.

Documentação
------------

.. toctree::
   :maxdepth: 2
   :caption: Conteúdo:

   installation
   configuration
   usage
