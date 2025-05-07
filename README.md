Jogo de Perguntas - CRUD
Este é um jogo de perguntas no estilo "Perguntados", onde os jogadores escolhem um tema e respondem a perguntas relacionadas. Todos os jogadores têm a permissão para editar ou excluir perguntas, sem a necessidade de um administrador. O sistema permite uma personalização contínua, com perguntas atualizadas pela própria comunidade de jogadores.

🛠 Tecnologias Usadas
Frontend: React

Backend: Node.js, Express

Banco de Dados: MongoDB (ou qualquer banco que você escolher)

Autenticação: (se houver) JWT, ou sessão de usuário simples

Ferramentas de Desenvolvimento: Postman, Nodemon, React Developer Tools

⚙️ Funcionalidades
1. Escolha de Tema
O jogador pode escolher um tema entre várias opções, como Geografia, História, Esportes, etc.

2. Respostas às Perguntas
Uma vez que o tema é escolhido, o jogador pode responder a perguntas relacionadas a esse tema. As perguntas são retiradas da base de dados e exibidas de maneira aleatória.

3. Edição e Exclusão de Perguntas
Qualquer jogador pode editar ou excluir perguntas. Não há um administrador para gerenciar as perguntas, e todos podem contribuir para melhorar o conteúdo do jogo.

4. Página de Edição
Existe uma página onde o jogador pode editar ou excluir perguntas existentes, podendo modificar texto, adicionar novas alternativas ou mudar o tema de uma pergunta.

5. API CRUD
A aplicação se comunica com uma API backend (Node.js/Express) para realizar as operações CRUD (Create, Read, Update, Delete) nas perguntas e temas.

🧑‍💻 Como Rodar o Projeto
1. Clonar o Repositório
Clone o repositório para sua máquina local:

bash
Copiar
Editar
git clone https://github.com/seu-usuario/nome-do-repositorio.git
cd nome-do-repositorio
2. Instalar Dependências
No diretório do projeto, instale as dependências necessárias para o frontend e backend.

Para o frontend:
bash
Copiar
Editar
cd frontend
npm install
Para o backend:
bash
Copiar
Editar
cd backend
npm install
3. Iniciar o Servidor Backend
Dentro da pasta backend, inicie o servidor Express:

bash
Copiar
Editar
npm run dev
Isso iniciará o servidor com Nodemon para detectar alterações no código e reiniciar automaticamente.

4. Iniciar o Frontend
Dentro da pasta frontend, inicie o React:

bash
Copiar
Editar
npm start
A aplicação estará disponível em http://localhost:3000.

5. Testar API
Use ferramentas como Postman ou Insomnia para testar as rotas da API do backend, como:

GET /api/questions para listar as perguntas.

POST /api/questions para adicionar uma nova pergunta.

PUT /api/questions/:id para editar uma pergunta.

DELETE /api/questions/:id para excluir uma pergunta.


📌 Observações
O banco de dados utilizado no projeto pode ser MongoDB, mas você pode trocar por MySQL ou SQLite conforme sua preferência.

O projeto permite atualizações em tempo real de perguntas, e as alterações podem ser vistas por todos os jogadores imediatamente após o envio de uma atualização.
