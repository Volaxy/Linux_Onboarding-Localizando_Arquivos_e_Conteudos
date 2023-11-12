Para abrir um arquivo usando o editor de texto ***Nano***, usa-se o comando `nano FILE_NAME`.

Caso o comando seja somente `nano`, o **Linux** cria um novo arquivo de texto usando o editor ***Nano***.

O comando `vi` faz entrar no editor de textos do ***VI***.

Para executar um comando, basta digitar `:` seguido do nome do comando que deve ser executado.
* `:q`: Sai do editor do ***VI***.
* `:w`: Salva as modificações no arquivo e continua editando o arquivo no editor do **VI**.

Para voltar alternar entre os modos, usa-se o botão **ESC** para alternar entre comandos e edição de texto.

# Modos

## Navegação

Por padrão, o editor entra neste modo, onde é possível digitar os comandos e navegar pelo arquivo sem modifica-lo.

Um atalho para apagar uma linha é digitar a tecla **d** 2x seguidas.

Para apagar uma série de linhas, digite o número de linhas que se quer apagar de uma vez, depois digite **dd**.

> Ex.: 11dd - Apaga 11 linhas a partir de onde o cursor do editor está

Para navegar para uma linha específica, digite `:` seguido do número da linha.

Para voltar ao início do arquivo, digite **gg**.

Para ir ao final do arquivo, digite **G**.

Para pesquisar uma string dentro do arquivo, digite "/" seguido da string que se quer buscar.

Para copiar uma linha, digite **yy**. Para colar, digite **p** para colar depois, e **P** para colar antes.

## Inserção

Para inserir um texto dentro do editar, basta apertar a tecla **i**, para entrar no modo de inserção.

> Caso seja inserido um texto e queira sair do editor sem aplicar as alterações, basta apertar a tecla **ESC** para sair do modo de inserção, e depois digitar o comando `:q!`, o `!` nesse caso faz o **VI** não salvar as alterações feitas no arquivo.

Para salvar as alterações feitas, digite o comando `:x`.

## Substituição

Para substituir caracteres no texto através do editor, aperte a tecla **r**, caso seja digitado um caractere, a tecla pressionada irá substituir o caractere onde o curso do editor estiver.