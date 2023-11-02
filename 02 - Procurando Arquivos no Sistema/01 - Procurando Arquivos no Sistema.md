O comando `find DIRECTORY -name FILE_NAME` procura pelos arquivos especificando o diretório onde deve ser feito a busca, e passando como parâmetro na opção `-name` o nome do arquivo.
* `-iname`: Ignora o case sensitive no nome do arquivo.
* `-max-depth n`: Define o números de subpastas que devem ser acessadas a partir do diretório especificado.
* `-amin -n`: Mostra os arquivos que foram criados nos últimos *n* minutos.
* `-atime -n`: Mostra os arquivos que foram criados nos últimos *n* dias.
* `-size +n`: Mostra os arquivos que tem mais do que *n* de tamanho (o tamanho pode ser definido com uma letra após o *n*).

> Caso o `+` seja retirado, o sistema procura por arquivos com exatamente o tamanho especificado

> Alguns diretórios no sistema precisam de permissão de super usuário para poderem ser acessados, caso a busca tivesse sido no `/`, algumas pasta estariam com permissão negada, para poder acessar essas pasta o comando deve estar precedido da palavra **`sudo`**.

O comando `ls -lh` mostra os dados dos arquivos em formato de leitura humana.