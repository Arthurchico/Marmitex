---
name: Erro ao trocar senha
about: Reporte um problema ao tentar trocar a senha de usuário (relacionado ao banco de dados)
title: "[BUG] Erro ao trocar senha"
labels: bug
assignees: ''

---

### 🐛 Descrição do erro
Um usuário relatou que está enfrentando problemas ao tentar trocar a senha. A operação falha e retorna um erro relacionado ao banco de dados. Isso impede a atualização correta da senha no sistema.

---

🔁 Como reproduzir o erro

Passos para reproduzir o erro:

Inicie o servidor local com o comando:

node server.js


Acesse a aplicação no navegador (http://localhost:3000).

Passos para reproduzir o erro:

Inicie o servidor local com o comando:

node server.js

Acesse a aplicação no navegador (por exemplo: http://localhost:3000).

Vá até a tela de login.

Clique no botão "Esqueci minha senha".

Você será redirecionado para a tela de recuperação de senha.

Nessa tela, informe:

Um e-mail válido já cadastrado no sistema.

A palavra-chave secreta definida previamente pelo usuário.

Clique para confirmar os dados.

⚠️ O erro ocorre após essa tentativa de validação. O sistema tenta consultar ou validar os dados no banco de dados e falha, impedindo o avanço para a próxima etapa (tela de redefinição de senha).

O erro pode ser exibido:

Na interface.

No terminal/backend (mensagem relacionada a falha de consulta ou conexão com o banco de dados, especialmente na tabela de users).
