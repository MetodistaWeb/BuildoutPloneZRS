# BuildoutPloneZRS
Modelo de pacote base de buildout de Plone com ZeoServer com ZRS (ZODB Replicated Storage).

Mais informações sobre ZeoServer e ZRS em: https://pypi.python.org/pypi/plone.recipe.zeoserver/

**Funcionalidades:**

* Buildout de desenvolvimento com checkout, homologação e produção;
* Centralização de configurações em arquivo buildout.d/settings.cfg - com adição de ZRS em produção e homologação;
* Configuração para ZRS com Data.fs e blobstorage específicos em portas diferentes do ZeoServer para Replicação;
* Substituição dos arquivos de configuração ZRS com base nos arquivos de configuração;
* Aplicação dos Patches de Segurança.

**Versionamentos:**

* Plone na versão 4.3.9;
* Versionamento geral em arquvo buildout.d/versions.cfg mantido em quantidade mínima para compatibilidade com Plone 4.x.
* Requisição para produtos Metodista:
* metodista.site.educacaosuperior
* metodista.site.tema
* metodista.site.portlets
