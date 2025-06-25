
 Locadora de Veículos - Projeto de Banco de Dados em MySQL

 Descrição

Este projeto consiste na modelagem e implementação de um banco de dados relacional para uma locadora de veículos, utilizando MySQL. Inclui a criação das tabelas principais, inserção de dados exemplares e consultas para gestão de clientes, veículos, manutenções, locações e pagamentos.

 Funcionalidades

- Cadastro de clientes, veículos e manutenções  
- Registro de locações e pagamentos  
- Controle de status dos veículos (disponível, alugado, manutenção)  
- Consultas para relatórios gerenciais:
  - Total arrecadado  
  - Veículos mais alugados  
  - Clientes com pagamentos pendentes  
  - Histórico de manutenções  

 Estrutura do Banco

Principais tabelas:  
- `cliente`  
- `veiculo`  
- `manutencao`  
- `locacao`  
- `pagamento`  
- `locacaoveiculo` (tabela de relacionamento entre locações e veículos)

 Como usar

1. Importe o arquivo `banco_locadora.sql` no seu ambiente MySQL.  
2. Execute os comandos para criar o banco, tabelas, inserir os dados e realizar consultas.  
3. Utilize as queries disponibilizadas para gerar relatórios e análises.

 Tecnologias

- MySQL  
- SQL padrão  

 Feitor por

Arthur Yan Oliveira Silva


