No comando `grep`, caso seja passado o parâmetro `-E` é colocado entre `""` a expressão regular para pesquisa. Um atalho para esse tipo de situação  é o comando `egrep "?"` que também passa uma expressão regular como critério de busca.

> Ex.: `grep -E "*sgi*"`: Pesquisa todas as ocorrências que contenham "sgi"
* `^...`: Começam com ...
* `...$`: Terminam com ...
* `|`: Uma ou outra ocorrência.
> Ex.: `grep -E "computer|phone"`: Busca por "computer" ou "phone".
* `^.test`: Começam com qualquer caractere seguido da palavra "test".