O comando `wc` mostra informações sobre a saída gerada (usado em combinação com `|` na maioria das vezes, com comandos executados anteriormente):
* Total de linhas.
* Total de palavras.
* Tamanho em ***bytes***.

O comando `cut -d "?" -f1,?,...` separa as strings pelo delimitador passado como parâmetro.
* `-d`: Especifica qual vai ser a string que vai ser usada como critério de separação.
* `-fn`: Especifica qual campo será retornado na saída, onde *n* é o número do campo que será mostrado. É possível incluir mais colunas separando por `,`.
> Ex.: `-f1,2,3,...`

> Ex.: `-f1-4`: Mostra os campos de 1 a 4

> Ex.: `-f4-`: Mostra todos os campos a partir do campo 4

> Ex.: `-f1-2,4-`: Mostra da coluna 1 a 2, e depois da 4 em diante