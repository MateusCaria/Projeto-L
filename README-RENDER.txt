COMO SUBIR NO RENDER

1. Crie um repositório no GitHub e envie esta pasta.
2. No Render, clique em New + Web Service.
3. Conecte o repositório.
4. O Render deve detectar:
   Build Command: npm install
   Start Command: npm start
5. Crie as variáveis de ambiente abaixo:
   PORT=10000
   DB_HOST=SEU_HOST
   DB_PORT=3306
   DB_USER=SEU_USUARIO
   DB_PASSWORD=SUA_SENHA
   DB_NAME=SEU_BANCO
   DB_SSL=true (se o banco exigir SSL)
6. Faça o deploy.

IMPORTANTE
- Não envie node_modules para o GitHub.
- Não envie o arquivo .env real.
- O projeto já está configurado para servir o frontend pelo próprio Node.
