<h1>Sistema de trechos, utilizei o Framework Laravel 9 com Inertia.js e PHP 8. Para o FRONT-END Vue Composition API e o banco de dados MySQL.</h1>

<h3>Descrição do Sistema:</h3>

<h2>Sistema será utilizado para o cadastro e gerenciamento de trechos de uma determinada rodovia. </h2>

 <p>Requisitos</p>

- PHP 7.1 ou superior
- Composer
- MySQL
- Node.js com npm ou yarn

## Instalação

1. **Clone o Repositório:**

   ```bash
   git clone https://github.com/seu-usuario/track_movement.git
   cd track_movement

1- Instale as Dependências do Backend:
<h1>Copiar código</h1>
composer install
Instale as Dependências do Frontend:

bash
Copiar código
npm install
ou, se você estiver usando Yarn:

bash
Copiar código
yarn install
Configurar o Banco de Dados:

Copie o arquivo .env.example para .env:

bash
Copiar código
cp .env.example .env
Configure suas credenciais de banco de dados no arquivo .env:

env
Copiar código
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=track_movement
DB_USERNAME=seu_usuario
DB_PASSWORD=sua_senha
Gere a chave da aplicação:

bash
Copiar código
php artisan key:generate
Execute as migrações para criar as tabelas:

bash
Copiar código
php artisan migrate
Compilar os Arquivos do Frontend:

bash
Copiar código
npm run dev
ou, se estiver usando Yarn:

bash
Copiar código
yarn dev
Iniciar o Servidor:

Para iniciar o servidor de desenvolvimento:

bash
Copiar código
php artisan serve
O sistema estará disponível em http://localhost:8000.

Testes
Execute os testes para garantir que o sistema está funcionando corretamente:

bash
Copiar código
php artisan test
