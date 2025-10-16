# Marmitex
## 🥗 Sistema de Marmitas Sustentáveis  

![Texto Alternativo](https://cdn-icons-png.flaticon.com/512/4310/4310157.png)

## 🎯 Objetivo

O nosso projeto está sendo desenvolvido com o intuito de auxiliar pessoas que não dispõem de tempo para preparar refeições saudáveis no dia a dia. A aplicação web responsiva permitirá que os usuários realizem cadastro, escolham opções de marmitas balanceadas e efetuem pedidos de forma prática, tanto pelo computador quanto pelo celular. Além disso, a plataforma visa promover a adoção de hábitos alimentares mais saudáveis, oferecendo uma solução acessível, conveniente e integrada ao cotidiano dos usuários.

---

## 👥 Equipe
- **Miguel Loureiro**
- **Arthur Francisco** 
- **Pedro Avellar** 
---

## 📌 Funcionalidades 
1. Cadastro/Login de Usuário (cliente e admin)  
2. Gestão de Marmitas (admin cadastra, clientes visualizam)  
3. Pedidos (seleção de marmitas, acompanhamento de status)  

---
⚙️ **Ferramentas tecnológicas**  
Para o desenvolvimento desse projeto utilizamos:

- [Trello](https://trello.com/invite/b/68b609f840b24b48824d8958/ATTI7d213796891627f40f024f6adac0715a59762156/marmitex): utilizado para gestão do projeto;
- [Figma](https://www.figma.com/design/teISHJKOZdnJXc4PcsHMz0/Marmitex?node-id=3-5&t=pribS653T5Ew2jtC-0): utilizado para prototipação.

---
🪟Diagrama de atividades do sistema

[Diagrama de atividades](https://www.canva.com/design/DAGzXAC2rGU/Z5S40FJHBrG6fbi9pfS5Mg/edit?utm_content=DAGzXAC2rGU&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton)

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

📎 **Print do Trello aqui**  

---

## 🚀 Stack Tecnológica (Aplicação Web – alternativa)

📌 Tecnologias Utilizadas

Linguagem/Framework (Front-end e Back-end): HTML + CSS e JavaScript

Banco de Dados Local (teste/desenvolvimento): SQLite (via biblioteca better-sqlite3 ou similar)

---
