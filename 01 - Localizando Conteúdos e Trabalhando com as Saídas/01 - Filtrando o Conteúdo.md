O arquivos onde mostra os serviços do sistema está localizado em */etc/services*.

O comando `cat FILE_NAME` mostra o conteúdo de um arquivo no terminal.

O comando `grep STRING FILES` busca por uma string especificada no 2º parâmetro, e busca nos arquivos especificados pelo 3º parâmetro.
* `-i`: Ignora o case-sensitive na busca, procurando tanto por ocorrências que estejam em minúsculas quanto em MAIÚSCULAS.
* `-l`: Retorna somente os **arquivos** onde o conteúdo está.
* `-L`: Retorna somente os **arquivos** em que o conteúdo não está incluido.
* `-r`: Faz uma busca recursiva nos arquivos dentro dos diretórios caso estejam presentes.

> Ex.: `grep http *`: Busca pela string *http* em todos os arquivos no diretório atual.

O arquivo presente em */etc/passwd* é uma base de dados local que armazena os usuários do sistema.