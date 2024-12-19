# Petshop Database

Este repositório contém o esquema de banco de dados e os dados iniciais para um sistema de gerenciamento de um petshop, incluindo tabelas e comandos de inserção, além da criação de relátorios, incluindo análise de métricas, visualização de informações relevantes e insights para tomada de decisão.

## Estrutura do Projeto

- **Tabelas SL.sql**: Contém o esquema do banco de dados, incluindo definição de tabelas, restrições e relações.
- **Inserts SL.sql**: Inclui dados iniciais para as tabelas do banco, como clientes, produtos, serviços e outros.
- **Relátorios SL.sql**: Contém relátorios gerados a partir de dados presentes no banco.

## Requisitos

Para executar este projeto, você precisará de:

- MySQL Server
- MySQL Workbench ou outro cliente para gerenciar o banco de dados

## Instalação e Uso

### 1. Importar o Esquema do Banco de Dados

1. Abra o arquivo `Tabelas SL.sql` em seu cliente MySQL.
2. Execute os comandos SQL para criar o esquema do banco de dados.

### 2. Inserir Dados Iniciais

1. Abra o arquivo `Inserts SL.sql` em seu cliente MySQL.
2. Execute os comandos para popular o banco de dados com os dados iniciais.

### 3. Criação de relatórios 

1. Abra o arquivo `Relatórios SL.sql` em seu cliente MySQL.
2. Execute os comandos de select para receber relátorios sobre os dados presentes no banco.

## Estrutura do Banco de Dados

O banco de dados inclui as seguintes tabelas principais:

### Tabelas

- **CLIENTE**: Armazena informações sobre os clientes, incluindo CPF, nome, telefones e e-mail.
- **PRODUTO**: Detalha produtos vendidos no petshop.
- **SERVICO**: Lista os serviços oferecidos pelo petshop.
- **AGENDAMENTO**: Registra agendamentos realizados por clientes.
- **ANIMAL**: Contém informações sobre os animais cadastrados pelos clientes.
- **FUNCIONARIO**: Inclui informações sobre os funcionários do petshop.

## Como Usar

### Requisitos
1. Ter o **MySQL** instalado em seu computador.
2. Um ambiente de desenvolvimento para executar comandos SQL.

### Passos para Instalar

1. Clone este repositório:
   ```bash
   git clone https://github.com/MatHenriqueAssis/BDII-Pet-Shop.git


