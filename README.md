# Repositório de Projetos de Banco de Dados

Este repositório contém os projetos e exercícios desenvolvidos para a disciplina de **Banco de Dados**. Cada pasta representa um trabalho ou conjunto de scripts SQL, organizados para demonstrar a aplicação prática dos conceitos aprendidos em sala de aula.

## Estrutura do Repositório

- **`Projeto-Livraria`**: Contém o script SQL para a criação e manipulação do banco de dados de uma livraria.
  - **`CREATE DATABASE livraria`**: Script inicial para criar o banco de dados e as tabelas, definindo chaves primárias e relacionamentos.
  - **`livraria2.txt`**: Versão mais completa que inclui `Constraints` como `UNIQUE`, `DEFAULT`, `CHECK` e `ENUM`, além de dados de exemplo para `autor`, `editora`, `financiador`, `livro`, `cliente` e `pedido`.
  - **`BancoDeDados_livraria-27-09-24.txt`**: Script que cria um banco de dados de livraria com tabelas para `pedido`, `cliente`, `livro`, `editora`, `autor` e `financiador`, além de `INSERT`s com dados de exemplo.

- **`Projeto-Estacionamento`**: Scripts para o banco de dados de um sistema de estacionamento, demonstrando o uso de `JOIN`s.
  - **`EstacionamentoTutoria-JOIN-INNER-RIGHT.txt`**: Criação de um banco de dados para um estacionamento, incluindo tabelas para `cliente`, `categoria`, `veiculo` e `estacionamento`. O script mostra a utilização de `INNER JOIN` para combinar dados de `veiculo`, `categoria` e `cliente`.

- **`Conceitos-Avançados`**: Exemplos práticos de comandos SQL e `Constraints`.
  - **`30-09-24-Bancodedados-CONSTRAINS.txt`**: Demonstra o uso de `Constraints` como `NOT NULL`, `UNIQUE`, `DEFAULT`, `ENUM` e `CHECK` em uma tabela de `usuario`.
  - **`aula_insert_anotacoes.txt`**: Um banco de dados para um sistema bancário (`banco_haylabank`). Este script inclui exemplos de `ALTER TABLE` para adicionar e remover colunas, renomear tabelas e colunas, e também comandos `INSERT`, `UPDATE` e `DELETE`.

---

### Como Usar

Para executar qualquer um desses scripts, siga os passos abaixo:

1.  Clone este repositório para sua máquina local.
2.  Abra o arquivo `.txt` desejado em seu SGBD (Sistema Gerenciador de Banco de Dados) de preferência (ex: MySQL Workbench, DBeaver, etc.).
3.  Execute os comandos SQL linha por linha ou em blocos para recriar as tabelas e popular os dados.

Sinta-se à vontade para explorar os scripts, adaptar o código e utilizá-los como base para seus próprios estudos.
