Tipos de armazenamento do Azure:
* Blob do azure: armazenamento de dados massivos não estruturados como texto ou binários. Usado para armazenar arquivos de mídia ou documentos de um site.
* Disco do azure: fornece disco de armazenamento para máquinas virtuais, aplicativos ou serviços.
* Fila do azure: serviço de armazenamento de mensagens que fornece armazenameno e recuperação de mensagens de ate 64KB.
* Arquivos do azure: usado para compartilhamento de arquivos de rede que requer alta disponibilidade usando protocolo SMB.
* Tabelas do azure: usado para armazenamento de dados estruturados não relacionais que utiliza opção de chave/valor

## Camadas de armazenamento
* Camada quente – uma camada online otimizada para armazenar dados acessados ou modificados com frequência. A camada quente tem os custos de armazenamento mais altos, mas os custos de acesso mais baixos.
* Camada fria – uma camada online otimizada para armazenar dados acessados ou modificados com pouca frequência. Os dados na camada de acesso esporádico devem ser armazenados por um mínimo de 30 dias. A camada fria tem custos de armazenamento mais baixos e custos de acesso mais altos em comparação com a camada quente.
* Camada de acesso frio: uma camada online otimizada para armazenar dados acessados ou modificados com pouca frequência, mas que ainda exigem uma recuperação rápida. Os dados na camada acesso frio devem ser armazenados por um mínimo de 90 dias. A camada de acesso frio tem custos de armazenamento mais baixos e custos de acesso mais altos em comparação com a camada de acesso esporádico.
* Camada de arquivos: uma camada offline otimizada para armazenar dados acessados raramente e com requisitos de latência flexíveis, na ordem de horas. Os dados na camada de arquivos devem ser armazenados por um mínimo de 180 dias.

## Migração

- AZCOPY
Um utilitário de linha de comando que permite copiar blobs ou arquivos para uma conta de armazenamento.

- Gerenciador de armazenamento do azure
Aplicativo com interface gráfica que usa os comandos do azcopy para migrar arquivos para um storage do azure.

- Sincronização de arquivos do Azure
Sincroniza arquivos locais e arquivos no azure. Diferente do azcopy ele faz envios bidirecionais de arquivos.