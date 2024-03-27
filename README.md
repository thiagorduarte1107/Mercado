Descrição: O projeto "Mercado" é uma aplicação de console desenvolvida em Java, simulando um sistema de gerenciamento para mercados que permite operações como cadastro, listagem, compra de produtos, e visualização do carrinho de compras. O projeto visa aplicar conceitos avançados de programação, padrões de projeto, e interação com banco de dados.

Tecnologias e Padrões Utilizados:

Java: Linguagem de programação principal, aplicando conceitos de orientação a objetos para a estruturação do projeto.
SQLite: Utilizado como sistema de gerenciamento de banco de dados relacional para armazenar informações dos produtos e transações, facilitando operações de CRUD (Criar, Ler, Atualizar, Deletar) com simplicidade e eficiência.
JDBC (Java Database Connectivity): API utilizada para conectar a aplicação Java ao banco de dados SQLite, permitindo a execução de consultas SQL e manipulação dos dados.
Padrão DAO (Data Access Object): Empregado para separar a lógica de acesso ao banco de dados da lógica de negócios, ilustrado pelo uso da classe ProdutoDAO.
Transações de Banco de Dados: Gerenciamento de transações para garantir a consistência dos dados, especialmente em operações de compra, aplicando conn.setAutoCommit(false);, conn.commit(); e conn.rollback(); para operações atômicas.
Padrões SQL: Utilização de SQL para operações de banco de dados, incluindo a criação de tabelas, inserção, atualização, consulta e listagem de registros.
Tratamento de Exceções: Implementação de tratamento adequado de SQLExceptions, garantindo que a aplicação possa gerenciar erros de banco de dados de forma eficiente.
Optional API: Aplicação da classe Optional do Java 8 para encapsular resultados que podem ou não existir, demonstrando práticas modernas de programação Java.
Gerenciamento de Conexões: Uso cuidadoso de conexões com o banco de dados, empregando o padrão try-with-resources para abertura e fechamento adequado de conexões, evitando vazamentos de recursos.
Contribuições Pessoais:

Desenvolvi integralmente a lógica de negócios utilizando Java, aplicando padrões de design de software para garantir a modularidade e manutenibilidade do código.
Implementei a interação com o banco de dados SQLite usando JDBC, incluindo o design de tabelas e execução de operações de CRUD para gerenciamento de produtos.
Apliquei práticas de segurança na área administrativa através de um sistema de autenticação simplificado, protegendo a gestão de produtos.
