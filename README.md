# Sistema de Gerenciamento Escolar - Java

Este projeto é um sistema simples de gerenciamento escolar utilizando **Java** e **JDBC**. Ele gerencia as informações de **Alunos**, **Professores** e **Turmas** em um banco de dados MySQL.

## Funcionalidades
- **CRUD de Alunos**: Criação, leitura e exclusão de registros de alunos.
- **CRUD de Professores**: Criação, leitura e exclusão de registros de professores.
- **CRUD de Turmas**: Criação e leitura de turmas.

## Estrutura do Projeto
O projeto é dividido em várias camadas:
- **Model**: Classes que representam as entidades (`Aluno`, `Professor`, `Turma`).
- **DAO**: Classes responsáveis pela comunicação com o banco de dados (uso de `JDBC` para operações como `INSERT`, `SELECT`, `DELETE`).
- **Connection**: Gerencia a conexão com o banco de dados MySQL.

## Como Rodar
1. **Clone o repositório**:
   ```bash
   git clone https://github.com/4L3M40/SabadoImersao.git

   Considerações Finais
Este sistema permite gerenciar dados de alunos, professores e turmas de forma simples, com conexão direta ao banco de dados. Ele pode ser facilmente expandido para incluir outras funcionalidades, 
como a atualização de registros ou integração com interfaces gráficas.

    Descrição
Projeto desenvolvido como parte de um exercício para aprender conceitos de Java, JDBC e manipulação de banco de dados.
