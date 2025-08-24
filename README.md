# Essencial Fidelidade 💚

Aplicativo web de Cartão Fidelidade digital desenvolvido para a clínica **Essencial Saúde e Estética**. Os clientes acumulam carimbos a cada compra e recebem uma recompensa ao completar 10 selos. O sistema também inclui um painel administrativo para gerenciamento dos usuários.

---

## 🧩 Funcionalidades

- Cadastro e login de clientes
- Registro de compras com carimbos digitais
- Recompensa automática ao completar 10 carimbos
- Painel administrativo com lista de usuários e opção de resetar cartões
- Interface responsiva e intuitiva
- Suporte offline via PWA (Progressive Web App)
- Integração com Firebase para banco de dados em tempo real

---

## 🚀 Tecnologias Utilizadas

- HTML5 / CSS3 / JavaScript
- Firebase Realtime Database
- Firebase Hosting
- Service Worker
- Manifest PWA

---

## 📦 Estrutura do Projeto

essencial-fidelidade/ ├── public/ │ ├── index.html │ ├── style.css │ ├── script.js │ ├── manifest.json │ ├── service-worker.js │ └── assets/ │ ├── logo.png │ ├── icon-192x192.png │ └── icon-512x512.png ├── .gitignore ├── .gitattributes ├── .env (não enviado ao GitHub) └── README.md


---

## 🔐 Segurança

- Dados sensíveis como `.env` e `firebase-adminsdk.json` estão protegidos via `.gitignore`
- Senhas não são armazenadas em texto plano (recomenda-se Firebase Authentication)
- Acesso ao painel administrativo restrito por login

---

## 📲 Como testar localmente

1. Clone o repositório:
   ```bash
   git clone https://github.com/ThiagoVieira04/essencial-fidelidade.git
Instale o Firebase CLI:

bash
npm install -g firebase-tools
Inicie o servidor local:

bash
firebase serve
🛠️ Deploy
Este projeto está hospedado via Firebase Hosting. Para publicar:

bash
firebase deploy
📌 Autor
Thiago Vieira 📍 Magé, RJ – Brasil 🔗 github.com/ThiagoVieira04

📄 Licença
Este projeto está sob a licença MIT.

Código

---

## 📁 `.gitignore`

```bash
# Firebase e variáveis de ambiente
.env
firebase-adminsdk.json
serviceAccountKey.json

# Node.js (se usar Firebase CLI)
node_modules/

# IDEs e sistema
.vscode/
.idea/
.DS_Store
Thumbs.db

# Logs
*.log
npm-debug.log*
yarn-debug.log*
yarn-error.log*

# Build e cache
dist/
build/
.cache/
📁 .gitattributes
gitattributes
# Normaliza line endings para LF em todos os sistemas
* text=auto eol=lf