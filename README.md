# Sistema_de_Gerenciamento_de_Estoques

📦 Sistema de Gerenciamento de Estoque e Vendas (Python + SQLite)

Este projeto é um sistema completo de gerenciamento de estoque, vendas e usuários, desenvolvido em Python, utilizando SQLite como banco de dados local.
Ele foi pensado para simular um ambiente real de controle comercial, aplicando conceitos de CRUD, persistência de dados, segurança básica, relatórios financeiros e controle de acesso por login.

O sistema funciona totalmente via terminal, sendo ideal para fins educacionais, pequenos comércios ou como base para evolução em projetos maiores (GUI, Web ou API).

🚀 Funcionalidades Principais
🔐 Autenticação e Segurança

Cadastro e login de usuários

Senhas armazenadas com hash SHA-256

Controle de usuário logado nas operações

Registro de data/hora das ações

📦 Gestão de Produtos (CRUD Completo)

Cadastro, edição e exclusão de produtos

Controle de preço de custo e venda

Controle de quantidade em estoque

Alerta automático de estoque baixo

Registro de peso e marca dos produtos

📥📤 Controle de Estoque

Entrada de estoque

Saída de estoque

Validação de estoque insuficiente

Registro automático de movimentações

Histórico completo de entradas, saídas e vendas

🧾 Registro de Vendas

Registro de vendas com:

Produto

Quantidade

Forma de pagamento

Cliente/consumidor

Atualização automática do estoque

Cálculo de valor total da venda

Registro da movimentação como “saída - venda”

👥 Clientes e Fornecedores

Cadastro de clientes

Cadastro de fornecedores

Listagem de clientes e fornecedores

📊 Relatórios

Listagem de produtos

Histórico de vendas

Relatório financeiro com:

Total vendido

Custo total

Lucro estimado

🗄️ Estrutura do Banco de Dados

O sistema utiliza SQLite e cria automaticamente as tabelas:

produtos

vendas

movimentacoes

clientes

fornecedores

usuarios

Além disso, o sistema insere produtos padrão automaticamente na primeira execução.

🛠️ Tecnologias Utilizadas

Python 3

SQLite

Biblioteca sqlite3

Biblioteca hashlib

Biblioteca datetime

🎯 Objetivo do Projeto

Este projeto foi desenvolvido com foco em:

Prática de lógica de programação

Manipulação de banco de dados relacional

Organização de código em funções e módulos

Simulação de um sistema real de gestão

Consolidação de conceitos fundamentais de backend


👨‍💻 Autor

Kaio Richard Amaral Lisboa
Estudante de Tecnologia | Python | Banco de Dados | Sistemas
