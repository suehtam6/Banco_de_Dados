                                                                         Banco de Dados

 40% Do banco de dados vai ser modelagem.
 60% vai ser script SQL.

 A parte de modelagem possúi duas etapas

 Modelagem conceitual -> Vai ser a forma que você vai desenhar o banco
 para entender aonde ficára cada parte corretamente.

 Um bom planejamento garante um Banco mais seguro.

 Modelagem lógica -> Vai ser a ordem que você irá encaixar cada parte,
 assim fazendo ele ficar mais lógico.
 
 Um banco de dados com uma modelagem ruim, pode acabar quebrando todo o seu sistema
 e assim te dando mais trabalho no futuro para resolver o problema.


      Dados
        X
    Informação
        X
    Conhecimento

  Dados -> Os dados sempre vão estar divididos em varias áreas,
   mas sem algum significado aparente.

  Informação -> Para obter uma informação você utilizara varios dados juntos,
   assim virando uma informação.

  Conhecimento -> A analise de todos os dados juntos podem formar as informações,
  que forneceram todo o conhecimento.

  Banco de Dados -> É uma ferramenta para coletar e organizar informações.
  Pode ser armazenado dados sobre pessoas, produtos, pedidos, ou qualquer outra coisa.

  Principais software de banco de dados existentes no mercado - antigos ou pouco usados hoje em dia:
   dBase, FileMaker, FireBird, InterBase XE.

   O Banco de Dados Access mesmo sendo antigo, ainda pode ser encontrado no mercado
   com um pouco mais de facilidade.
   Access não é seguro, deve tomar bastante cuidado com ele.

   Principais software de banco de dados existentes no mercado - Atuais, livres ou com custo bem baixo:
        MySQL                PostgreSQL              MariaDB            MongoDB
          |                       |                     |                  |
        Relacional           Relacional             Relacional        Não Relacional

  Relacional -> Esse modelo utiliza conceitos como relações (tabelas),
    tuplas (linhas) e atributos (colunas) para organizar os dados de forma estruturada e consistente.

  Não Relacional -> é um sistema de armazenamento de dados que não usa o modelo tradicional de tabelas,
    linhas e colunas típico dos bancos relacionais (SQL)

      Bancos Relacionais|                      
                        |-> MySQL
                        |-> MariaDB
                        |-> ORACLE
                        |-> SQLServer
                        |-> PostgreSQL

     Bancos não Relacionas|    
                          |-> mongoDB
                          |-> cassandra
                          |-> redis
                          |-> riak
                          |-> Hbase

  Principais software de banco de dados existentes no mercado - Atuais e Pagos:
  MySQL, SQLServer e ORACLE

  SGBD -> Sistema de gerenciamento de Banco de Dados. Pode ser considerado a parte mais importante do Banco de Dados.
  Métodos de acesso do SGBD -> O SGBD tem três métodos de acesso para interagir com o banco de dados.
  DDL(Data Definition Language) -> Especificações do esquema do BD(dados e seus tipos de dados, índices, etc...) no método DDL podemos usar Create, Alter, Drop.
  Exemplo:
  Create -> Seria como criar a estrutura de uma casa.

  DML(Data Manipulation Language) -> manipulação de dados(Insert, Update, Delete, Select) processamento eficaz de consultas
  considera relacionamentos, predicados de seleção, volume de dados.

  DCL(Data Control Language) -> reponsável pelas permissões de acesso a base de dados.

  Vantagens de utilizar SGBD:

  * Rapidez na manipulação e no acesso a informação.
  * Redução de esforço humano
  * Redução de redundância e da inconsistência de informações
  * Redução de problemas da integradade

