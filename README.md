Olá, bem-vindo ao mini solução de ETL. Desenvolvido em SSIS.

Neste foi planejado a importação de dados em que o caminho e nome do arquivo sãoo variáveis iniciar.

Além dos parâmetros, é previsto ainda um tratamento de exceção que venha a ocorrer no arquivo. 
Este faz a inserção dos mesmos registros que incidiram o erro para uma outra tabela, com maior nível de tolerancia de inconformidade, 
no caso, importa os dados sem utilizar o parâmetro de separação por delimitador e, no decorrer do fluxo, insere nesta mesma tabela os detalhes do respectivo erro.

--Para fins de registro pessoal. O ETL foi produzido com 15 dias de estudo nas documentações e youtube. 
