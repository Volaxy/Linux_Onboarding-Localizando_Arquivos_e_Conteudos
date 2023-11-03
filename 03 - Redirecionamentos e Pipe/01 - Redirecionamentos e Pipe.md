O sinal de `>` redireciona a saída no console para um arquivo local.

> Ex.: `grep http * > output.txt`

> Por padrão o comando sobrescreve o arquivo caso ele exista, para evitar esse comportamento, deve-se colocar `>>` ao invés de `>`, para se realizar um *append* no conteúdo do arquivo

O caractere `|` executa uma cadeia de comandos em sequência, em que a saída do 1º comando é o parâmetro de entrada do 2º comando e assim sucessivamente.

> Ex.: `cat /etc/services | grep http > output.txt`

O comando `sort` ordena a saída em ordem crescente por padrão em ordem alfabética.