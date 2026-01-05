<div align="center">

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![SQLite](https://img.shields.io/badge/Database-SQLite-lightgrey?logo=sqlite)
![Status](https://img.shields.io/badge/Status-Concluído-success)
![License](https://img.shields.io/badge/License-MIT-green)

</div>

# 📦 Sistema de Gerenciamento de Estoque e Vendas


## 📝 Descrição

Sistema completo de **gerenciamento de estoque e vendas**, desenvolvido em **Python**, utilizando **SQLite** como banco de dados local.

O projeto simula um ambiente real de controle comercial, aplicando conceitos de **CRUD**, **persistência de dados**, **controle de usuários**, **relatórios financeiros** e **segurança básica com hash de senha**.

O sistema é executado via **terminal**, sendo ideal para estudos, pequenos comércios ou como base para evolução em aplicações maiores.


## 🚀 Funcionalidades


### 🔐 Autenticação
- Cadastro e login de usuários  
- Senhas criptografadas com SHA-256  
- Controle de usuário logado  
- Registro de data e hora das operações  


### 📦 Produtos
- Cadastro, edição e exclusão de produtos  
- Controle de preço de custo e venda  
- Controle de quantidade em estoque  
- Alerta automático de **estoque baixo**  
- Registro de peso e marca  


### 📥📤 Controle de Estoque
- Entrada de produtos  
- Saída de produtos  
- Validação de estoque insuficiente  
- Registro automático de movimentações  


### 🧾 Registro de Vendas
- Registro de vendas com:
  - Produto
  - Quantidade
  - Forma de pagamento
  - Cliente/consumidor  
- Atualização automática do estoque  
- Cálculo do valor total da venda  


### 👥 Clientes e Fornecedores
- Cadastro de clientes  
- Cadastro de fornecedores  
- Listagem de clientes e fornecedores  


### 📊 Relatórios
- Listagem completa de produtos  
- Histórico de vendas  
- Relatório financeiro com:
  - Total vendido  
  - Custo total  
  - Lucro estimado  


## 🗄️ Banco de Dados

O sistema utiliza **SQLite** e cria automaticamente as seguintes tabelas:

- produtos  
- vendas  
- movimentacoes  
- clientes  
- fornecedores  
- usuarios  

Além disso, produtos padrão são inseridos automaticamente na primeira execução do sistema.


## 🛠️ Tecnologias Utilizadas

- Python 3  
- SQLite  
- sqlite3  
- hashlib  
- datetime  


## 🎯 Objetivo do Projeto

Este projeto foi desenvolvido com foco em:

- Prática de lógica de programação  
- Manipulação de banco de dados relacional  
- Organização de código em funções  
- Simulação de um sistema real de gestão comercial  
- Consolidação de conceitos fundamentais de backend  


## 📌 Possíveis Evoluções Futuras

- Interface gráfica (Tkinter ou PyQt)  
- API REST (Flask ou FastAPI)  
- Interface Web  
- Controle de permissões por usuário  
- Exportação de relatórios (PDF / Excel)  
- Migração para PostgreSQL ou MySQL  


## 👨‍💻 Autor

**Kaio Richard Amaral Lisboa**  
Estudante de Tecnologia | Python | Banco de Dados | Sistemas
