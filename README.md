# API Coleta de Clientes - MeggaPainel

Automação que coleta dados de clientes usando Puppeteer e disponibiliza via API REST.

## 🚀 Endpoints

- `GET /` - Informações da API
- `GET /clientes` - Retorna todos os clientes
- `GET /status` - Status do cache
- `GET /atualizar` - Força nova coleta
- `GET /clientes-app` - Dados formatados para app
- `GET /limpar-cache` - Limpa e regenera cache

## 🌐 Deploy no Render.com

1. Acesse https://render.com e faça login com GitHub
2. Clique em "New +" → "Web Service"
3. Selecione este repositório
4. Configure:
   - **Build Command**: `npm install`
   - **Start Command**: `npm start`
5. Adicione as variáveis de ambiente:
   - `USER_EMAIL`: seu email
   - `USER_PASSWORD`: sua senha
6. Clique em "Create Web Service"

Pronto! Sua API estará no ar em poucos minutos.

## 🔧 Instalação Local
