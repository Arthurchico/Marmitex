# Projeto-Lucas
## 🥗 APS – Sistema de Marmitas Sustentáveis  

## 🎯 Objetivo
Uma aplicação web para **cadastro de clientes, marmitas e pedidos**, incentivando alimentação saudável e sustentável.  

---

## 👥 Equipe
- **Miguel Loureiro **– Dev Back-end (Django, Banco de Dados)  
- **Arthur Francisco ** – Dev Front-end (HTML, CSS, Bootstrap/Tailwind)  
- **Pedro Avellar** – QA/Testes, Documentação, Deploy Azure  
---

## 📌 Funcionalidades Principais
1. Cadastro/Login de Usuário (cliente e admin)  
2. Gestão de Marmitas (admin cadastra, clientes visualizam)  
3. Pedidos (seleção de marmitas, acompanhamento de status)  
4. Planos de Assinatura (semanal ou mensal)  
5. Dashboard (clientes e admin com visões diferentes)  

---

## 🗂 Histórias de Usuário
> Definidas com base nos **3Cs (Claras, Concisas e de Valor)**  

-Cadastro de Conta

Card: Como cliente, quero me cadastrar para acessar o sistema.

Conversation: Preencho nome, email e senha.

Confirmation: Dados gravados no banco (tabela Usuário).


-Login no Sistema


Card: Como cliente, quero fazer login para acessar minhas funcionalidades.

Conversation: Digito email e senha.

Confirmation: Autenticação validada no banco.


-Editar Perfil


Card: Como cliente, quero atualizar meus dados pessoais.

Conversation: Altero email, nome ou senha.

Confirmation: Alterações salvas na tabela Usuário.


-Escolher Marmitas


Card: Como cliente, quero visualizar marmitas e adicioná-las ao meu pedido.

Conversation: Navego pelo catálogo, clico em “adicionar”.

Confirmation: Itens registrados em Itens do Pedido.

-Fazer Pedido


Card: Como cliente, quero confirmar meu pedido para receber as marmitas.

Conversation: Escolho quantidade e finalizo.

Confirmation: Pedido salvo na tabela Pedido com status “pendente”.


-Visualizar Histórico de Pedidos

Card: Como cliente, quero ver pedidos anteriores.

Conversation: Abro meu dashboard.

Confirmation: Dados lidos da tabela Pedido.


-Assinar Plano

Card: Como cliente, quero contratar um plano semanal ou mensal.

Conversation: Escolho plano e duração.

Confirmation: Registro em Plano.


Histórias do Admin

-Cadastrar Marmitas

Card: Como admin, quero cadastrar novas marmitas no sistema.

Conversation: Preencho nome, calorias, preço e foto.

Confirmation: Marmita salva em Marmita.


-Gerenciar Pedidos

Card: Como admin, quero atualizar o status dos pedidos.

Conversation: Mudo de “pendente” para “em preparo” → “entregue”.

Confirmation: Status atualizado na tabela Pedido.


-Visualizar Relatórios

Card: Como admin, quero ver total de marmitas vendidas e clientes ativos.

Conversation: Acesso dashboard.

Confirmation: Dados agregados lidos das tabelas Pedido e Usuário.
---

## 📊 Priorização das Entregas
- **Alta (MVP)**  
  - Cadastro/Login de Usuário  
  - Gestão de Marmitas  
  - Pedido (criação e status)  

- **Média**  
  - Dashboard básico  
  - Histórico de pedidos  

- **Baixa (pós-MVP)**  
  - Planos de Assinatura  
  - Dashboard avançado (gráficos, métricas detalhadas)  

---

## 🧑‍💻 Papéis da Equipe
- **PO/Scrum Master** → Organização no Trello/Jira, definição de histórias, comunicação com professor.  
- **Dev Back-end** → Modelos Django, banco de dados, API.  
- **Dev Front-end** → Templates Django, HTML, CSS, responsividade.  
- **QA/DevOps** → Testes unitários, documentação, deploy no Azure.  

---

## 📋 Organização
- **Trello** → Backlog com as histórias priorizadas.  
- **GitHub** → Repositório público com este README e código-fonte.  

📎 **Print do Trello aqui**  

---

## 🚀 Stack Tecnológica
- **Back-end**: Python + Django (sem Generic Views nem Django Forms)  
- **Banco de Dados**: SQLite (desenvolvimento) / PostgreSQL (produção)  
- **Front-end**: HTML, CSS (Bootstrap/Tailwind)  
- **Deploy**: Azure  

---
