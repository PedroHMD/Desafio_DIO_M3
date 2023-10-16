# Desafio_DIO_M3
- Verifique os cabeçalhos e tipos de dados

- Modifique os valores monetários para o tipo double preciso

- Verifique a existência dos nulos e analise a remoção

- Os employees com nulos em Super_ssn podem ser os gerentes. Verifique se há algum colaborador sem gerente

- Verifique se há algum departamento sem gerente

- Se houver departamento sem gerente, suponha que você possui os dados e preencha as lacunas

- Verifique o número de horas dos projetos

- Separar colunas complexas

- Mesclar consultas employee e departament para criar uma tabela employee com o nome dos departamentos associados aos colaboradores. A mescla terá como base a tabela employee. Fique atento, essa informação influencia no tipo de junção

- Neste processo elimine as colunas desnecessárias.

- Realize a junção dos colaboradores e respectivos nomes dos gerentes . Isso pode ser feito com consulta SQL ou pela mescla de tabelas com Power BI. Caso utilize SQL, especifique no README a query utilizada no processo.

- Mescle as colunas de Nome e Sobrenome para ter apenas uma coluna definindo os nomes dos colaboradores

- Mescle os nomes de departamentos e localização. Isso fará que cada combinação departamento-local seja único. Isso irá auxiliar na criação do modelo estrela em um módulo futuro.

- Explique por que, neste caso supracitado, podemos apenas utilizar o mesclar e não o atribuir:

  Ao fazer a mesclagem o powerBI funciona semelhante a um join juntando os dados em colunas com as correspondências encontradas. Ao usar o "Atribuir" ele faz a concatenação das linhas acarretando em junção desestruturada.
