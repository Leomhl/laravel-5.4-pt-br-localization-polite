# Arquivos de linguagem do Laravel 5.4 - Português do Brasil versão "educada"

Essa tradução foi criada a partir do conteúdo disponibilizado neste repositório:
https://github.com/Leomhl/laravel-5.4-pt-br-localization

## Instalação

1. Clonar este projeto para uma pasta dentro de `resources/lang/`
  ```
  $ cd resources/lang/
  $ git clone https://github.com/Leomhl/laravel-5.4-pt-br-localization-polite.git ./pt-br
  ```
  
  Você pode remover o diretório .git para poder incluir e versionar os arquivos deste projeto no seu repositório.

  ```
  $ rm -r pt-br/.git/
  ```
  
2. Configurar o Framework para utilizar a linguagem como Default
  ```
  // Linha 80 do arquivo config/app.php
  'locale' => 'pt-br',
  ```
