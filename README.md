# database-experience-no-sql-dio

##O que é um banco de dados relacional?

São os bancos que normalmente estão normalizados, 
que garante um esquema sem duplicidade, 
com esquema de dados rígidos, 
onde se tem bastante relacionamento entre tabelas.
Banco que garante a integridade integridade dos dados.

Como temos um esquema forte, as consultas de dados se tornam relativamente simples, já que você sempre vai receber o esquema por completo.

###Exemplos: MySQL, PostgreSQL, SQL Server.

##O que é um banco NoSQL?

É uma alternativa a bancos relacionais, 
os bancos NoSQL não estão aqui para substituir os bancos relacionais.
No momento surgiu a necessidade de armazenar dados não estruturados e que fossem escaláveis, surgiu o NoSQL.
Como o volume de dados que um banco NoSQL consegue armazenar é gigante, sem crescer tanto (MB/GB) a escalabilidade horizontal desse modelode banco é bem viável.

Um ponto de atenção no uso de bancos NoSQl é a definição das chaves, já que não temos a garantia que os dados estarão dentro do mesmo esquema/padrão, precisamos ter alguma forma de consulta.

###Exemplos: MongoDB, DynamoDB, Redis.

##Casos de uso:

##Bancos Relacionais:

Um bom exemplo de uso é em um Ecommerce, onde temos ali a estrutura do pedido, que precisar ser estruturado, que se relaciona com outras tabelas, como cadastro do cliente, condições de pagamento, estoque e etc.
Um outro exemplo seria as transações financeiras, teríamos um caos generalizado no dia a dia dos bancos sem um esquema de dados rígido no dia a dia.

##Bancos NoSQL:

Podem ser utilizados quando precisamos de alto armazenamento juntamente com performance, ou quando precisamos de escalabilidade horizontal.
Suporte nativo a replicação também é um bom fator na escolha de uso do NoSQL.
Quando precisamos de algum tipo de cache, com armazenamento chave-valor por exemplo, o NoSQL é uma excelente escolha.

Também vejo o NoSQL como uma ótima alternativa para cadastros auxiliares que não precisam se relacionar diretamente com outros tipos de dados, por exemplo um cadastro de municípios onde precisamos armazenar apenas nome de código do IBGE.

