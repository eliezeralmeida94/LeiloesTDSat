Projeto Casa de Leilões – Atividade 2
Aluno: Eliezer
Curso: Técnico em Desenvolvimento de Sistemas – UC11
Atividade: Atividade 2 – Cadastro e Listagem de Produtos com Git e Relatório

Objetivo
O objetivo desta atividade foi criar um sistema Java com interface gráfica que permitisse:
- Cadastro de produtos (nome, valor e status)
- Salvamento em banco de dados (MySQL)
- Listagem dos produtos cadastrados
- Controle de versionamento com Git
- Relatório com evidências (prints e repositório remoto)

 Tecnologias Utilizadas
- Java (NetBeans IDE)
- Swing (Interface Gráfica)
- JDBC (Conexão com MySQL)
- MySQL (Banco de Dados `uc11`, tabela `produtos`)
- Git e GitHub (Versionamento e repositório remoto)

Funcionalidades
- Tela de cadastro de produtos
- Conexão com banco de dados MySQL (`localhost`)
- Listagem automática dos produtos na interface
- Validação básica de campos
- Mensagens de sucesso e erro

Como Executar
1. Abra o projeto no NetBeans.
2. Execute a classe `CadastroView.java` para iniciar o sistema.
3. Preencha os campos de nome e valor do produto e clique em Cadastrar.
4. Os produtos cadastrados serão exibidos automaticamente na tabela.
5. O banco utilizado está configurado para `uc11`, com a tabela `produtos`.

Banco de Dados
CREATE DATABASE IF NOT EXISTS uc11;
USE uc11;

CREATE TABLE produtos (
  id BIGINT UNSIGNED AUTO_INCREMENT PRIMARY KEY,
  nome TEXT,
  valor INT,
  status TEXT
);

GitHub
- Repositório remoto: https://github.com/eliezeralmeida94/LeiloesTDSat.git
- Contém todos os commits e histórico de alterações.
