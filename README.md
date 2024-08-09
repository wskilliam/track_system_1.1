<h1>Sistema de trechos</h1>

<h2>Descrição do Sistema:</h2>

<h4>Sistema será utilizado para o cadastro e gerenciamento de trechos de uma determinada rodovia. </h4>

<p>Requisitos</p>

- PHP 7.1 ou superior
- Composer
- MySQL
- Node.js com npm ou yarn

## Instalação ##

1. **Clone o Repositório:**

````
git clone https://github.com/wskilliam/track_system_1.1.git
````
2. **Instale as Dependências do Backend:**

_Copiar código:_

````
composer install
````

3. **Instale as Dependências do Frontend:**

_Copiar código:_
````
npm install
````

4. **Configurar o Banco de Dados:**

_Copie o arquivo .env.example para .env:_

_Copiar código:_
````
cp .env.example .env
`````

_Configure suas credenciais de banco de dados no arquivo **.env**:__

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
