🧠 Jogo de Curiosidades - CRUD
Este projeto é um jogo de curiosidades no estilo interativo, onde os jogadores escolhem um tema e recebem curiosidades relacionadas. Diferente de jogos tradicionais de perguntas e respostas, não há alternativas nem pontuação — o objetivo é explorar e aprender de forma leve e divertida.

Todos os jogadores podem adicionar, editar ou excluir curiosidades, criando um ambiente colaborativo de conhecimento. Não existe um administrador: o conteúdo é gerenciado pela própria comunidade.

🛠 Tecnologias Utilizadas
Frontend: React.js

Backend: Node.js + Express

Banco de Dados: MongoDB

Ambiente de Desenvolvimento: IntelliJ, Docker e Postman

⚙️ Funcionalidades
Escolha de Tema
Os jogadores escolhem um tema como História, Tecnologia, Natureza, entre outros.

Exibição de Curiosidades
Após escolher um tema, são exibidas curiosidades associadas, vindas diretamente do banco de dados.

CRUD de Curiosidades
Todos os jogadores podem criar novas curiosidades, editar ou excluir as existentes.

Edição Aberta e Colaborativa
Não há login obrigatório nem permissões especiais: qualquer usuário pode modificar o conteúdo.

API RESTful
A aplicação se comunica com uma API construída com Express para realizar todas as operações de criação, leitura, atualização e exclusão.

🚀 Como Rodar o Projeto
1. Clone o repositório
bash
Copiar
Editar
git clone https://github.com/seu-usuario/nome-do-repositorio.git
cd nome-do-repositorio
2. Instale as dependências
Frontend:

bash
Copiar
Editar
cd frontend
npm install
Backend:

bash
Copiar
Editar
cd backend
npm install
3. Configure o ambiente
Certifique-se de que o MongoDB esteja rodando localmente ou via Docker. Exemplo com Docker:

bash
Copiar
Editar
docker run --name curiosidades-mongo -p 27017:27017 -d mongo
4. Inicie os servidores
Backend (com Nodemon):

bash
Copiar
Editar
cd backend
npm run dev
Frontend:

bash
Copiar
Editar
cd frontend
npm start
A aplicação estará disponível em: http://localhost:3000

🔌 Endpoints da API
GET /api/curiosidades – Lista todas as curiosidades

POST /api/curiosidades – Cria uma nova curiosidade

PUT /api/curiosidades/:id – Edita uma curiosidade existente

DELETE /api/curiosidades/:id – Exclui uma curiosidade

📌 Observações
O projeto usa MongoDB, mas pode ser adaptado para outros bancos como MySQL ou SQLite.

Todas as alterações feitas nas curiosidades são atualizadas em tempo real para todos os usuários.

Este projeto é ideal para aprender conceitos de CRUD, colaboração aberta e integração entre frontend e backend.

