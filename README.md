### Consolidando Arquivos .xlsx via Python


[Vídeo Apresentação](https://youtu.be/0kxkbB9noUg)

***Objetivo:*** 

Projeto desenvolvido para consolidar diversos arquivos em um diretório, com o mesmo tipo de extensão e mesmo formato de tabela. Com o objetivo de eliminar trabalhos manuais e/ou diminuir a carga em softwares de B.I., extraindo de um diretório, tratando e carregando em um banco de dados, neste caso, no *MS Access*.

***Como utlizar*** 

 Usando a mesma base, abrindo o *script* em um IDE, alterando os diretórios. O conceito é, da tabbela existente, limpa a tabela e insere novos dados consolidados com os arquivos antigos, sendo facilmente possível mudar este conceito, como: ao rodar o *script*, limpa o diretório, coloca novos arquivos a serem consolidados e incrementados no banco de dados.

***Sobre o Projeto*** 

O projeto está na versão 1. Nele, foi utilizado os softwares *MS Access* e *VS Code* como IDE para a linguagem Python. Também, envolve alguns conceitos como: lógica de programação, ETL e criação de tabelas em banco de dados.

Foi utilizado dados fictícios simples, desta forma, não foi necessário fazer tratamento nos dados antes do input no banco de dados.

##### Os Arquivos a serem tratados

No desenvolvimento do projeto foram utilizados as planilhas abaixo, contendo duas colunas: uma de texto e uma numérica.

![ArquivoTodos](https://github.com/MendesRamon/Dash_Fifa_Python/assets/141190770/c1d4b335-9082-49a6-8a69-fdbbe0624373)

##### Criação da tabela no banco de dados

A tabela foi criada para obter os dados já consolidados e limpos pelo *script*, e as colunas tratadas no ETL devem seguir a mesma tipagem dos dados. Sendo:

- coluna: *Id* (o incremento dos números são automáticos e sequênciais);
- coluna: *LETRA* (coluna com valores tipado como texto);
- coluna: *NUMERO* (coluna com valores tipado como número inteiro).

![BD_ACCESS_PROJ_CONSOLIDADOR_ARQUIVOS](https://github.com/MendesRamon/CONSOLIDANDO_ARQUIVOS_XLSX/assets/141190770/27972ce8-fd2c-4943-a79f-e4e2a82fee21)

Tabela populada após testes. Observer que os 'Ids' já não começam com o número 1, devido os testes durante o desenvolvimento, porém, seguem o conceito de *chave primária*, uma vez que foram dropados as linhas em testes anteriores.

![BD_ACCESS_PROJ_CONSOLIDADOR_ARQUIVOS - TABELA](https://github.com/MendesRamon/CONSOLIDANDO_ARQUIVOS_XLSX/assets/141190770/ea6372ba-77fc-4de7-bf53-e9cbb98636ab)



