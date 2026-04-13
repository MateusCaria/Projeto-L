PROJETO-L — INSTALAÇÃO COMPLETA

1) REQUISITOS
- Node.js instalado
- XAMPP instalado
- MySQL do XAMPP iniciado

2) BANCO DE DADOS
- Abra o phpMyAdmin
- Crie/importe o banco usando o arquivo:
  server/banco.sql

3) INSTALAR DEPENDÊNCIAS
Na pasta do projeto, rode:

npm install

4) INICIAR O BACKEND
Rode:

npm start

O servidor sobe em:
http://localhost:3000

5) ABRIR O SISTEMA
Abra no navegador:
http://localhost:3000

6) CONFIGURAÇÃO PADRÃO DO MYSQL
O projeto está configurado para:
- host: localhost
- user: root
- password: (vazio)
- database: painel_clientes

Se seu XAMPP estiver diferente, edite:
- scripts/server.js

7) CORREÇÃO APLICADA NESTA VERSÃO
- corrigido problema dos gráficos do dashboard
- removida função duplicada que sobrescrevia a renderização dos gráficos
- removidas chamadas duplicadas de recarregamento do dashboard
- package.json incluído na raiz para funcionar com npm install

8) ARQUIVOS PRINCIPAIS
- package.json
- scripts/server.js
- scripts/dashboard.js
- dashboard.html
- server/banco.sql
